# Legacy Application Migration to AWS Cloud 

## Executive Summary

This project demonstrates the migration of a traditional on-premises business application to AWS cloud infrastructure.

The migration involved modernizing a legacy web platform by deploying a complete LAMP stack (Linux, Apache, MySQL, PHP) on Amazon EC2 and hosting a WordPress application.

The objective was to improve scalability, reliability, security, and operational efficiency while reducing the maintenance burden associated with on-premises infrastructure.

---

# Business Scenario

Many organizations operate legacy applications on physical servers that require ongoing maintenance, hardware upgrades, manual backups, and limited scalability.

This project simulates a cloud migration initiative where a legacy web application is moved from an on-premises environment into AWS.

Business goals:

* Improve availability
* Reduce infrastructure maintenance
* Enable future scalability
* Increase operational flexibility
* Improve security posture
* Support cloud modernization initiatives

---

# Solution Architecture

The migrated environment consists of:

Users

↓

Amazon EC2

↓

Apache Web Server

↓

PHP Application Layer

↓

MySQL Database

↓

WordPress Application

---

# AWS Services Used

## Compute

* Amazon EC2
* Ubuntu Server 22.04 LTS

## Networking

* Security Groups
* Public IP Access
* Virtual Networking

## Application Layer

* Apache HTTP Server
* PHP Runtime

## Database Layer

* MySQL Database Server

---

# Migration Objectives

This migration focused on:

* Rehosting a legacy application in AWS
* Deploying cloud-based infrastructure
* Implementing secure remote administration
* Creating a repeatable deployment process
* Demonstrating cloud adoption strategies

---

# Environment Configuration

## Operating System

* Ubuntu Server 22.04 LTS

## Web Server

* Apache 2

## Database

* MySQL 8

## Application Platform

* PHP
* WordPress

---

# Migration Process

## Assessment Phase

The existing application architecture was analyzed to identify:

* Application dependencies
* Server requirements
* Database requirements
* Security considerations

## Infrastructure Deployment

AWS infrastructure was provisioned using:

* Amazon EC2
* Security Groups
* SSH Access Controls

## Application Migration

The application stack was deployed:

* Apache installed
* MySQL configured
* PHP installed
* WordPress deployed

## Validation

Application functionality was tested after migration to verify:

* Web accessibility
* Database connectivity
* Application functionality
* Administrative access

---

# Security Implementation

Security controls implemented:

* SSH access restrictions
* Security Group firewall rules
* Least privilege administration
* Secure database configuration

Allowed ports:

| Port | Purpose            |
| ---- | ------------------ |
| 22   | SSH Administration |
| 80   | HTTP               |
| 443  | HTTPS              |

---

# Operational Benefits

Cloud migration provided:

* Reduced infrastructure maintenance
* Faster deployment capabilities
* Improved system availability
* Simplified administration
* Greater scalability opportunities

---

# Technical Skills Demonstrated

Cloud Engineering:

* Amazon EC2
* AWS Networking
* Security Groups
* Cloud Infrastructure Deployment

System Administration:

* Linux Administration
* Apache Configuration
* MySQL Administration
* PHP Configuration

Migration:

* Legacy System Assessment
* Application Migration
* Infrastructure Modernization
* Cloud Adoption Strategy

---

# Lessons Learned

Key takeaways from this project:

* Legacy workloads can be migrated efficiently to AWS.
* Cloud infrastructure simplifies operational management.
* Security should be incorporated during migration planning.
* Proper architecture planning reduces migration risks.

---

# Future Improvements

* Migrate database to Amazon RDS
* Implement Auto Scaling
* Add Application Load Balancer
* Deploy infrastructure using Terraform
* Containerize the application using Docker
* Implement CI/CD automation

---

# Author

Abdon Njunwa

AWS Certified Solutions Architect

Cloud & DevOps Engineer

