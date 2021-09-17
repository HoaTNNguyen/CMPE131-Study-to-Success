# Product Specifications

- [Product Specifications](#product-specifications)
  - [Description:](#description)
  - [Contributors:](#contributors)
  - [Functional Requirements](#functional-requirements)
    - [General Feature](#general-feature)
    - [Memorizing](#memorizing)
      - [1. Input a markdown file and ouput flash cards](#1-input-a-markdown-file-and-ouput-flash-cards)
      - [2. Share flash cards (add to their account)](#2-share-flash-cards-add-to-their-account)
      - [3. Mind map of flash cards](#3-mind-map-of-flash-cards)
      - [4. Change order of flash cards based on how often user got answer correct](#4-change-order-of-flash-cards-based-on-how-often-user-got-answer-correct)
      - [5. Create pdf of flash cards to print](#5-create-pdf-of-flash-cards-to-print)
    - [Notes](#notes)
      - [1. Render markdown notes](#1-render-markdown-notes)
      - [2. Convert markdown notes to pdf](#2-convert-markdown-notes-to-pdf)
      - [3. Share notes with other people (add to their account)](#3-share-notes-with-other-people-add-to-their-account)
      - [4. Find text in files](#4-find-text-in-files)
      - [5. Quickly rename files using regular expression](#5-quickly-rename-files-using-regular-expression)
      - [6. Add ability to navigate between notes using this syntax [[this other note]]](#6-add-ability-to-navigate-between-notes-using-this-syntax-this-other-note)
    - [Time Management](#time-management)
      - [Use Cases:](#use-cases)
    - [USE CASE #2](#use-case-2)
    - [USE CASE #3](#use-case-3)

## Description:
- Date: TBD
- Product Name: [Study2Success](https://github.com/HoaTNNguyen/Study2Success)
- Problem Statement: TBD

## Contributors:
1. Hoa Nguyen: https://github.com/HoaTNNguyen
2. Ngan Ngo: https://github.com/RachelNgo
3. Jerusalem Ilag: https://github.com/jeruilag
4. [Abdullah Waheed](https://github.com/abdullahw1): https://github.com/abdullahw1

## Functional Requirements

### General Feature
1. Ability for users to sign-up, login/logout. 
2. Be able to delete account

### Memorizing
#### 1. Input a markdown file and ouput flash cards
- DRI: [Hoa Nguyen](https://github.com/HoaTNNguyen)

#### 2. Share flash cards (add to their account)
- DRI: [Hoa Nguyen](https://github.com/HoaTNNguyen)

#### 3. Mind map of flash cards
- DRI: [Hoa Nguyen](https://github.com/HoaTNNguyen)

#### 4. Change order of flash cards based on how often user got answer correct
- DRI: [Hoa Nguyen](https://github.com/HoaTNNguyen)

#### 5. Create pdf of flash cards to print
- DRI: [Jerusalem Ilag](https://github.com/jeruilag)


### Notes
#### 1. Render markdown notes
- DRI: [Abdullah Waheed](https://github.com/abdullahw1)

#### 2. Convert markdown notes to pdf
- DRI: [Abdullah Waheed](https://github.com/abdullahw1)

#### 3. Share notes with other people (add to their account)
- DRI: [Abdullah Waheed](https://github.com/abdullahw1)

#### 4. Find text in files
- DRI: [Abdullah Waheed](https://github.com/abdullahw1)

#### 5. Quickly rename files using regular expression
- DRI: Jerusalem Ilag

#### 6. Add ability to navigate between notes using this syntax [[this other note]]
- DRI: Jerusalem Ilag


### Time Management


#### Use Cases:
1.  Create time blocks
- Summary: Feature which users could make blocks of time.
- Actors: The Users

Preconditions: The users has logged in

Trigger: Open the "time blocks"

Primary Sequence: 

  1. System show users a calendar with dates.

  2. Users select a date from a calendar

  3. Users create their event title and tasks with a due time.

  4. System automatically show up the event in the users's calendar with a block of time.

  5. Users log out

Post conditions:

Users had an event in their calendar

Alternate sequence:


### USE CASE #2 

Product name: Study to Success

Problem Statement: feature which users could estimate how many pomodoros each task will take

Non-functional Requirements:

Use case name: Use pomodoro timer

Actors: The Users

Preconditions: The Users has logged in. 

Trigger: the users open the "Pomodoro timer"

Primary Sequence:
  
  1. Decide task to be done
  
  2. Set timer to 25 min 
  
  3. Work until timer run out

Post conditions:

The Users would focus on a single task at a time.

Alternate sequence:

### USE CASE #3

Product name: Study to Success

Problem Statement: feature which users could organize and manage their to-do items 

Non-functional Requirements:

Use case name: Add todo tracker

Actors: The Users

Preconditions: The Users has logged in.

Triggers: The Users select "ToDo Tracker " option

Primary sequence:

 1. System prompt the users to do a list.

 2. The users make a list, sort them according to their priority.

 3. System show the list with the checklist.

 4. The Users log out.

Postconditions:

The Users can add, delete and mark the todo list.
