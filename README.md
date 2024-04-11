# GitHub Cheatsheet

This cheatsheet contains some useful commands and tips for working with GitHub.

## Table of Contents

1. [Introduction](#introduction)
2. [Setting up Git](#setting-up-git)
3. [Creating and Cloning Repositories](#creating-and-cloning-repositories)
4. [Making Changes](#making-changes)
5. [Branching](#branching)
6. [Committing Changes](#committing-changes)
7. [Pushing Changes](#pushing-changes)
8. [Pull Requests](#pull-requests)
9. [Merging Changes](#merging-changes)
10. [Resolving Merge Conflicts](#resolving-merge-conflicts)
11. [Collaborating with Others](#collaborating-with-others)
12. [GitHub Pages](#github-pages)

  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--     <title>GitHub Cheatsheet</title> -->
</head>
<body>

<section id="introduction">
    <h1>GitHub Cheatsheet</h1>
    <p>This cheatsheet contains some useful commands and tips for working with GitHub.</p>
</section>

<section id="setting-up-git">
    <h2>Setting up Git</h2>
    <ul>
        <li>Install Git: <a href="https://git-scm.com/downloads">Download and install Git</a></li>
        <li>Configure Git: Set your username and email address</li>
        <code>
            <pre>git config --global user.name "Your Name"</pre>
            <pre>git config --global user.email "your.email@example.com"</pre>
        </code>
    </ul>
</section>

<section id="creating-and-cloning-repositories">
    <h2>Creating and Cloning Repositories</h2>
    <ul>
        <li>Create a new repository on GitHub</li>
        <li>Clone a repository to your local machine</li>
        <code><pre>git clone &lt;repository_url&gt;</pre></code>
    </ul>
</section>

<section id="making-changes">
    <h2>Making Changes</h2>
    <ul>
        <li>View the status of your working directory and staging area</li>
        <code><pre>git status</pre></code>
        <li>Add files to the staging area</li>
        <code><pre>git add &lt;file_name&gt;</pre></code>
        <li>Remove files from the staging area</li>
        <code><pre>git reset &lt;file_name&gt;</pre></code>
    </ul>
</section>

<!-- Other sections omitted for brevity -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Commands Cheatsheet</title>
</head>
<body>

<section id="branching">
    <h2>Branching</h2>
    <p>Branching allows you to diverge from the main line of development and continue to work without messing with the main codebase. It's useful for working on new features or fixing bugs without affecting the main project.</p>
    <p><strong>How to use:</strong></p>
    <ul>
        <li>Create a new branch: <code>git checkout -b &lt;branch_name&gt;</code></li>
        <li>Switch to an existing branch: <code>git checkout &lt;branch_name&gt;</code></li>
    </ul>
</section>

<section id="committing-changes">
    <h2>Committing Changes</h2>
    <p>Committing changes saves your work to the local repository. It's important to commit regularly to track your progress and keep a history of changes.</p>
    <p><strong>How to use:</strong></p>
    <ul>
        <li>Commit changes: <code>git commit -m "Commit message"</code></li>
    </ul>
</section>

<section id="pushing-changes">
    <h2>Pushing Changes</h2>
    <p>Pushing changes sends your committed changes to a remote repository, making them accessible to others. It's necessary to push changes to collaborate with others and keep remote repositories up-to-date.</p>
    <p><strong>How to use:</strong></p>
    <ul>
        <li>Push changes to a remote repository: <code>git push origin &lt;branch_name&gt;</code></li>
    </ul>
</section>

<section id="pull-requests">
    <h2>Pull Requests</h2>
    <p>Pull requests are used to propose changes and request them to be merged into the main codebase. They facilitate collaboration and code review among team members.</p>
    <p><strong>How to use:</strong></p>
    <ul>
        <li>Create a pull request on GitHub</li>
        <li>Review and discuss changes with collaborators</li>
        <li>Merge pull requests to incorporate changes into the main branch</li>
    </ul>
</section>

<section id="merging-changes">
    <h2>Merging Changes</h2>
    <p>Merging combines changes from one branch into another. It's used to integrate feature branches or bug fixes back into the main codebase.</p>
    <p><strong>How to use:</strong></p>
    <ul>
        <li>Merge changes from one branch into another: <code>git merge &lt;branch_name&gt;</code></li>
    </ul>
</section>

<section id="resolving-merge-conflicts">
    <h2>Resolving Merge Conflicts</h2>
    <p>Merge conflicts occur when Git is unable to automatically merge changes. They need to be resolved manually by the user to proceed with the merge.</p>
    <p><strong>How to use:</strong></p>
    <ul>
        <li>Identify conflicting files</li>
        <li>Manually resolve conflicts within conflicting files</li>
        <li>Add resolved files to the staging area</li>
        <li>Commit the merge</li>
    </ul>
</section>

<section id="collaborating-with-others">
    <h2>Collaborating with Others</h2>
    <p>Collaboration on GitHub involves adding collaborators to your repository, assigning tasks, reviewing code, and using issues and project boards to manage tasks and workflow.</p>
    <p><strong>How to use:</strong></p>
    <ul>
        <li>Add collaborators to your repository</li>
        <li>Assign tasks and review code in pull requests</li>
        <li>Use issues and project boards to manage tasks</li>
    </ul>
</section>

<section id="github-pages">
    <h2>GitHub Pages</h2>
    <p>GitHub Pages allows you to host static websites directly from your GitHub repositories. It's a great way to showcase your projects, documentation, or personal website.</p>
    <p><strong>How to use:</strong></p>
    <ul>
        <li>Create a new branch named <code>gh-pages</code></li>
        <li>Commit your HTML, CSS, and JavaScript files to this branch</li>
        <li>Visit your repository's settings and enable GitHub Pages, selecting the <code>gh-pages</code> branch as the source</li>
        <li>Your website will be published at <code>https://&lt;username&gt;.github.io/&lt;repository_name&gt;/</code></li>
    </ul>
</section>

</body>
</html>


</body>
</html>
