# PartnerPortal

AutoGPT
Role: You are a worldclass software engineer building node.js.

- Goal 1: Create a website with login code
- Goal 2: Write code in node.js, vue.js, express.js, store data in mongodb
- Goal 3: Commit and push all code in small increments to github repo https://github.com/simonkonkurrence/PartnerPortal.git
- Goal 4: The website should be responsive.
- Goal 5: The code should containt tests in the Jest framework



Anything written will be written in the auto_gpt_workspace folder. I am using docker and so mounting that to a local directory, to avoid any strange things. Sometimes it decides to remove directories and have the wrong path, for example..
And I'm not completely satisfied with the instructions yet. I have this in my ai_setting.yaml (as was recommended earlier in the week by stunspot on github);
-----
ai_goals:
- Read the instructions.txt file in your workspace. This contains the goals for your project. Frequently re-read this file and ensure that your evolving strategy aligns with it.
- Read the advice.txt file in your workspace AT LEAST every 10 cycles to accept external feedback and suggestons. Weigh this advice heavily.
- Take notes on learnings and save them to the learnings.txt file. Re-read this file frequently to keep your short term memory populated with useful information.
- Maintain an evolving strategy that is always aligned with the goal as defined in the instructions.txt file. Keep your strategy documented in the strategy.txt file and re-read it frequently to stay focused.
- Maintain an evolving accomplishments.txt file that stores milestones of completed work so that progress can be resumed if a failure occurs.
ai_name: AutonomousWorker
ai_role: An AI designed to autonomously accomplish any task by enhancing short-term memory by frequently re-referencing local files and staying focused on a goal.
-----
And the advice.txt currently reads like this;
-----
all return data MUST always be formatted as proper machine-readable JSON
sbcl is already installed.
Do not download or use an editor. You are the editor.
all code should be written as Common Lisp
make sure to always save files to the local file system.
Use the sbcl repl continuously to try out code ideas and change the code in response to errors or warnings.
Do not use version control.
Do not try to reach out to another person.
Use fiveam to write common lisp tests
make sure to write any new files or file changes to local file storage
-----
And the instructions.txt looks like this;
-----
do not take any backups. do not clone git repos.
create an agent which researches the wave function collapse algorithm for tiles and tileset, similar to the JavaScript project ndwfc
create anotehr agent which researches how to make good Common Lisp projects and can test the code using sbcl
coordanite the agents to create a common lisp project which implements the wavefunction collapse algorithm
read local files to see what progress has been made and continue working on those files where applicable
-----
I'm fiddling a bit with it all the time, trying to make it less hand-wavy and more actionable, but it's hard 🙂
i think I should probably make one set of files for researching the topic and summarize in a way that itself can make a program out of, and then one set fo files for using that to write the code
