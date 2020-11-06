# 4G_Handover_Verification

This repository is a for the formal verification files of the 4G handover procedures of X2 and S1. 

## X2 File Structure

The X2 folder contains the following proverif files:

- X2.pv
- X2patched.pv

These files contain the processes for the following entities: UE, seNode, teNode and MME

- X2_ndevices.pv
- X2_ndevices_patched.pv

These files contain the single processes for the following entities: seNode and MME
Along with multiple processes for the following entities: UE and teNode

The following file is for the forward secrecy attack on the X2 protocol: 

- X2_forwardSecrecy.pv

## S1 File Structure

The S1 folder contains the following proverif files:

- S1.pv
- S1patched.pv

These files contain the processes for the following entities: UE, seNode, teNode and MME

- S1_ndevices.pv
- S1_ndevices_patched.pv

These files contain the single processes for the following entities: seNode and MME
Along with multiple processes for the following entities: UE and teNode

## Traces

This folder contains all of the trace for all the attacks found on the LTE handover protocols.

## Submission

These files are in support of the paper being submitted to a conference.