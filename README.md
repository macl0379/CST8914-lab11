# CST8914 Lab 11

**Student Name**: Collin MacLeod
**Student ID**: macl0379
**Course**: CST8914 - Accessible by Design
**Semester**: Fall 2026

---

## Introduction

In modern web development, custom UI components are widely used, offering unique interactions and features. However, accessibility is often overlooked during their creation. Your objective is to develop accessible UI components to ensure inclusivity and usability for all users.

### Objectives

- Employ accessible patterns to identify accessibility requirements for a custom component 
- Integrate ARIA and keyboard operability to make custom UI component accessibility

## Questions

### What keyboard interaction is missing?

The keyboard is unable to open and close the accordion.

### What ARIA is missing

The button to open the accordion is miossing aria-controls and aria-expanded. The accordion section is missing the aria-labelledby and while it is not ARIA the accordion section is also missing role="region". Both sections are also missing id tags which will allow aria-labelledby and aria-controls to function as intended. As per WAI ARIA patterns, the button was also wrapped in an h2 tag.