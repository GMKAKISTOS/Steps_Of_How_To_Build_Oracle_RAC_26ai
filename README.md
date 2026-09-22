# Oracle RAC 26ai Project

This is a simple Oracle project created to practice and learn how to install and configure Oracle Real Application Clusters (RAC) 26ai on Oracle Linux.

The project demonstrates the main steps required to prepare the operating system, configure the RAC environment, install Oracle Grid Infrastructure, configure ASM and create an Oracle RAC database.

## Technologies

Oracle Database 26ai
Oracle RAC
Oracle Grid Infrastructure
Oracle Clusterware
Oracle ASM
Oracle Linux
Linux Shell
SSH
DNS / SCAN
Shared Storage

## Project Structure

Steps_Of_How_To_Build_Oracle_RAC_26ai/
│
├── Install_Oracle_RAC_26ai_On_Oracle_Linux/
│   └── Oracle RAC 26ai installation steps
│
├── CREATE_FILES_WITH_PERMISSIONS_FOR_ROOT_USER_GRID_ORACLE_USERS.txt
│   └── Files, permissions and ownership
│
└── README.md

## What This Project Does

The basic process is:

Oracle Linux
    ↓
Operating System Configuration
    ↓
Users and Groups
    ↓
Network Configuration
    ↓
SSH Configuration
    ↓
Shared Storage
    ↓
Oracle Grid Infrastructure
    ↓
Oracle ASM
    ↓
Oracle RAC Database
    ↓
Cluster Validation

The project provides step-by-step instructions for preparing Oracle Linux and building an Oracle RAC 26ai environment.

## What I Learned

While working on this project I practiced:

Installing Oracle RAC
Preparing Oracle Linux for Oracle RAC
Creating Oracle users and groups
Configuring RAC networking
Configuring SSH between RAC nodes
Installing Oracle Grid Infrastructure
Working with Oracle Clusterware
Working with Oracle ASM
Configuring shared storage
Creating an Oracle RAC database
Checking RAC cluster resources
Troubleshooting Oracle RAC installation
Using Oracle RAC administration commands

## Oracle RAC Components

The project covers the main Oracle RAC components:

Grid Infrastructure - Provides the cluster infrastructure

Oracle Clusterware - Manages the RAC cluster and resources

Oracle ASM - Manages shared database storage

Oracle RAC Database - Provides the clustered database environment

SCAN / VIP - Provides RAC network connectivity

## Useful Commands

Check cluster status:

crsctl check cluster -all

Check cluster resources:

crsctl status resource -t

Check ASM disk groups:

asmcmd lsdg

Check database status:

srvctl status database

Check RAC instances:

srvctl status instance

## Requirements

To run or follow this project you need:

Oracle Linux
Oracle Database 26ai
Oracle Grid Infrastructure
At least two RAC nodes
Shared storage
Network connectivity between the nodes
DNS or hostname resolution
Root access
Grid user
Oracle user
The required permissions for Oracle RAC installation

## Purpose

This project was created mainly for learning and practicing Oracle RAC, Oracle Database Administration, Oracle Grid Infrastructure, Oracle ASM and Linux Administration.

It can also be used as a simple reference for anyone who is starting to learn Oracle RAC installation and configuration.

## Important Note

This project is intended for learning and testing purposes.

Oracle RAC installation requirements can vary depending on the Oracle Database version, Oracle Linux version, network configuration, storage configuration and infrastructure.

Always check the official Oracle documentation before using the configuration in a production environment.

## Author

Panagiotis Chronopoulos
