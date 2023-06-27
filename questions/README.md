Q1.Programmatically confirm that the number of job descriptions is as expected (i.e. that
there are 50,000 distinct job descriptions in the skill2vec 50K dataset).

Q2. Work out the frequencies with which distinct skills are mentioned in job descriptions,
and present the top 10 (in order of decreasing frequency) skills in your report, alongside
the frequency of each across the entire dataset. I.e. if your dataset consists of the
following:
JD1,python,databricks,amazon web services aws software,,
JD2,python,deep learning,,,
JD3,machine learning,python,amazon web services aws software,,
Your output would be:
Skill Freq
python 3
amazon web services aws software 2
databricks 1
deep learning 1
machine learning 1

Q3. Find the 5 most frequent numbers of skills in JDs across the dataset. I.e. given the
example with JD1, JD2 and JD3 above, the expected result would be:
Num skills Freq
3 2
2 1
indicating that 2 JDs contain 3 skills while 1 JD contains only 2 skills.

Q4. So far, you've explored the dataset in its original form. Check how the distribution of
the frequencies with which distinct skills are mentioned in JDs changes if you lower case
all the skills. As in question 2, present the top 10 (in order of decreasing frequency)
skills in your report.

Q5. To gain some additional information about the sought after skills, you'd like to join
the (lower cased) skills from JDs with the skills listed in the Example column in the
O*NET dataset (don't forget to lower case the example column!). Find the change in
the number of skills before and after the join (i.e. report the number of original skills
and the skills that are both in the JD dataset and the O*NET dataset { reporting two
separate numbers).

Q6. The join you performed in Question 5 gives you access to the "Commodity Title" column.
Find the 10 most frequent "Commodity Title"s across all the job descriptions.
I.e. using the example from Question 2, the output should be:
Object or component oriented development software 3
Data base user interface and query software 2
Note that more than one skill can map to the same "Commodity Title".