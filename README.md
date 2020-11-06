# 4G_Handover_Verification

This repository is a for the formal verification files of the 4G handover procedures of X2 and S1.

## X2 File Structure

The X2 folder contains the following proverif files:

- X2.pv
- X2patched.pv

The files above contain a main process with just one session of the following entities: UE, source Node, target Node and MME. The "X2.pv" file encodes the original X2 protocol and the "X2patched.pv" file encodes our new, secure version of X2.

- X2_ndevices.pv
- X2_ndevices_patched.pv

The files above contain a main process with multiple entities UE, source Node, target Node and MME, adn/or multiple sessions thereof. The "X2_ndevices.pv" file encodes the original X2 protocol and the "X2_ndevices_patched.pv" file encodes our new, secure version of X2, in this setting.

The following file is for the forward secrecy attack on the X2 protocol:

- X2_forwardSecrecy.pv

## S1 File Structure

The S1 folder contains the following proverif files:

-S1.pv
-S1patched.pv

The files above contain a main process with just one session of the following entities: UE, source Node, target Node and MME. The "S1.pv" file encodes the original S1 protocol and the "S1patched.pv" file encodes our new, secure version of S1.

- S1_ndevices.pv
- S1_ndevices_patched.pv

The files above contain a main process with multiple entities UE, source Node, target Node and MME, adn/or multiple sessions thereof. The "S1_ndevices.pv" file encodes the original S1 protocol and the "S1_ndevices_patched.pv" file encodes our new, secure version of S1, in this setting.

## Traces

This folder contains some exemple of traces for the attacks we found on these LTE handover protocols.

## Submission

These files are in support of a paper being submitted to a conference.