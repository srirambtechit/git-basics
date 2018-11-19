# git-basics

## Mardown content online editor
https://stackedit.io/app#

## Getting Started

Download and install the Git command line extension. You only have to set up Git LFS once.

`git lfs install`

Select the file types you'd like Git LFS to manage (or directly edit your .gitattributes). You can configure additional file extensions at anytime.

`git lfs track "*.psd"`

Make sure .gitattributes is tracked

`git add .gitattributes`
There is no step three. Just commit and push to GitHub as you normally would.

`git add file.psd`
`git commit -m "Add design file"`
`git push origin master`
