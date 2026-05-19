# Credit Card Processing & Plan Balance Management System

## Overview

This project is a mini Credit Card Processing System developed on Mainframe using COBOL, CICS, VSAM and JCL concepts. The application simulates real-world credit card transaction processing, balance management and transaction history handling.

## Features

* Credit card transaction processing
* Purchase and Cash Withdrawal handling
* Transaction history retrieval
* Credit card validation using Luhn Algorithm
* Dynamic Transaction ID generation
* Plan balance updation through batch processing
* Current Balance and OTB (Open To Buy) management
* CICS BMS screen-based user interaction

## Technologies Used

* COBOL
* CICS
* VSAM KSDS
* JCL
* BMS Maps

## Modules Implemented

### 1. Login & Menu Navigation

* User authentication
* COMMAREA-based screen navigation
* Menu-driven application flow

### 2. Transaction Processing

* Card validation
* Expiry date and CVV validation
* Purchase and Cash Withdrawal transactions
* Transaction record creation

### 3. Transaction History

* VSAM browse using STARTBR / READNEXT
* Display of transaction details on CICS screens
* Scroll-based transaction viewing

### 4. Batch Plan Balance Updation

* Reads transaction file
* Updates Purchase and Cash plan balances
* Updates Principal, Interest, Late Fee and Total balances
* Updates Current Balance and OTB values

## VSAM Files Used

* Account File
* Card File
* Transaction File

## Key Concepts Covered

* Pseudo-conversational CICS programming
* VSAM KSDS file operations
* Generic browse processing
* Batch processing
* Date arithmetic using COBOL intrinsic functions
* Transaction-based balance management

