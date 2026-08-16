# Computer Networks — Coursework

Lab work from the **Computer Networks** course at FAST-NUCES — socket programming in Python plus the written lab reports.

## Contents

| File | Topic |
|---|---|
| [`UDP_Server.py`](UDP_Server.py) / [`UDP_Client.py`](UDP_Client.py) | Basic **UDP socket** pair — connectionless send/receive |
| [`q1serverLab6.py`](q1serverLab6.py) / [`q1clientLab6.py`](q1clientLab6.py) | Lab 6, exercise 1 — client/server exchange |
| [`q2serverLab6.py`](q2serverLab6.py) / [`q2clientLab6.py`](q2clientLab6.py) | Lab 6, exercise 2 |
| `CN-Lab2.docx`, `L21-5648-Lab3.pdf`, `Lab 4-21L-5648.pdf` | Lab reports |

## Topics covered

The socket API · UDP vs TCP and when connectionless is the right trade · client/server architecture · packet structure and datagram handling · addressing and ports

## Running the socket examples

Start the server first, then the client in a second terminal:

```bash
python UDP_Server.py
```

```bash
python UDP_Client.py
```

Both default to localhost — edit the host/port constants at the top of each file to run them across machines.
