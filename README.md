Task 04: Hand Gesture Recognition using MediaPipe
This project explores Human-Computer Interaction (HCI) by developing a real-time system that can detect hand landmarks and interpret their meaning.

Key Highlights:
Technology: Integrated the MediaPipe Tasks API to identify 21 distinct 3D coordinates (landmarks) on the human hand.

Feature Extraction: Developed a custom Python algorithm to analyze the spatial geometry of fingers, comparing fingertip positions to knuckles to determine if a finger is extended or folded.

Gesture Classification: Implemented rule-based logic to "read" gestures, allowing the AI to differentiate between an Open Palm, Victory Sign, Closed Fist, and Finger Counting.

Robustness: Optimized the model to handle multi-hand detection and maintain high accuracy even with complex background noise.

Goal: To build the foundational logic used in sign language translation and touchless device control.
