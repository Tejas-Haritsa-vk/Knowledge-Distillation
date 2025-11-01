🧠 MNIST Knowledge Distillation

This repository demonstrates Knowledge Distillation (KD) on the MNIST dataset — a technique where a smaller student model learns from a larger teacher model, transferring its “knowledge” to achieve high accuracy with fewer parameters.

📘 Overview

Knowledge Distillation allows a compact model to mimic the behavior of a larger, well-trained model.
In this project:

A Teacher model (large CNN) is first trained on MNIST.

A Student model (smaller CNN or MLP) is then trained using both:

The true labels

The soft targets (logits) from the teacher model
