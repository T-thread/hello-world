# Please follow the general pull request review steps:

- [ ] The IAR project compiles with no significant warnings
- [ ] The Simulator compiles with no significant warnings 
- [ ] Verify with developer (chat/email) that unit testing has been completed
- [ ] Check if code liceneses are still valid
- [ ] Check if API keys are still valid for greater than one year
- [ ] Static analysis results contain no high severity warnings (View analysis in Team City)

## Code review guidance:
<!-->
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
-->

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

<!-- You can erase any parts of this template not applicable to your checklist. -->
