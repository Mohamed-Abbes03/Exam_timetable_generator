Exam Timetable Generator - Genetic Algorithm Solution
📝 Project Overview

This project implements a Genetic Algorithm (GA) solution for generating optimal exam timetables, addressing the complex constraints of:

    Room capacities

    Lecturer availability

    Student course enrollments

    Timeslot management

The system features both traditional evolutionary approaches and an advanced co-evolution strategy.
🖼️ Screenshots
Course Selection Interface

Course Selection
Traditional Evolution Timetable

Traditional Evolution
Co-Evolution Timetable

Co-Evolution
Fitness Comparison

Fitness Comparison
Fitness Progress

Fitness Progress
Fitness Over Generations

Fitness Over Generations
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

🛠️ Technical Implementation
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

    Install required dependencies:
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

Run the application:
bash

    python timetable_generator.py

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
