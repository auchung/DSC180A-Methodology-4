# Methodology Assignment 4

**Audrey Chung**  
**Email:** auchung@ucsd.edu  
**Course:** DSC 180A – Data Science Capstone  
**Domain:** D08 – From First Search to Trust at Scale: Building Data-Driven Marketing Systems and AI Agents for the Fertility Patient Journey and Online Reputation Management  
**Mentor:** Tamar Schaap

### 1. What is the most interesting topic covered in your domain this quarter?

One of the most interesting topics we've explored this quarter is how AI platforms influence the visibility of fertility clinics and the information patients receive about different providers. Our track examines whether RPSD appears in AI-generated responses, how prominently it is mentioned, and which competing clinics appear alongside it. I find it interesting that AI platforms can produce different recommendations in response to similar questions, raising concerns about their consistency and reliability. Since patients may rely on these responses when researching fertility treatment, understanding how clinics are represented is especially important.

### 2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.

I would be interested in investigating how prompt engineering influences AI-generated recommendations for fertility clinics. Specifically, we could explore how negations, changes in wording, and different ways of framing patient questions affect which clinics are recommended and how prominently they appear. I would also like to examine whether RPSD and its competitors are consistently recommended across different prompt variations. This could help us better understand how sensitive AI-generated recommendations are to the way questions are phrased.

### 3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?

One change I would make is to improve how we distinguish between a clinic being mentioned and actually being recommended in AI-generated responses. Although our current approach tracks clinic mentions and their positions, appearing earlier in a response does not necessarily mean that a clinic is being recommended more strongly. By manually reviewing a sample of responses and comparing them with our automated labels, we could improve the accuracy and consistency of our evaluation process. This would help make our comparisons between RPSD and competing clinics more reliable.

### 4. What other techniques would you be interested in using in your project?

I would be interested in using more systematic prompt engineering and statistical analysis to better understand differences in AI-generated recommendations. For example, we could create variations of the same question by changing one element at a time, such as adding a negation or emphasizing a specific patient concern. We could then use statistical testing to examine whether these changes consistently affect clinic visibility and recommendation positions. I would also like to explore information extraction techniques to compare which services and characteristics AI platforms highlight for different clinics.
