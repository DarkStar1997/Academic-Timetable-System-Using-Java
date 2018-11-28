# Academic Timetable using Java

An algorithm to create an academic time-table for the classes in 4th and 6th semester has been implemented in the project.

## Databases used

### 1. *timeslots.csv
> Contains the timeslots per day of the week

*Sample table*

| Day of Week | Slot | Start Time | End Time |
|-------------|------|------------|----------|
| Tue         | 1    | 920        | 1010     |

### 2. *courses.csv
> Contains the courses with their respective slots and resource type

*Sample table*

| Code | Name          | Contact Slot | Course Type | Resource Type | Association |
|------|---------------|--------------|-------------|---------------|-------------|
| M401 | Mathematics-1 | 4            | Lecture     | Lecture Room  |             |

### 3. *instructors.csv
> Contains the data of all the instructors with their respective expertise

*Sample table*

| Name | Expertise1 | Expertise2 | Expertise3 | Expertise4 |
|------|------------|------------|------------|------------|
| AKDS | M401       | CS691      | CS604B     |            |

### 4. *sections.csv
> Contains the data of all concerned sections which are to be considered in the allocation

*Sample table*

| Year | Section | Lab Section | Enrollment |
|------|---------|-------------|------------|
| 2    | A       | A1          | 40         |

### 5. *rooms.csv
> Contains the data of all available rooms

*Sample table*

| Resource | Type         | Capacity |
|----------|--------------|----------|
| LG3.1    | Lecture Room | 100      |




