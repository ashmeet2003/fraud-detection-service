# fraud-detection-service
This is an asynchronous, backend processing service that analyzes financial transactions for potential fraud in real-time. It has no direct API endpoints and operates by consuming events from Kafka, applying a set of rules, and publishing its findings back to the event bus.
