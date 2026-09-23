# EduPro-Online-Platform

Project Title / Headline

     Instructor Performance & Course Quality Evaluation — EduPro Online Platform

 Short Description / Purpose

       An interactive analytics dashboard that evaluates instructor effectiveness and course quality across the EduPro online learning platform. It joins instructor profiles, course records, and enrollment transactions to answer questions government/platform stakeholders actually care about: which instructors consistently deliver high-quality courses, whether experience translates into better ratings, which course categories depend most on instructor quality, and how evenly teaching performance is distributed — replacing subjective, fragmented instructor evaluation with a data-driven, filterable framework.
       
Tech Stack
python -pandas,Matplotlib,  Mysql
Power BI Desktop – Dashboard Development Power Query Editor – Data Cleaning & Transformation (ETL) DAX (Data Analysis Expressions) – Measures and Calculated Columns Data Modeling – Relationships & Star Schema Microsoft Excel / CSV – Source Dataset Interactive Visualizations KPI Cards Bar Charts Column Charts Pie/Donut Charts Line Charts Tables & Matrix Slicers Filters



     Data Source
EduPro Online Platform export, 4 linked CSV files:

Users — learner records
Teachers — TeacherID, TeacherName, Age, Gender, Expertise, YearsOfExperience, TeacherRating (60 instructors)
Courses — CourseID, CourseName, CourseCategory, CourseLevel, CoursePrice, CourseDuration, CourseRating (60 courses)
Transactions — TransactionID, CourseID, TeacherID, TransactionDate, Amount, PaymentMethod (10,000 enrollment records linking instructors to courses)
