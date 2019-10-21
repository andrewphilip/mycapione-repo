# mycapione-repo
Repo that has info regarding my contribution info


2019-Half yearly contribution:
  1.  got onboarding on Turing platform; progressively gaining knowlege of all the components of Turing .
  2.  was able to test GM-blacklisted tokens in EMR cluster in prod.
  3.  developed and tested standalone client to test java-sdk with concurrent requests from batch size of 5000+ items 
  4.  contributing in the SHA1 - to SHA2 office hours 
  5.  on one instance was able to address client with regard to hystrix fallback queries via bridge call
-----------------------------------------------------------------------

[10/21/2019]

List of tasks I worked on so far..

1.  Worked on  standalone app to do concurrent tokenize operation using Turing-java-sdk and  studied the outcomes modifying factors like  changing thread-core-size, concurrent_timeout, batchsize, max-queue-size etc.,

2. Worked on GM- Blacklisted tokens; created standalone app using flink framework to test blacklisted token use case

3. Worked on the perf test on the RR- utilization; created multiple scenarios toggling RR lookup enable/disable; RO/RW mode; used EMR to test with dataset of 5mil records and changed the config parameters in the app_config.json  on the ec2 instance; verified the results using datadog dashboards and spunk.

4. Worked on adding overloaded methods for tokenize,detokenize using  an additional  argument (message-id) in the Turing-java-sdk

5. Co-ordinated with the MFA team to get the MFA implementation on non-prod/prod  for UI

6. Worked on improving code-coverage for batch-sdk from 42  to 65%

7. Worked on  the Datadog dashboard:  in an effort to make sure we have synced up all the prod datadog  in non-prod environment (alongside with Raja).

8. worked on turing-ui dockerization :

  a. worked on the ECS CFT to provision ecs cluster with ECS service, Task and all the necessary scaling policies
    and alarms.

  b. worked on the getActiveStack, switchTraffic, checkWeightedRecords scripts

  c. worked on the jenkins pipeline declarative script for NPI as well as for PreCDE.

  d. worked on the UI dockerization in PreCDE ( had lot of challenges here along the way)

------------------------------------------------------------------------------
