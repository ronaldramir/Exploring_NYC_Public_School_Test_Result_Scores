# NYC Public School SAT Performance Analysis

This project analyzes SAT performance data for New York City public schools. The dataset includes scores in reading, math, and writing for various schools. The analysis answers key questions regarding school performance in math, top-performing schools based on combined SAT scores, and the borough with the largest standard deviation in SAT scores.

## Dataset

The dataset `schools.csv` contains the following columns:
- `school_name`: The name of the school
- `borough`: The borough where the school is located
- `average_math`: The average math score for the school
- `average_reading`: The average reading score for the school
- `average_writing`: The average writing score for the school

## Analysis

The analysis involves:

1. **Identifying Schools with the Best Math Results**
   - Schools with an average math score of at least 80% of the maximum possible score (800) are considered.
   
2. **Finding Top 10 Performing Schools Based on Combined SAT Scores**
   - The combined SAT score is the sum of average math, reading, and writing scores.

3. **Determining the Borough with the Largest Standard Deviation in Combined SAT Scores**
   - The borough with the greatest variability in combined SAT scores is identified.

## How to Use

### Prerequisites

Ensure you have Python and the necessary libraries installed:

```bash
pip install pandas
