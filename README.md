# XAI in Large Language Models - Token Saliency Analysis in Food Descriptions

## 🚀 Overview
This project explores how the GPT-2 model processes and evaluates different words (or tokens) in food descriptions. I used saliency analysis to see which words are most important when the model generates text based on a given prompt. 

## 📝 Steps
1. **Set Up:**
   - First, you’ll need to import the necessary libraries and load the GPT-2 model and tokenizer.

2. **Input Your Prompt:**
   - Choose a food description that you want to analyze. This can be anything from "A delicious bowl of spaghetti with fresh basil" to "A crispy apple pie with a golden crust."

3. **Run the Analysis:**
   - Call the `analyze_prompt_with_perturbations(prompt)` function with your prompt to see which tokens (words) the model thinks are the most important.

4. **Visualize the Results:**
   - Check out the generated visualizations (like bar charts and word clouds), which show how much impact each token has on the output.

## 📊 Visualizations
Here are the kinds of visualizations you'll see:
- **Bar Chart of Average Saliency Scores:** Shows how important each word is in your description.
- **Word Cloud:** A way to visualize the most significant words, where bigger words mean more importance.
- **Distribution of Saliency Scores:** Gives you a sense of how scores are spread out across all the tokens.
- **Heatmap:** Highlights the saliency scores across multiple runs, helping you see variations in token importance.

## 📈 Results Interpretation
- **High Saliency Tokens:** These are the words that the model thinks are crucial for generating the output (like "aroma" or "filled").
- **Medium Saliency Tokens:** These are helpful but not critical (like "freshly" or "melted").
- **Low Saliency Tokens:** These words don't have much impact on the model’s decision (like "the" or "over").

## 🔍 Key Takeaways

#### Model Understanding
1. GPT-2 shows sophisticated semantic hierarchy processing
2. Strong position-dependent processing effects
3. Clear preference for experiential over structural content
4. Robust handling of semantic relationships

#### Token Interactions
1. Strong forward propagation effects
2. Semantic clustering influences token importance
3. Position affects token interdependence

#### Semantic Recommendations
1. Prioritize sensory language
2. Use concrete nouns as semantic anchors
3. Minimize structural words where possible

#### Structural Recommendations
1. Lead with high-impact sensory words
2. Group related descriptors together
3. Place key descriptors in early/mid sequence

#### Style Recommendations
1. Create semantic clusters for stronger impact
2. Use token position to improve importance
3. Consider interdependence in word choice


## 🔚 Conclusion
This analysis gives us a deeper look into how GPT-2 understands food descriptions. By visualizing token importance, we can see what the model focuses on when generating text.
