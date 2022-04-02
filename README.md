# 1. Learning Crib Sheet

A drop zone for links and materials around topics I would like to delve into (or am actively looking out through work/play).

- [1. Learning Crib Sheet](#1-learning-crib-sheet)
  - [1.1. Introduction](#11-introduction)
  - [2. Utilities/Helpful Resources](#2-utilitieshelpful-resources)
  - [2.1. The Book of Secret Knowledge](#21-the-book-of-secret-knowledge)
  - [2.2. Awesome .NET!](#22-awesome-net)
  - [2.3. Awesome .NET Core](#23-awesome-net-core)
  - [2.4. Throw library](#24-throw-library)
  - [3. Running Docker on Windows without Docker Desktop](#3-running-docker-on-windows-without-docker-desktop)
  - [3.1 Installing WSL (specific guides)](#31-installing-wsl-specific-guides)
  - [3.2. Installing Docker on Windows without Docker Desktop](#32-installing-docker-on-windows-without-docker-desktop)
  - [3.1. Docker for development](#31-docker-for-development)
  - [4. Copying data between Azure Cosmos Collections (MongoDB API)](#4-copying-data-between-azure-cosmos-collections-mongodb-api)
  - [4.1. Tooling for Copying data](#41-tooling-for-copying-data)

## 1.1. Introduction

Each section will denote a subject that I am trying to delve deeper into, covering topics required for work and for personal blogging. This document will adjust over time as I hit topics in as much detail as required (at the given time).

---

## 2. Utilities/Helpful Resources

## 2.1. The Book of Secret Knowledge

An interesting list of tools (systems, networks, devops, etc.):

- [The Book of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge).

## 2.2. Awesome .NET!

A collection of .NET tools, libraries, etc. (with a fair few contributors) to investigate:

- [Awesome .NET](https://github.com/quozd/awesome-dotnet).

## 2.3. Awesome .NET Core

.NET Core focused variant:

- [Awesome .NET Core](https://github.com/thangchung/awesome-dotnet-core).

***Consider contributing to this (caching?)***

## 2.4. Throw library

- [Throw](https://github.com/mantinband/throw).

---

## 3. Running Docker on Windows without Docker Desktop

Something I would like to look into (using just the Docker engine and WSL2). The following are interesting resources that indicate how to achieve this (note, only concerned with Linux containers for the moment).
  
## 3.1 Installing WSL (specific guides)

- [Install WSL](https://docs.microsoft.com/en-us/windows/wsl/install).

## 3.2. Installing Docker on Windows without Docker Desktop

- [Install Docker on Windows (WSL) without Docker Desktop](https://dev.to/bowmanjd/install-docker-on-windows-wsl-without-docker-desktop-34m9).
- [Install Docker Engine without Docker Desktop on Windows](https://jflower.co.uk/install-docker-engine-without-docker-desktop-on-windows/).
- [Docker on WSL2 without Docker Desktop](https://dev.solita.fi/2021/12/21/docker-on-wsl2-without-docker-desktop.html).
- [How To Live Without Docker Desktop — A Developer’s Perspective](https://www.objectivity.co.uk/blog/how-to-live-without-docker-desktop-developers-perspective/).
- [Run Docker in WSL (Windows 10/11) without Docker Desktop](https://medium.com/geekculture/run-docker-in-windows-10-11-wsl-without-docker-desktop-a2a7eb90556d).

## 3.1. Docker for development

- [.NET Development in Docker with Dev Containers](https://itnext.io/net-development-in-docker-6509d8a5077b).

---

## 4. Copying data between Azure Cosmos Collections (MongoDB API)

We have a requirement to fully port environments (e.g. a live to test restore, of sorts). The following documentation discusses facilitating this (using tools such as Azure Data Factory).

## 4.1. Tooling for Copying data

- [Copy data to or from Azure Cosmos DB's API for MongoDB using Azure Data Factory or Synapse Analytics](https://docs.microsoft.com/en-us/azure/data-factory/connector-azure-cosmos-db-mongodb-api?tabs=data-factory).
- [Azure Cosmos DB Data Migration tool](https://microsoft.github.io/AzureTipsAndTricks/blog/tip334.html).
