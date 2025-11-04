# Short Response Questions

1. If you are collaborating with a classmate, what is the first thing that each of the team members needs to do? Why is it important to do this step?
Hint: After this step each team member would have diverged from the main branch!

`If you are collaborating with a classmate, you have to make sure that both are working in different tasks and no one is working in the main branch. In addition, when creating the branch the name should describe what your gonna do in that branch.`

- *Ex.*
```
git branch bugFix/fixing-typos-lisseth
```

2. Why do developers use branches?

`Developers use branches to continue working without affecting the main branch.`

3. What is git? What is github? How does git and github work together?

`Git is a Distributed Version Control System. Github is a cloud based service that allows developers to store, track, manage, and control changes to their code. We use Git in Github when we are creating our code sinceggi`

4. What is wrong with the following command sequence? What should be the correct command sequence?

```
git commit -m "saving work"
git add .
git push
```

`The commands are correct, but in the wrong order. The correct code is:`

```
git add .
git commit -m "saving work"
git push
```