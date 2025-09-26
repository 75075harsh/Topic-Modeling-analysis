Data Loading

Import the Excel dataset (delhi_ai_courses_student_feedback_200.xlsx) using pandas.

Text Vectorization

Convert feedback text into numerical features using TF-IDF.

Remove stop words and ignore extremely common or rare terms.

Topic Modeling (NMF)

Apply NMF to extract hidden topics.

Specify the desired number of topics (e.g., 5).

Assign Dominant Topic

For each feedback entry, assign the topic with the highest score as the dominant topic.

Export Results

Save the DataFrame with the new dominant_topic column to topic_modeling_output.xlsx.

Recommendations for Course Improvement and Student Satisfaction

Enhance Practical Labs and Hands-On Sessions

Feedback highlights appreciation for practical labs, but also suggests some topics need more exercises.

Action: Increase interactive coding sessions and project-based exercises.

Improve Course Content Clarity

Some reviews mention complex topics or insufficient explanations.

Action: Simplify explanations, provide step-by-step guides, and include more real-world examples.

Balance Technical Depth and Business Relevance

Students value advanced technical topics like CNNs/RNNs, but also business-oriented case studies.

Action: Maintain a balance between deep technical content and practical applications in business contexts.

Optimize Course Pace and Duration

Mixed feedback on course length and speed.

Action: Offer optional supplementary sessions for challenging topics and provide recorded sessions for self-paced learning.

Enhance Instructor Support and Feedback

Positive feedback when instructors are clear and supportive.

Action: Introduce Q&A sessions, discussion forums, and personalized feedback to address doubts.

Leverage Feedback for Continuous Improvement

Topic modeling helps identify frequently discussed themes like labs, content clarity, assignments.

Action: Regularly analyze feedback and iterate course content based on dominant topics and student sentiment.

Focus on Student Engagement

Feedback shows that students appreciate interactive elements and clear demonstrations.

Action: Include quizzes, polls, and group activities to increase engagement and reinforce learning.

Monitor Ratings and Emotions

Use sentiment or emotion analysis alongside topic modeling to track satisfaction trends.

Action: Quickly address negative feedback and enhance areas with lower satisfaction scores.
