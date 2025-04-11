
# **PUBLIC REPORT ON THE DEVELOPMENT OF THE NUTRITIONIST PLATFORM AND THE CALORIE ESTIMATION ALGORITHM**  

---

### 1. CONTEXT AND OBJECTIVES

This report presents the work carried out to create a platform for nutritionists, focusing on improving patient follow-up through artificial intelligence (AI) and computer vision resources. The main innovation is the development of a **proprietary algorithm to estimate calories** from images, designed for **low computational cost**, ensuring both scalability and accessibility in different contexts.

Since this is still a research and development solution, some detailed technical information remains confidential. However, this document highlights:

1. The market scenario and the motivation to build such a platform.  
2. The methodological foundations and main features of the algorithm.  
3. The initial practical results and lessons learned.  
4. The next steps for project evolution.

The purpose of this report is to inform and demonstrate to the responsible manager the status of the work performed, providing a clear view of the progress made, as well as the challenges and opportunities identified.

---

### 2. FUNDAMENTALS AND DOCUMENTARY BASIS

Various studies and internal analyses were considered to support the project, including:

- **Computer vision and AI methodologies applied to food**: a review of segmentation, classification, and regression techniques for calorie estimates.  
- **Best practices in data annotation**: defining procedures for collecting and labeling images, ensuring consistency and reliability of the model.  
- **Market and competitive analyses**: assessing the potential of digital nutrition solutions, including existing platforms and unmet gaps.  
- **Positioning strategies**: using frameworks such as SWOT and Porter to map risks, opportunities, and guide project development.

These pillars helped to establish the scope of features and the relevance of our algorithm in a rapidly expanding market.

---

### 3. OVERVIEW OF THE SOLUTION AND DIFFERENTIATORS

The platform targets two main audiences:

1. **Nutritionists and Clinics**  
   - **Automated calorie calculation**: the algorithm estimates the energy value of each meal directly from photos, reducing manual entry time.  
   - **Monitoring dashboard**: provides reports and indicators of patient adherence to the meal plan.  
   - **Integration with the workflow**: professionals have access to consolidated data without needing to switch systems or perform multiple manual steps.

2. **Patients**  
   - **Quick registration via photo or text**: just take a picture of the plate, and the system returns an approximate calorie estimate.  
   - **Immediate feedback**: view consumption history, daily goals, and alerts to maintain or adjust the diet.  
   - **Streamlined experience**: avoids lengthy form-filling and encourages greater adherence to the meal plan.

#### Calorie Estimation Algorithm: Main Characteristics

- **Low Computational Cost**  
  Developed to use minimal hardware resources, allowing operation on modest devices or in a lean cloud infrastructure.  
- **Focus on Brazilian Dishes**  
  Unlike many solutions that do not include our local cuisine, the model is trained with images of typical Brazilian foods, improving estimation accuracy.  
- **Integration with the Nutritionist’s Workflow**  
  The goal is for the professional to receive ready and reliable data, speeding up decision-making and nutritional counseling.

---

### 4. MARKET AND COMPETITION ANALYSIS

The digital nutrition sector is experiencing significant growth, driven by the adoption of apps and platforms that simplify the routine of those seeking to improve their eating habits. In this context:

- **Demand for Automation**: there is a great deal of interest among users and professionals in reducing the manual workload of meal logging, creating opportunities for AI and computer vision solutions.  
- **Existing Solutions**: many international platforms have certain limitations in recognizing regional dishes, which negatively impacts the experience of Brazilian users.  
- **Opportunity for Differentiation**: combining artificial intelligence adapted to local cuisine with a user-friendly design creates a strong competitive advantage.

Moreover, strategic analyses indicate that even with the possibility of new solutions entering the market, there is a good chance of consolidating this platform as a reference, especially by combining accuracy, low computational cost, and support for Brazilian users’ preferences.

---

### 5. METHODOLOGY AND INITIAL RESULTS

#### 5.1 Development and Initial Testing

1. **Image Collection**  
   An initial set of photos of typical dishes was built, covering variations in angles, lighting, and contexts (deep or shallow plates, different dishware, etc.).

2. **Data Preparation**  
   The images were annotated and organized so that the model could learn to recognize different foods and estimate calorie content effectively.

#### 5.2 Observed Results

- **Measurement Accuracy**  
  In practical tests, there was good consistency between the overall evaluation of the dish’s dimensions and the final calorie estimation, although perspective and lighting can cause slight variations.

- **Computational Efficiency**  
  Even on lower-capacity servers, processing time was satisfactory, indicating feasibility on a large scale or in resource-limited environments.

- **Use in Real Environments**  
  Although still in laboratory tests, there was already noticeable potential for easy adoption by nutritionists, given the convenience of having patients log their meals.

---

### 6. CONCLUSION AND NEXT STEPS

**Main Conclusions**  
- There is a favorable scenario for platforms that automate the meal registration process, especially if adapted to local cuisines.  
- The developed calorie estimation algorithm shows good potential for scalability and accuracy, serving as a central solution in our system.  
- Initial results reinforce the viability of this approach, yet further refinements are needed to handle a wider range of dishes, angles, and lighting conditions.

**Next Steps**  
- **Expand the Data Set**: collect new images from different regions and contexts to increase the model’s robustness.  
- **Refine the Algorithm**: add adjustments to improve segmentation for mixed foods and correct possible inaccuracies in estimation.  
- **Pilots in Professional Settings**: partner with clinics and practices to test the platform’s daily use, gathering feedback from nutritionists and patients.  
- **MVP Evolution**: implement improvements to the interface, develop more detailed dashboards for professionals, and include teleconsultation resources and additional integrations.

---

**In summary**, the work carried out so far demonstrates a promising solution to optimize nutritional monitoring, benefiting both patients and nutritionists. The low computational cost and focus on local foods stand out, paving the way for positioning this product competitively in the digital nutrition market. Our commitment is to continue improving the algorithm and platform to deliver a simple, reliable experience aligned with real user needs.
