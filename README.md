

# Multi-branch pipeline will be created here  in Jenkins shared library. 

create pipepine --> select mulit-branch pipeline and create dev-branch-1, feature-branch-2 ..etc.


* Backend server CI will be implemented using multi-branch pipeline, and CD implemented pipeline project.

 9.27.backend-shared-library
* Create a feature branch and switch to it.
git branch feature-100
git checkout -b feature-100

* Note: In Jenkins CICD, for CI pipeline we will use multibranch pipeline and it has BRANCH_NAME variable exited. For CD pipeline, We will use pipeline project.

* Note: I have faced version 1.8.0. feature-1 already existed in remote repository. You always push changes into main branch, it is the issue. You should push changes into feature-1, feature-2, feature-3.

* Create and Switch to the New Branch (recommended):
git checkout -b feature-100

* Push changes into new branch feature-100
git add .;git commit -m "k8s backend shared library"; git push -u origin feature-100;
