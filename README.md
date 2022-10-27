{
  "metadata": {
    "language_info": {
      "codemirror_mode": {
        "name": "python",
        "version": 3
      },
      "file_extension": ".py",
      "mimetype": "text/x-python",
      "name": "python",
      "nbconvert_exporter": "python",
      "pygments_lexer": "ipython3",
      "version": "3.8"
    },
    "kernelspec": {
      "name": "python",
      "display_name": "Python (Pyodide)",
      "language": "python"
    }
  },
  "nbformat_minor": 4,
  "nbformat": 4,
  "cells": [
    {
      "cell_type": "code",
      "source": "s=2\nprint(s)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 2,
      "outputs": [
        {
          "name": "stdout",
          "text": "2\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "print(s)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 6,
      "outputs": [
        {
          "name": "stdout",
          "text": "2\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "print ('ABCDEFABFBWUYF'. count (\"F\"))",
      "metadata": {
        "trusted": true
      },
      "execution_count": 8,
      "outputs": [
        {
          "name": "stdout",
          "text": "3\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "a=[1,22,423,61,13,23,14]\nprint (max(a))",
      "metadata": {
        "trusted": true
      },
      "execution_count": 10,
      "outputs": [
        {
          "name": "stdout",
          "text": "423\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "a=[1,22,423,61,13,23,14]\nk=0\nfor i in a:\n    if i%2==0:\n        k+=1\nprint(k)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 12,
      "outputs": [
        {
          "name": "stdout",
          "text": "2\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "k=0\nl=input()\nfor i in a:\n    if l in \"AUYIOE\":\n        k+=1\nprint (k)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 47,
      "outputs": [
        {
          "ename": "<class 'TypeError'>",
          "evalue": "'in <string>' requires string as left operand, not Future",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mTypeError\u001b[0m                                 Traceback (most recent call last)",
            "Cell \u001b[0;32mIn [47], line 4\u001b[0m\n\u001b[1;32m      2\u001b[0m l\u001b[38;5;241m=\u001b[39m\u001b[38;5;28minput\u001b[39m(\u001b[38;5;28mstr\u001b[39m())\n\u001b[1;32m      3\u001b[0m \u001b[38;5;28;01mfor\u001b[39;00m i \u001b[38;5;129;01min\u001b[39;00m a:\n\u001b[0;32m----> 4\u001b[0m     \u001b[38;5;28;01mif\u001b[39;00m \u001b[43ml\u001b[49m\u001b[43m \u001b[49m\u001b[38;5;129;43;01min\u001b[39;49;00m\u001b[43m \u001b[49m\u001b[38;5;124;43m\"\u001b[39;49m\u001b[38;5;124;43mAUYIOE\u001b[39;49m\u001b[38;5;124;43m\"\u001b[39;49m:\n\u001b[1;32m      5\u001b[0m         k\u001b[38;5;241m+\u001b[39m\u001b[38;5;241m=\u001b[39m\u001b[38;5;241m1\u001b[39m\n\u001b[1;32m      6\u001b[0m \u001b[38;5;28mprint\u001b[39m (k)\n",
            "\u001b[0;31mTypeError\u001b[0m: 'in <string>' requires string as left operand, not Future"
          ],
          "output_type": "error"
        },
        {
          "output_type": "stream",
          "name": "stdin",
          "text": " w5ywy\n"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "a=int(input())\nb=int(input())\ns=a*b\nprint(s)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 48,
      "outputs": [
        {
          "name": "stderr",
          "text": "Future exception was never retrieved\nfuture: <Future finished exception=JsException(DataCloneError: Failed to execute 'postMessage' on 'DedicatedWorkerGlobalScope': function(){} could not be cloned.)>\n",
          "output_type": "stream"
        },
        {
          "ename": "<class 'TypeError'>",
          "evalue": "int() argument must be a string, a bytes-like object or a real number, not 'Future'",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mTypeError\u001b[0m                                 Traceback (most recent call last)",
            "Cell \u001b[0;32mIn [48], line 1\u001b[0m\n\u001b[0;32m----> 1\u001b[0m a\u001b[38;5;241m=\u001b[39m\u001b[38;5;28;43mint\u001b[39;49m\u001b[43m(\u001b[49m\u001b[38;5;28;43minput\u001b[39;49m\u001b[43m(\u001b[49m\u001b[38;5;28;43mstr\u001b[39;49m\u001b[43m)\u001b[49m\u001b[43m)\u001b[49m\n\u001b[1;32m      2\u001b[0m b\u001b[38;5;241m=\u001b[39m\u001b[38;5;28mint\u001b[39m(\u001b[38;5;28minput\u001b[39m(\u001b[38;5;28mstr\u001b[39m))\n\u001b[1;32m      3\u001b[0m s\u001b[38;5;241m=\u001b[39ma\u001b[38;5;241m*\u001b[39mb\n",
            "\u001b[0;31mTypeError\u001b[0m: int() argument must be a string, a bytes-like object or a real number, not 'Future'"
          ],
          "output_type": "error"
        }
      ]
    }
  ]
}
