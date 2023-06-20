# Please follow the general pull request review steps:

- [ ] Verify with developer (chat/email) that unit testing has been completed
- [ ] Static analysis results contain no high severity warnings (View analysis in Team City)
<!-- IAR and Sim warnings as well as errors are checked by the build server 
	 Static analysis results to be moved into the checklist???
	 Code licenses to be moved into the checklist???
	 API key check should be moved into the checklist???

-->

## Code review guidance:
- Review logic
- Review thread safety (if applicable)
- Review function return method
- Review data access 
- Check comments
- Check spelling
- Check spacing
- Check brackets
- Check return function handling
- Check variable names
- Check if new code has any new warnings
- Check header files have externs on function prototypes
- Check timer initialization
- Verify correct sws version update if included in the review list
<!-- Remove parts that will be performed by a code beautifier when available -->


## Next Steps
#### Merge the branch into master
Merge, not rebase. This is specifically to track which ECR was just merged in
Squash and merge are acceptable, but make sure all contributors are properly identified
####	"Co-authored-by: name <name@example.com>"
####	Clean up the comments before squash
####	Add the pull request number to the comments
####	Ensure the commit message Summary matches this template:
####	ECR ####: <ECR title/description>
#### Delete the branch 

<!-- You can remove any parts of this template not applicable to your checklist. -->
