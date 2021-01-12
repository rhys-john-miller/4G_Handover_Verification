# 4G_Handover_Verification

This repository contains supporting files for the formal verification of 4G handover procedures X2 and S1. 

## 1) Long Version

- LongVersion.pdf

This pdf contains a longer version of the paper submitted.

## 2) X2 File Structure

The X2 folder contains:

- X2.pv
- X2patched.pv

The files above contain a main process with just one session of the following entities: UE, source Node, target Node and MME. The "X2.pv" file encodes the original X2 protocol and the "X2patched.pv" file encodes our new, secure version of X2.

- X2_ndevices.pv
- X2_ndevices_patched.pv

The files above contain a main process with multiple entities UE, source Node, target Node and MME, adn/or multiple sessions thereof. The "X2_ndevices.pv" file encodes the original X2 protocol and the "X2_ndevices_patched.pv" file encodes our new, secure version of X2, in this setting.

The backward secrecy attacks can be found in:

- X2_backwardSecrecy.pv

### Traces

Inside of this folder you will find the supporting traces for each of the queries for all of the X2 ProVerif files.

## 3) S1 File Structure

The S1 folder contains:

- S1.pv
- S1patched.pv

The files above contain a main process with just one session of the following entities: UE, source Node, target Node and MME. The "S1.pv" file encodes the original S1 protocol and the "S1patched.pv" file encodes our new, secure version of S1.

- S1_ndevices.pv
- S1_ndevices_patched.pv

The files above contain a main process with multiple entities UE, source Node, target Node and MME, adn/or multiple sessions thereof. The "S1_ndevices.pv" file encodes the original S1 protocol and the "S1_ndevices_patched.pv" file encodes our new, secure version of S1, in this setting.

### Traces

Inside of this folder you will find the supporting traces for each of the queries for all of the X2 ProVerif files.

## 4) Figures

This folder contains some the figures within the file.

# Submission

These files are in support of a paper being submitted to a conference.