# Actions and Condition Context Keys for AWS CodeCommit<a name="list_codecommit"></a>

AWS CodeCommit \(service prefix: codecommit\) provides the following service\-specific actions and condition context keys for use in IAM policies\.

**Actions for AWS CodeCommit**

For information about using the following AWS CodeCommit actions in an IAM policy, see [Access Permissions Reference](http://docs.aws.amazon.com/codecommit/latest/userguide/access-permissions.html) in the *[AWS CodeCommit User Guide](http://docs.aws.amazon.com/codecommit/latest/userguide/)*\.

+ `[codecommit:GetBranch](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetBranch.html)`

+ `[codecommit:GetBlob](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetBlob.html)`

+ `[codecommit:PutRepositoryTriggers](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_PutRepositoryTriggers.html)`

+ `[codecommit:GetCommit](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetCommit.html)`

+ `[codecommit:GetRepository](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetRepository.html)`

+ `codecommit:GitPull` \- this is an IAM policy permission only, not an API action that can be called\.

+ `[codecommit:GetRepositoryTriggers](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetRepositoryTriggers.html)`

+ `[codecommit:DescribePullRequestEvents](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_DescribePullRequestEvents.html)`

+ `[codecommit:GetCommitHistory](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetCommitHistory.html)`

+ `codecommit:GetTree` \- this is an IAM policy permission only, not an API action that can be called\.

+ `[codecommit:GetComment](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetComment.html)`

+ `[codecommit:UpdatePullRequestDescription](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_UpdatePullRequestDescription.html)`

+ `[codecommit:ListBranches](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_ListBranches.html)`

+ `[codecommit:DeleteRepository](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_DeleteRepository.html)`

+ `[codecommit:ListRepositories](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_ListRepositories.html)`

+ `[codecommit:UpdateRepositoryDescription](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_UpdateRepositoryDescription.html)`

+ `[codecommit:GetPullRequest](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetPullRequest.html)`

+ `[codecommit:UpdateRepositoryName](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_UpdateRepositoryName.html)`

+ `[codecommit:GetUploadArchiveStatus](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetUploadArchiveStatus.html)`

+ `[codecommit:PostCommentReply](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_PostCommentReply.html)`

+ `[codecommit:GetCommitsFromMergeBase](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetCommitsFromMergeBase.html)`

+ `[codecommit:DeleteBranch](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_DeleteBranch.html)`

+ `[codecommit:CreateRepository](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_CreateRepository.html)`

+ `[codecommit:ListPullRequests](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_ListPullRequests.html)`

+ `[codecommit:UpdatePullRequestStatus](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_UpdatePullRequestStatus.html)`

+ `[codecommit:GetCommentsForPullRequest](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetCommentsForPullRequest.html)`

+ `[codecommit:GetMergeConflicts](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetMergeConflicts.html)`

+ `codecommit:GetObjectIdentifier` \- this is an IAM policy permission only, not an API action that can be called\.

+ `[codecommit:DeleteCommentContent](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_DeleteCommentContent.html)`

+ `[codecommit:MergePullRequestByFastForward](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_MergePullRequestByFastForward.html)`

+ `[codecommit:CreatePullRequest](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_CreatePullRequest.html)`

+ `[codecommit:TestRepositoryTriggers](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_TestRepositoryTriggers.html)`

+ `[codecommit:UpdateComment](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_UpdateComment.html)`

+ `[codecommit:PostCommentForComparedCommit](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_PostCommentForComparedCommit.html)`

+ `[codecommit:GetCommentsForComparedCommit](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetCommentsForComparedCommit.html)`

+ `[codecommit:UpdateDefaultBranch](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_UpdateDefaultBranch.html)`

+ `[codecommit:CreateBranch](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_CreateBranch.html)`

+ `[codecommit:UpdatePullRequestTitle](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_UpdatePullRequestTitle.html)`

+ `[codecommit:GetReferences](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_GetReferences.html)`

+ `[codecommit:UploadArchive](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_UploadArchive.html)`

+ `[codecommit:BatchGetPullRequests](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_BatchGetPullRequests.html)`

+ `codecommit:GitPush` \- this is an IAM policy permission only, not an API action that can be called\.

+ `[codecommit:BatchGetRepositories](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_BatchGetRepositories.html)`

+ `[codecommit:CancelUploadArchive](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_CancelUploadArchive.html)`

+ `[codecommit:PostCommentForPullRequest](http://docs.aws.amazon.com/codecommit/latest/APIReference/API_PostCommentForPullRequest.html)`

**Condition context keys for AWS CodeCommit**

AWS CodeCommit has no service\-specific context keys that can be used in an IAM policy\. For the list of the global condition context keys that are available to all services, see [Available Global Condition Keys](reference_policies_condition-keys.md#AvailableKeys) in the *IAM Policy Elements Reference*\.