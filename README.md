# Commit Message Standards

This document briefly explains and exemplifies commit message standard for izerozlu github repositories.

Includes
* Commit message types
* Commit message summary and descriptions
* Emoji and label usages for commit message types

> PS: Commit types and emoji usages are heavily inspired by [Carlos Cuesta](https://carloscuesta.me/)'s work [gitmoji](https://github.com/carloscuesta/gitmoji).

## Commit Types

Commits must include type. These types are:
* Start **[START]**
* Bug Fix **[BUG-FIX]**
* Work in Progress **[WIP]**
* Refactor **[RFAC]**
* Feature addition **[FEAT]**
* Version **[VER]**

### 1. Start

Used when starting a project.

#### 1.1 Summary (Required)

```
🎉 [START] | "Learning Ember.js" initialized.
```
#### 1.2 Description (Optional)

```
This project includes a simple TODO list created with Ember.js.
```

### 2. Bug Fix

Indicates a known bug is resolved with this commit.

#### 2.1 Summary (Required)

```
🐛 [BUG-FIX] | Calculation which breaks virtual repeater's first page fixed.
```
#### 2.2 Description (Optional)

```
io-virtual-repeater#setupFirstPoint method's faulty placement calculation fixed.

Bug was created with misunderstanding of placement requirements.
```

### 3. Work In Progress

Acts like a checkpoint in a video game. 

Tries to explain that the work being done is not finished yet but this commit was required to be made.

#### 3.1 Summary (Required)

```
🔖 [WIP] | WeatherHttpRequestService's API integration with back-end.
```
#### 3.2 Description (Required)

```
Methods for the following endpoints are implemented.

# GET /api/daily-forecast
# GET /api/weekly-forecast

Endpoints left out:

# POST /api/city-selection
# PUT /api/city-selection
```

### 4. Refactor

Explicitly describes refactorings made in code.

#### 4.1 Summary*

```
✨ [RFAC] | Duplicate methods extracted to a service in NewsShowcaseComponent.
```
#### 4.2 Description*

```
Code block at NewsShowcaseComponent:429 -> 457 extracted into a method named "clearNewsEntity" in NewsUtilityService.
```

### 5. Feature Addition

A new feature is added to application.

Work in Progress [WIP] commits are mostly used to reach this commit type in the end.

#### 5.1 Summary*

```
✅ [FEAT] | "Trending Topics" report has been added.
```
#### 5.2 Description*

```
Latest trend analysis and visualization report's implementation is complete.
```

### 6. Version

Version of the project -a set of improvement and feature inclusions- increased. 

#### 6.1 Summary*

```
🍻 [VER] | 1.0.1 -> 1.0.2
```
#### 5.2 Description*

```
Issues #32, #12, #9, #22 resolved.
```
