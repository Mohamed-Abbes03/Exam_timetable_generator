# Exam-Timetabling-Optimization - Genetic Algorithm Solution
📝 Project Overview

This project implements a Genetic Algorithm (GA) solution for generating optimal exam timetables, addressing the complex constraints of:

    Room capacities

    Lecturer availability

    Student course enrollments

    Timeslot management

The system features both traditional evolutionary approaches and an advanced co-evolution strategy.<br>
    
🖼 Screenshots<br>

![Screenshot 2025-05-16 221347](https://github.com/user-attachments/assets/d900cb29-d5c1-4dd4-8335-f083537fb36c)

![Screenshot 2025-05-16 221403](https://github.com/user-attachments/assets/d8e11656-f93c-4265-b9d6-a50ea816ad12)

![Screenshot 2025-05-16 221458](https://github.com/user-attachments/assets/3efd4eda-5e9a-49d9-9965-b721b85bd7c9)

![Screenshot 2025-05-16 221509](https://github.com/user-attachments/assets/93418792-0d09-430f-aba0-13a0a0eb59d4)

![Screenshot 2025-05-16 221419](https://github.com/user-attachments/assets/370177cd-19af-4ba1-b775-f898afe5b072)

![Screenshot 2025-05-16 221447](https://github.com/user-attachments/assets/ebd15f59-de84-47d9-9c8c-a7b8f2ea9718)





🧠 Key Features

    Advanced Genetic Algorithm Implementation

        Multiple crossover methods (One-point, Uniform)

        Specialized mutation operators (Room, Timeslot)

        Diverse selection strategies (Generational, Elitism, Crowding)

    Co-Evolution Strategy

        Parallel evolution of complementary solutions

        Enhanced exploration of solution space

        Better handling of complex constraints

    Comprehensive Visualization

        Interactive GUI with Tkinter

        Comparative fitness plots

        Generation-by-generation progress tracking

    Practical Constraints Handling

        Room capacity enforcement

        Student schedule conflict prevention

        Lecturer availability management

🛠 Technical Implementation
Core Algorithm Components

    Chromosome Representation: Encodes course-room-timeslot assignments

    Fitness Function: Evaluates solutions based on constraint violations

    Genetic Operators: Specialized for timetable optimization

Advanced Techniques

    Shared Fitness: Maintains population diversity

    Crowding Replacement: Preserves solution variety

    Genetic Distance: Measures solution similarity

📊 Performance Metrics

The system tracks and visualizes:

    Configuration-wise fitness comparisons

    Generational fitness progress

    Top performing configurations

💾 Data Management

    CSV-based data input for all entities

    Automatic saving/loading of results

    Persistent storage of best solutions

🚀 Getting Started

Install required dependencies:<br>
bash

    pip install pandas matplotlib tkinter tqdm tabulate

Prepare input CSV files:

    courses.csv

    lecturers.csv

    rooms.csv

    students.csv

    timeslots.csv

    students_courses.csv

    lecturers_courses.csv

Run the application:<br>
bash

    python main.py

📚 Documentation

The code includes comprehensive docstrings and comments explaining:

    Genetic algorithm parameters

    Fitness calculation details

    Constraint handling mechanisms

    Visualization methods

📈 Results Interpretation

The system provides multiple views for analyzing results:

    Best Timetables: Detailed exam schedules

    Fitness Comparisons: Bar charts of configuration performance

    Progress Tracking: Line graphs of generational improvement

    Summary Statistics: Top fitness values per configuration
