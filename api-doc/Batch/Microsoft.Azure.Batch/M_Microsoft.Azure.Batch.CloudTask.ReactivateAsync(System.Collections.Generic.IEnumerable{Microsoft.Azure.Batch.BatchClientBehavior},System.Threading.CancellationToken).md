## Remarks  
 Reactivation makes a task eligible to be retried again up to its maximum retry count.  
  
 This operation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).             Additionally, this will fail if the job is in the [Microsoft.Azure.Batch](assetId:///N:Microsoft.Azure.Batch?qualifyHint=False&autoUpgrade=True) or [Completed](assetId:///T:Microsoft.Azure.Batch.Common.JobState?qualifyHint=False&autoUpgrade=True) or [Terminating](assetId:///T:Microsoft.Azure.Batch.Common.JobState?qualifyHint=False&autoUpgrade=True) state.  
  
 The reactivate operation runs asynchronously.