# Bootstrap Grid System Homework

### 1. Basic Grid Layouts

**Task 1: Equal Width Columns**

Layout 1: Two Columns
+----------+----------+
|  Col-6   |  Col-6   |
+----------+----------+

Layout 2: Three Columns
+------+------+------+
| Col-4| Col-4| Col-4|
+------+------+------+

Layout 3: Four Columns
+----+----+----+----+
|Col3|Col3|Col3|Col3|
+----+----+----+----+


**Task 2: Unequal Columns**

Layout 1:
+---------+---+
|  Col-9  | 3 |
+---------+---+

Layout 2:
+----+--------+
| C4 | Col-8  |
+----+--------+

Layout 3:
+--+--------+--+
|2 | Col-8  |2 |
+--+--------+--+


### 2. Content Section Layouts

**Task 1: News Website Layout**

+------------------+
|     Header       |
|     Col-12       |
+--------+---------+
| Main   | Sidebar |
| Col-8  | Col-4   |
|        |         |
+--------+---------+
|     Footer       |
|     Col-12       |
+------------------+


**Task 2: E-commerce Product Layout**

+----+----+----+----+
| Product Cards 4x   |
| Each Col-3        |
+----+----+----+----+


### 3. Complex Grid Patterns

**Task 1: Dashboard Layout**

+-----+-----+-----+
| C4  | C4  | C4  | Stats Cards
+-----+-----+-----+
+--------+--------+ 
| Col-6  | Col-6  | Charts
+--------+--------+
+--+--+--+--+--+--+ 
|C2|C2|C2|C2|C2|C2| Info Cards
+--+--+--+--+--+--+


**Task 2: Image Gallery**

+----+----+----+----+
| C3 | C3 | C3 | C3 |
+----+----+----+----+
+------+------+------+
| Col4 | Col4 | Col4 |
+------+------+------+


### 4. Practical Layout Tasks

**Task 1: Student Portal Layout**

+-----------------+
|     Header      |
+-----------------+
| Notice Board    |
| Col-12          |
+--------+--------+
| Marks  | Events |
| Col-6  | Col-6  |
+--------+--------+
| Timetable       |
| Col-12          |
+-----------------+


**Task 2: Food Delivery Menu**

+------------------+
| Category Header  |
+-----+-----+-----+
| C4  | C4  | C4  | Food Items
+-----+-----+-----+
+--------+--------+
| Col-6  | Col-6  | Special Offers
+--------+--------+


### 5. Implementation Instructions

**Basic Template:**
html
<!DOCTYPE html>
<html>
<head>
    <title>Grid Practice</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    
</head>
<body>
    <div class="container">
        <!-- Add your grid here -->
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


### 6. Practice Projects

**Project 1: College Department Website**
Create these sections:

1. Header (Full Width)
+------------------+
|     Col-12       |
+------------------+

2. Department Info
+--------+---------+
| About  | Notice  |
| Col-8  | Col-4   |
+--------+---------+

3. Faculty Profiles
+----+----+----+
| C4 | C4 | C4 |
+----+----+----+

4. Course Information
+-----+-----+-----+
| C6  | C6  | Full Row Courses
+-----+-----+
| Col-12    | Course Details
+-----------+


**Project 2: Restaurant Menu**
Create this layout:

1. Top Section
+------------------+
| Restaurant Name  |
+------------------+

2. Menu Categories
+----+----+----+----+
| C3 | C3 | C3 | C3 |
+----+----+----+----+

3. Special Items
+--------+--------+
| Col-6  | Col-6  |
+--------+--------+

4. Contact Section
+-----+-----+-----+
| C4  | C4  | C4  |
+-----+-----+-----+


### 7. Submission Requirements

For each layout submit:
1. HTML file with grid implementation
2. Screenshots of the layout
3. Brief explanation of column choices

### 8. Success Checklist

Verify each layout has:
- Proper container
- Row structure
- Correct column classes
- Content in each column
- Clean formatting

### 9. Additional Tips

1. Column Rules:
   - Always equals 12 per row
   - Nest within parent columns
   - Keep content inside columns

2. Layout Tips:
   - Plan layout on paper first
   - Start with main sections
   - Add nested grids last
   - Keep HTML indented properly

Remember:
- Practice each layout multiple times
- Try different column combinations
- Keep code clean and organized
- Add content to test real usage