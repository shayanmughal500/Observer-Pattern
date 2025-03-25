# Observer-Pattern

# Overview

This repository contains two simple examples of the Observer Design Pattern implemented in Java. The Observer Pattern is a behavioral design pattern where an object (known as Subject) maintains a list of dependents (Observers) and notifies them automatically of any state changes.

# Examples Included

## 1. Simple Observer Pattern

Converts a number into Binary, Octal, and Hexadecimal formats.

Whenever the subject’s state changes, all attached observers update automatically.

Demonstrates how observers can be attached and detached dynamically.


## 2. Event Management System

Simulates a file editor where opening or saving a file triggers notifications.

Listeners like EmailNotificationListener, LogOpenListener, and SMSSupportListener react to events.

Shows real-world use cases such as logging, email alerts, and SMS notifications.
