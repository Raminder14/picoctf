# Challenge: Obedient Cat — General Skills — 5pts
Date: 2026-04-19

## Description
This file has a flag in plain sight (aka "in-the-clear").

## Files / service
flag (no extension, plain file)

## Recon
- file type: ASCII text
- strings output: flag visible directly
- observations: no encoding, no encryption, flag in plain text

## Attempts
1. file flag → ASCII text
2. strings flag → picoCTF{s4n1ty_v3r1f13d_9b8fa0bc}

## Solution
Flag was stored as plain readable text inside the file. strings dumped it immediately.

## Flag
picoCTF{s4n1ty_v3r1f13d_9b8fa0bc}

## Key technique
Always run strings on any unknown file first — if flag is in plain text it appears instantly.

## Time taken
~2 min
## Resource used
None
