# Who Bears the Burden? Decoding Climate Equity with PCA

In this in-depth analysis, we utilize Principal Component Analysis (PCA) to unravel the complex narrative of climate equity. Through a meticulous examination of GDP, population metrics, historical emissions, and adaptation scores, this project distills nuanced insights into the roles and responsibilities of nations within the global climate crisis framework. 

## Project Overview

Climate equity is a multifaceted issue that defies simple categorization. Nations' contributions to climate change and their capacities to combat it vary widely, influenced by economic strength, historical actions, and inherent vulnerabilities. By synthesizing an extensive dataset from Climate Watch, this analysis ventures beyond surface-level statistics to explore the underlying dynamics of global climate equity.

### Key Insights

- **Economic Giants vs. Vulnerable Nations**: Our PCA-based exploration delineates a spectrum of national profiles, from affluent, high-emitting countries to economically modest nations disproportionately impacted by climate change.
- **Patterns of Responsibility and Capability**: We identify patterns linking historical emissions to current economic and environmental resilience, offering a basis for nuanced discussions on global climate policies.
- **Strategic Directions for Climate Action**: The analysis points towards differentiated responsibilities, suggesting targeted strategies for emissions reduction, adaptation, and international cooperation.

## Technologies and Techniques

This project employs a suite of data science tools and techniques, showcasing proficiency in:
- Data preprocessing and feature engineering with `pandas`.
- Advanced data visualization including PCA space mapping with `matplotlib` and `plotly`.
- Implementation of PCA using `scikit-learn` to analyze and interpret complex datasets.

## How to Navigate This Project

- **Data Preparation**: Dive into our dataset compilation process, featuring socio-economic indicators and emissions records crucial for understanding climate equity.
- **Feature Engineering**: Explore how we distilled key indicators to capture the essence of climate equity from multiple perspectives.
- **Correlation Analysis**:  Uncover the intricate relationships between economic strength, emissions, and climate vulnerability, setting the foundation for a deeper PCA-driven exploration.
- **PCA Analysis**: Understand our approach to simplifying dataset complexity, preserving variance, and unveiling dominant patterns in global climate dynamics.

## Enhanced Insights through Visualization

We present a range of visualizations to deepen understanding and exploration of our climate equity analysis:

- **Correlation Heatmap**: Illuminates the relationships between variables, emphasizing the interconnectedness of economic strength, emissions, and climate vulnerability.

<p align="center">
<img src="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/correlation_heatmap.png" alt="Correlation Heatmap" width="800">
</p>

- **Scree Plot & Cumulative Explained Variance Plot**: These plots help in determining the number of principal components to retain, illustrating the variance captured by each component.

<p align="center">
<a href="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/scree_plot.html">
  <img src="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/scree_plot.png" alt="Scree Plot" width="400">
</a>
<a href="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/cumulative_explained_variance_plot.html">
  <img src="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/cumulative_explained_variance_plot.png" alt="Cumulative Explained Variance Plot" width="400">
</a>
</p>

- **Feature Contributions**: Breaks down the contribution of each feature to the principal components, clarifying their impact on the analysis.

<p align="center">
<img src="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/feature_contributions.png" alt="Feature Contributions" width="1000">
</p>

- **PCA Scatter Plots (PC1 vs PC2, PC2 vs PC3)**: Map the strategic positioning of countries within the PCA space, highlighting their roles and responsibilities in climate equity.

<p align="center">
<a href="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/pc1_pc2.html">
  <img src="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/pc1_pc2.png" alt="PC1 vs PC2" width="400">
</a>
<a href="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/pc2_pc3.html">
  <img src="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/pc2_pc3.png" alt="PC2 vs PC3" width="400">
</a>
</p>

- **Interactive 3D Plot on Climate Equity**: Explore this interactive plot for a comprehensive view across principal components, enhancing the exploration of our findings. (Note: This plot is interactive and will open in a new tab)

<p align="center">
<a href="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis//Plots/pca_3d.html">
   <img src="https://jasminekuo.github.io/Climate-Equity-PCA-Analysis/Plots/pca_3d.png" alt="Interactive 3D Plot on Climate Equity" width="600">
 </a>
</p>

## Conclusion and Call to Action

Our journey through data with PCA paints a vivid picture of the world's climate equity challenge—a mosaic of shared burdens and diverse responsibilities. This project underscores the necessity of a united front, advocating for a global pact to navigate the intricate balance of environmental stewardship and economic development.

## License

This project is released under the [MIT License](LICENSE), promoting open access to data and encouraging innovative use of the findings.

## About the Author

This analysis was conducted by Jasmine Kuo, a data scientist with a passion for leveraging analytics to address global challenges. For inquiries or collaboration, reach out via [Email](mailto:ik2437@nyu.edu) or [LinkedIn](https://www.linkedin.com/in/jasmineejkuo/).
