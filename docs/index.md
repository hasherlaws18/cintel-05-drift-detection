# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Custom Project

### Dataset
added to the data set with my own numbers.

### Signals
Used signals: requests, errors, latency.
Created signals: averages, mean differences, and drift flags to detect changes.

### Experiments
Adjusted threshold values (increased them) to test how sensitivity to drift changes.

### Results
Requests and errors were flagged as drifting, but latency was not, even though it increased significantly.

### Interpretation
The system is less sensitive after increasing thresholds. It still detects obvious changes (requests, errors) but can miss important shifts (latency), meaning thresholds may need tuning.

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)
