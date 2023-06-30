
# SRE Interview preparation resources

This is a compilation of what might be the questions asked, if you appear for an SRE Interview as an experienced person.

Disclaimer: I would not say, this compilation would givve you all the resources but it might give you an idea.

### Common Interview rounds

  #### 1. Coding 
  - Data structures and Algorithm (easy-medium) (hard - very rare)
  - Scripting questions (log parsing, api response parsing)

  #### 2. Linux
  - Operating system concepts (*nix implementation)
  - Networking concepts

  #### 3. System Design
  Not traditional system Design, but related something you would do as an Devops/SRE, like
  - Designing CI/CD 
  - Designing logging infrastructure at scale
  - Designing monitoring infrastructure at scale

  #### 4. Troubleshooting 
  - Explain a recent incident you faced and how did you solve it.
  - Given a scenario, gie me an explanation on how would you debug it, step by step.

  #### 5. Tools specific knowledge
  - Some companies, mostly startups would like to test, how deep you understood the tools you use on daily basis.
  
     
### Resources/References

#### 1. Coding
- For DSA Refer Blind 75 leetcode problems, https://gist.github.com/krishnadey30/88c4e2f601e96597974c00185e479532
- For scripting questions like log parsing, you can expect questions like below (Refer to coding sections in below refs)https://github.com/krishnaramb/FB_Prep/wiki/linkedin https://awesomeopensource.com/project/rishiloyola/SRE-Interviews - https://leetcode.com/problems/reorder-data-in-log-files/ https://leetcode.com/problems/simplify-path/ https://leetcode.com/problems/longest-absolute-file-path/ https://yumminhuang.github.io/note/sreinterview/ https://www.reddit.com/r/sre/comments/dloa6c/how_the_heck_do_you_leetcode_prep_for_sre/ https://gist.github.com/zapalote/30aa2d7b432a08e6a7d95e536e672494 https://stackoverflow.com/questions/5419888/reading-from-a-frequently-updated-file https://azalio.wordpress.com/2016/05/29/facebook-production-engineer/ https://leetcode.com/discuss/interview-question/392017/FaceBook-Phone-screen https://leetcode.com/discuss/interview-question/685613/production-engineer-interview-questions-facebook/1205810

Note: And also have a deep knowledge about the language you are using. For example if you are using python know about GIL.

#### 2. Linux 
https://github.com/0xAX/linux-insides/blob/master/SUMMARY.md https://linkedin.github.io/school-of-sre/level102/linux_intermediate/introduction/ https://linuxopsys.com/topics/linux-interview-questions-answers  
https://www.youtube.com/watch?v=zj-ZeHuqvIQ    
https://www.youtube.com/playlist?list=PLSIUOFhnxEiC3YTdxwqZqgEY5imVL8U8J
https://rentry.co/o8ivsk

Note: Many repeated topics in all refs, but gives you an cumulative idea. And I would recommend you to read a book, if you have patience :)

#### 3. System Design 
Generic    
https://danrl.com/srm/#nalsdhttps://danrl.com/srm/#nalsd
https://gist.github.com/vasanthk/485d1c25737e8e72759f   
Logging  
https://leetcode.com/discuss/interview-question/system-design/622704/Design-a-system-to-store-and-retrieve-logs-for-all-of-eBay  
https://www.learnsteps.com/logging-infrastructure-system-design/
https://medium.datadriveninvestor.com/designing-a-centralized-logging-application-da5e0272791
Metrics monitoring, alerting   
https://www.statcan.gc.ca/en/data-science/network/monitoring-alerting-system
https://dev.to/kliukovkin/system-design-monitoring-and-alerting-system-3nnl
https://leetcode.com/discuss/interview-question/system-design/958919/System-Design-Interview-or-Service-Health-Monitoring-and-Alerting-Service    
Distriuted Systems   
https://book.mixu.net/distsys/single-page.html

#### 4. Troubleshooting
- Service A is not able to reach Service B  (Network Troubleshooting) (https://www.howtouselinux.com/post/step-by-step-to-troubleshoot-a-network-issue-in-linux)
- Service is slow https://www.howtouselinux.com/post/troubleshoot-slow-linux-server https://www.howtouselinux.com/post/troubleshoot-high-iowait-issue-on-linux-system
- Misc  https://github.com/alex/what-happens-when, https://linkedin.github.io/school-of-sre/level101/linux_networking/dns/

Note: Have a incident story in mind to tell the interviewer how did you troubleshoot it, cover all the edge cases. Backup your theory with strong reasons.

#### 5. Tools 
It is good to have tool specific knowledge like how do they work and knowing about their architecture. Starting from 

coding (python,golang) --> CI (Jenkins,Github actions) --> CD (Argocd,Spinnaker) --> infrastructure (docker, kubernetes,terraform) --> Config management (Ansible) --> Logging (loki) --> Metrics aggregation/alerting (Prometheus,grafana) --> perf testing(Locust) --> cloud (aws,azure)  etc.












