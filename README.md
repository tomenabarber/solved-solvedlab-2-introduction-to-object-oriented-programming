Download Link: https://assignmentchef.com/product/solved-solvedlab-2-introduction-to-object-oriented-programming
<br>
Designing classesCreate a new Python file in your lab2 folder and name it lab2.py. Your task is to perform an “object-oriented analysis” of a problem specification, outlined in the steps below.

Read the specifications in specs.txt (click on the filename to open the file — it’s a link). First, identify the classes you’d like to have. Remember that a class usually models some noun in the problem description, but that not every noun needs an entire class to model it. For example, an email address can be modelled by a simple str.Next, picture how your classes will be used by writing some code in the if __name__ == ‘__main__’} block of lab2.py which does the following:Create a race registry.Register the following runners:

Gerhard (with time under 40 minutes),Tom (with time under 30 minutes),Toni (with time under 20 minutes),Margot (with time under 30 minutes),and Gerhard (with time under 30 minutes — he’s gotten faster).Report the runners in the speed category of under 30 minutes.

Remember, you haven’t written the classes yet! This main block will help you to do that, just like the doctest examples in a function’s docstring help you write the function.Then, use Part 1 of the Class Design Recipe to create the public interface of each class. (You already chose a part of it in the previous step.) Note that this involves a lot of documentation and writing of basic examples and tests, but still no implementation whatsoever. That will come later.

This analysis will require a fair amount of thought. Don’t worry about getting it completely right — if you think the specifications are ambiguous, write down your problem, and try to come up with a solution you think is reasonable. A good skill to develop in this course is identifying ambiguities and proposing multiple solutions for such ambiguities in problem descriptions you receive.Implementing your designNow, take your design and implement all of the methods in each of the classes you defined.

This may involve defining additional private attributes and methods that are not part of the public interface of a class — remember to follow the naming convention of starting such identifiers with an underscore.

Use your example from earlier (and build upon it) to help check the correctness of your code.

Additional practiceAs well as the race registry, here are some additional exercises in designing and implementing classes.

We certainly don’t expect you to do these exercises in the lab, but they are here for additional practice.

Object-oriented analysisAs the problems get larger, it becomes more important to be able to focus on high level design before getting into details. We can record a high-level design with a simple drawing. Here is a design for our Twitter example from class. Notice that this drawing omits details such as what type we should use for each piece of data, what parameters each method should have, and so on. We can decide on these later, once we have settled on the overall design.

Read the specifications for this larger problem in specs_larger.txt. Circle the nouns and underline the verbs.Using the same diagram style as in the example above, come up with a design for this software. There is a lot of judgement involved, and there are multiple good solutions. The point here is to think about and debate some options, and start to get comfortable with the process.