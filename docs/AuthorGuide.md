# Author Guidelines

#### Preparing your JOSE submission should be a simple task, once you have a complete software or learning module you wish to publish.

## The two submission types

JOSE accepts two types of submissions: (1) computational learning modules, created as open educational resources (OER), and (2) open-source software, created as educational technology or infrastructure.

### What are "computational learning modules"?

**JOSE is not focused in OER for "learning to code" as much as "coding to learn."**
_Computational learning modules_ are sets of lessons targeted at teaching material in any subject, supported by computing. 
The ideal size of a module is such that one could teach an intense tutorial over 1–2 days with one, or a semester-long course with a handful of them.
(Or, a module is to a course like a chapter is to a book.)
Modularity is a good-design feature of modern courses, especially online courses.
Identifying the opportunity of mudularity, the 2014 report of the Task Force on the Future of MIT Education [[PDF](http://web.mit.edu/future-report/TaskForceFinal_July28.pdf)] says:
_"a full 12-unit graduate class may be accessible only to a small number of students, while smaller modules of material may be relevant and useful for a larger audience"_ (p.12).
The report goes so far as to say that _"the very notion of a "class" may be outdated"_.
JOSE wants to encourage modular design of digital learning materials also because it will favor re-use.

## Submission requirements

JOSE submissions must be fully open, under the [Open Definition](http://opendefinition.org). This means that any text content or graphical objects should be under a Creative Commons license (ideally CC-BY) and code components should be under an [OSI-approved license](https://opensource.org/licenses).

Computational learning modules should be complete and immediately usable for self-learning or adoption by other instructors. They should make a clear contribution to teaching and learning of any subject, and they should follow good practices of instructional design (breaking things down, chunking, scaffolding).

Software submissions should make a clear contribution to the available open-source software that supports teaching and learning, or makes an educational process better (e.g., faster, easier, simpler). Examples include software to auto-grade student work, learning management systems, and student collaboration frameworks. Software should be feature-complete (no half-baked solutions).

### How to prepare a software submission?

Before starting your submission, you should:

* Have the software available in an open repository (GitHub, Bitbucket etc.) under an [OSI-approved license](https://opensource.org/licenses).
* Write a short Markdown file titled `article.md`  containing a title, author names and affiliations, summary, and key references. We provide an [sample article file](https://github.com/arfon/fidgit/tree/master/paper) to get you started.
* Ideally, also create a metadata file and include it in your repository. We provide a [script](https://gist.github.com/arfon/478b2ed49e11f984d6fb) that generates the metadata automatically.

Once you have those items in place, [submit](http://jose.theoj.org) via the JOSE web app.

### How to prepare a learning-module submission?

Before starting your submission, you should:

* Have the content in an open repository, under a Creative Commons license (ideally CC-BY), and any code components under an OSI-approved license.
* Write a short Markdown file titled `article.md`  containing a title, author names and affiliations, summary, and key references. We provide a [sample article file](https://github.com/arfon/fidgit/tree/master/paper) to get you started.
* Ideally, also create a metadata file and include it in your repository. We provide a [script](https://gist.github.com/arfon/478b2ed49e11f984d6fb) that generates the metadata automatically.

Once you have those items in place, [submit](http://jose.theoj.org) via the JOSE web app.

### What to include in the paper?

JOSE papers should contain the following:

* A list of authors and affiliations.
* A short summary describing the functionality of the software (for software submissions), or the learning objectives and instructional design (for learning modules).
* A list of key references including a link to the open archive of the sofware or the learning module.

JOSE papers contain a limited set of metadata (see header in the [sample article file](https://github.com/arfon/fidgit/tree/master/paper)), plus Summary & Reference sections. We explicitly do not publish long-form articles, because the scholarship represented by a JOSE article is contained in the software or learning modules themselves. 


## How will the review proceed?

Take a look at our [reviewer guidelines]() to help you understand what our reviewers will be looking for. Provided you have followed our pre-submission steps and meet our submission requirements then you should expect the review to proceed at a quick pace.

Review workflow:

* You submit via the JOSE web app.
* A "Pre-review" issue is created in the JOSE reviews repository on GitHub.
* An editor will be assigned or will self-assign to your submission. You will suggest an editor in the submission form.
* Editors may enter comments in the "Pre-review" issue while determining that the submission is in-scope for the journal.
* The editor will assign one or more JOSE reviewers and create the "Review" issue in our GitHub repository. (At this point, the "Pre-review" issue will be closed.)
* Reviewers will enter comments about the submission in the "Review issue," and authors respond to the comments at will. Reviewers may also open specific issues in the external issue-tracker of the submitted software or content.
* Authors make changes or improvements to the submission, as needed.
* Reviewers will check off each item of the JOSE Review Checklist.
* When the review completes, you will be asked to deposit a full archive of your (updated) repository with a data-archiving service such as Zenodo or figshare. You will update the review issue thread with the DOI for this archive.
* After assignment of a DOI (for the JOSE article), your paper metadata will be deposited in CrossRef, and the published article will be listed on the JOSE website.

### What next?

_Celebrate!_ Tweet your joy using the hashtag [#JOSE_TheOJ](https://twitter.com/hashtag/JOSE_theoj?src=hash), share your new publication in your school newsletter, and—most importantly—add it to your academic CV.

We also recommend that you add a **How to cite this work** note in the README of your repository, because we still need to educate folks about citing different scholarly works. 
