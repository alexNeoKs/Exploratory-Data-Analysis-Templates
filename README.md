# Exploratory-Data-Analysis-Templates
A data scientist must master a variety of plots to explore, analyze, and communicate data effectively. Since most plots or techniques are almost always reusable, this repo serves as a template for anyone to pull or copy off for their uses. If you want to contribute to this repo , feel free to reach out ! 

EDA to me is just a matter of telling a story with the data you are given. Different charts or techniques are basically just different narrative devices to help communicate info to your readers or yourself! 

I am going to organise this repo into different levels for understanding sake and each different level will have its own folder containing examples.

### Foundational Data Understanding
This is literally your “What is in my dataset, and can I trust it?”.
It should always be your first steps you do when you inspect data. NEVER ASSUME, you know said data cus it never hurts to be extra extra careful. 

#### There are 4 Key Stages to data understanding:
1. Dataset Structure Inspection
2. Summary Statistics
3. Missing Data Analysis
4. Duplicate & Consistency Checks
5. Basic Visualization

#### 1. Data Structure Inspection
Purpose:<br>
Before modeling or even plotting, you want to quickly understand the dataset’s “shape” and layout so you don’t make bad assumptions.

Rows vs columns (the “shape”)
- Rows ≈ samples/observations (e.g., customers, transactions)
- Columns ≈ features/variables (e.g., age, price, timestamp)

Column names and meanings
- Names tell you what fields exist.
- You often pair this with a quick look at a few rows to understand semantics.

Memory usage
- Large datasets can be slow or crash notebooks

#### 1. Data Structure Inspection