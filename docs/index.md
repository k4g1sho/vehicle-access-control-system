## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

#  Vehicle Access Control System

## Description
This is a project that will teach and demonstrate the use of cloud technologies. But first we must first create them locally securely before exploring the cloud. Trial by fire.

## This repository will only contain documentation.

## Plan
The plan is to make a vehicle access control system. It will track cars coming in and out with their respective driver names.

## Code and Database
Python using fastAPI REST API for backend, posgresql.

## Infrastructure 
1. Code and database on the same machine(desktop)
2. Code and database on same machine(desktop) on different virtual machines,manual install
3. Code and database on the same machine(desktop) different virtual devices,manual install
4. Code and database on the same machine(desktop) different virtual machines,docker
5. Code on the Desktop and database on laptop - local connection via lan cable, manual
6. Code on thee Desktop and database on laptop - local connection via wifi, manual
7. Code on the Desktop and database on laptop- over the internet - Desktop connected to wifi laptop connected to mobile network
8. Code on the Desktop database on aws
9. Code on aws database on the desktop
10. Code and database on aws, manual
11. Code and database on aws, setup automated


car-tracking-system/          <-- The "Parent" Repo (Documentation & Infra)

* .git/                         <-- Git tracking for the Parent

* .gitmodules                   <-- The "Map" that links the submodule

* docs/                         <-- Your GitHub Pages (MkDocs) files
    * index.md                  <-- Home: Project Overview
    * steps.md                  <-- Steps
    * tech stack.md

* infrastructure/               <-- Networking notes, Firewall rules, Docker (later)
    * steps.md                  <-- Follow through on how the work is done
    * configurations.md         <-- Configuration files
    * logs.md                   <-- Errors encountered

* back-end-code/                <-- SUBMODULE (A "window" to Repo #2)
    * .git/                     
    * main.py                   
    * requirements.txt          e