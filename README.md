# SC4015 Cyber Physical Security Project - Correlation Power Analysis
This repository is submitted as part of the NTU CCDS course, SC4015 CPS module. This was a group project done by Kopikia, @TheGreatReee, and WeiCocoGoat.

## Project Description
Given a set of power traces (waveform.csv), implement Correlation Power Analysis (CPA) to extract the key. 

## Contents
- CPA_Project_First_byte_extraction.ipynb - Python Script for processing the power traces and running the Correlation Power Analysis attack. Extracts the first byte of the key
- CPA_Project_key_extraction.ipynb - Python Script for processing the power traces and running the Correlation Power Analysis attack. Extracts the full 16 byte key. 
- waveform.csv - A set of 110 power traces
- SC4015 Group Project Report - Submission for the Project Report

## Running the Notebook
- CPA_Project_key_extraction.ipynb: No special instructions are needed. Select Run all and wait for the program to finish running
- CPA_Project_First_byte_extraction.ipynb: This file works on a truncated version of waveform.csv (it uses the first 100 samples). Before running this, remove the bottom 10 rows of waveform.csv manually
