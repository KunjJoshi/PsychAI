# Psych.ai

## Overview

**Psych.ai** is an innovative chatting tool designed to address the stigma surrounding psychology and psychiatry in India. It aims to provide an anonymous platform for individuals dealing with complex issues, offering guidance and support without the need for direct doctor confrontation. Additionally, it serves as a pre-diagnosis tool for psychiatrists, facilitating a better understanding of patients' problems before a face-to-face consultation.

## Motivation

### Why?
Psychology and psychiatry remain taboo topics in India. Many people are hesitant to seek help from doctors for their daily issues due to the associated stigma. Psych.ai aims to bridge this gap by offering a confidential and anonymous platform for individuals seeking help. It also serves as a preliminary diagnostic tool for doctors, allowing them to understand patients' issues better before an in-person consultation.

## Features

### What?
- **Anonymous Support**: Psych.ai provides a safe and anonymous platform for users to discuss their problems and receive guidance.
- **Pre-Diagnosis Tool**: Psychiatrists can use Psych.ai to gain preliminary insights into patients' issues before a face-to-face consultation.
- **Expert Responses**: The tool is fine-tuned on psychiatric responses to real-life issues and solutions provided by leading doctors.

## Technology

### How?
Psych.ai is built using a Large Language Model (LLM) with adapters, specifically fine-tuned to respond to psychiatric issues. Given the impracticality of training a model from scratch on a limited dataset, we employed fine-tuning techniques to develop this tool.

- **Model**: The base model used is Mistral-7B v1.0.
- **Technique**: Fine-tuning is performed using Prompt Triggers and the Parameter-Efficient Fine-Tuning (PEFT) method.
