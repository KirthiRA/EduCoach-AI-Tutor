# EduCoach — Personalized Multi-Agent AI Tutor  
### Capstone Project — Agents for Good Track  

## **Problem**
Many students struggle to learn foundational math concepts without personalized guidance.  
Traditional learning tools provide fixed explanations and generic exercises, with minimal real-time feedback, leading to repeated mistakes and slower mastery.

## **Solution**
EduCoach is an AI-powered **multi-agent intelligent tutoring pipeline** that delivers adaptive learning by:  
- Generating structured lesson plans  
- Explaining concepts in grade-appropriate tones  
- Solving math step-by-step with verified code execution  
- Creating quizzes that adapt to student mastery  
- Evaluating answers and updating mastery scores in a Memory Bank  
- Logging all agent activity for observability and reproduction  

## **Demo Flow**
Student enters topic → Fractions – Addition
Orchestrator runs Lesson Planner → generates plan
Explainer explains in friendly tone
Solver runs verified math steps
Quiz Generator creates practice
Evaluator checks answers → sends score
Mastery + mistakes saved to SQLite → Logs stored

## **Output Files Generated**
After execution, EduCoach produces:
| Output                 | File Name             |
| ---------------------- | --------------------- |
| Question Bank          | `question_bank.csv`   |
| Student Learning State | `demo_student_1.json` |
| System Logs            | `logs/events.log`     |
| Memory                 | `memory.db`           |

## **Evaluation Metrics Demonstrated**
Auto-graded quiz accuracy
Mastery updates stored persistently
Step-level math verified using code execution
Runtime + interaction logs generated for debugging

## **Tools & Technologies Used**
Python notebook environment
Multi-Agent orchestration
SQLite for student memory
Code execution tool for math verification
JSONL logs for observability
Modular layered design

## **Future Improvements**
If given more time, EduCoach could include:
Web chat UI
More subjects (Algebra, Geometry, Physics)
Agent debate explanations for deeper reasoning
Cloud deployment for persistent sessions
Visual dashboards for progress tracking

## **Authors & Credits**
### Created by: Kiruthika Anandhan
### Capstone Track: Agents for Good


