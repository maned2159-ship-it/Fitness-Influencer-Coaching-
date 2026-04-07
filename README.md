ER Diagram

You have:

Trainers (influencers) offering services
Clients (users) consuming different types of services
Multiple service models:
One-time consultation
Subscription-based coaching
Predefined fitness plans
Live sessions
Continuous progress tracking + interaction
User (Super Entity)

user_id (PK)
name
email
phone
role (client / trainer)

👉 This allows scaling (trainer = also a user)
<img width="5019" height="4425" alt="diagram-export-07-04-2026-20_57_13" src="https://github.com/user-attachments/assets/49c5bd12-de2a-481e-9b86-38d9ba80affd" />

2. Trainer
trainer_id (PK, FK → User)
bio
specialization
experience_years
3. Client
client_id (PK, FK → User)
age
gender
fitness_goal
