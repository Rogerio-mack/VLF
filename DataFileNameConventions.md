# File Name Conventions
---

A **sample of data is available here**. You can access the same data in a Linux File Server by `sftp` or `wget` (file browser is not allowed).

> https://github.com/Rogerio-mack/VLF/tree/main/data

> https://meusite.mackenzie.br/rogerio/vlf/data

<br>

<br>

## Narrowband Files


Filename: **XXYYMMDDHHMMSSZZZ_ACCT.mat**

* XX – Station ID

* YY – Year

* MM — Month

* DD — Day

* HH — Hour

* MM — Minute

* SS — Second

* ZZZ — Transmitter Callsign

* A — Usually not used

* CC — 00 for N/S channel, 01 for E/W channel

* T — Type of data

* A is low resolution (1 Hz sampling rate) amplitude

* B is low resolution (1 Hz sampling rate) phase

* C is high resolution (50 Hz sampling rate) amplitude

* D is high resolution (50 Hz sampling rate) phase

* F is high resolution (50 Hz sampling rate) effective group delay

Narrowband files available here are in 24-hour blocks, so the start time of all files is 00:00:00 UT, and the end time is 24:00:00 UT. 

## Broadband Files

Filename: **XXYYMMDDHHMMSS_ACC.mat**


* XX – Station ID

* YY – Year

* MM — Month

* DD — Day

* HH — Hour

* MM — Minute

* SS — Second

* A — Sampling rate. 0 for 100 kHz sampled data (VLF), 1 for 1 MHz sampled data (LF), 2 for 25 kHz sampled data (Siple station experiment).

* CC — 00 for N/S channel, 01 for E/W channel
