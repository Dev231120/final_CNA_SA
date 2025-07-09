Report Outline
1-Introduction

2-Problem statement and motivation for dynamic pricing

3Overview of the parking system and data

4-Methodology

Model 1: Baseline Linear Model

Simple occupancy-based pricing


Model 2: Demand-Based Pricing

Key features used (occupancy, queue, traffic, etc.)

Demand function formulation

Normalization and bounding

Model 3: Competitive Pricing

Geographic proximity calculation

Competitor price integration

Rerouting logic

Data preprocessing

Real-time pipeline with Pathway

Parameter tuning approach

Results and Analysis

Price behavior under different conditions

Comparison between models

Key findings

Potential improvements

Business implications

Key Features of the Implementation
Progressive Model Complexity:

Starts with simple linear model (Model 1)

Adds multiple demand factors (Model 2)

Incorporates competition (Model 3)

Real-Time Capabilities:

Uses Pathway for streaming data processing

Maintains state between time steps

Scales to handle continuous data streams

Practical Considerations:

Smooth transitions between prices

Explainable price changes based on clear factors

Visualization:

Interactive Bokeh plots showing price dynamics

Correlation with occupancy and queue length

Multiple parking lots comparison
