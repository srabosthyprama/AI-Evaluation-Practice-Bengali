# Data Quality Evaluation Samples

## Sample 1 - Duplicate and Invalid Data

| Name | Age | City |
|------|-----|------|
| Rahim | 25 | Dhaka |
| Karim | 31 | Chattogram |
| Rahim | 25 | Dhaka |
| Sumaiya | -5 | Sylhet |
| Tanvir | 28 | Dhaka |

### Identified Issues

1. The record for Rahim appears twice, indicating a possible duplicate record.
2. Sumaiya's age is -5, which is an invalid value.

### Feedback

There are two data-quality issues: a duplicate record for Rahim and an invalid negative age (-5) for Sumaiya.

---

## Sample 2 - Instruction-Based Counting

### Dataset

- Cars: 5
- Buses: 2
- Motorcycles: 3
- Bicycles: 2
- Pedestrians: 6
- Trucks: 1

### Instruction

Count only cars, buses, motorcycles, and trucks.

### Result

**Total vehicles = 11**

Calculation:

5 cars + 2 buses + 3 motorcycles + 1 truck = 11 vehicles

### Excluded

- Bicycles
- Pedestrians

### Evaluation Note

The result follows the specified counting rule and excludes object categories that were not requested.
