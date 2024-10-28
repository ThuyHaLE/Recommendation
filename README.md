# Plastic Injection Molding Optimization

## Overview

This project focuses on optimizing the plastic injection molding process for manufacturing parts by utilizing a structured database. The objective is to generate an efficient production plan based on production orders (POs) while considering machine capabilities, mold specifications, and plastic material requirements.

## Manufacturing Process

Plastic injection molding is a manufacturing process that produces parts by injecting molten plastic material into molds. This process is efficient for producing high volumes of plastic parts, making it widely used in various industries.

## Project Components

### Database

The database contains essential information categorized as follows:

1. **Plastic Information**
   - **Mold Specification**: Name and code of the mold.
   - **Capacity**: Number of parts produced per mold (psc/mold).
   - **Optimized Cycle Time**: Time per shot in seconds.
   - **Suitable Machine Tonnage List**: List of machine tonnage with priority given to the lowest tonnage.

2. **Mold Information**
   - **Plastic Types**: Types of plastics used for production.
   - **Required Quantity**: Quantity of plastic (in kg) needed for producing each 10,000 pcs.

3. **Production Report**
   - **Total Order List**: A list of all production orders received.
   - **Order Status**: Status of each order in the production process.

### Input and Output

#### Input

- Production Orders (POs) with desired delivery dates.

#### Output

1. **Production Plan**: 
   - A list detailing which items will be produced on each machine with an estimated lead time.

2. **Mold Plan**: 
   - A list specifying which molds will be used on each machine with an estimated lead time.

3. **Plastic Plan**: 
   - A breakdown of plastic types and quantities required for each machine per day.

## Usage

1. **Setup**: Initialize the database with machine and mold specifications, plastic information, and production orders.
2. **Run Optimization**: Execute the optimization algorithm to generate the production, mold, and plastic plans.
3. **Review Output**: Check the output plans for efficiency and feasibility based on the production orders.

## Conclusion

This project aims to enhance the efficiency of the plastic injection molding process by recommending optimal production plans that align with customer demands and machine capabilities. It streamlines the manufacturing workflow, ensuring timely delivery of high-quality plastic parts.

---

Feel free to modify any sections to better fit your project's specific requirements or to add additional details as needed!
