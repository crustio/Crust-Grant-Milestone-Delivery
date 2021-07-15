# Milestone Delivery

> Only the GitHub account, which is responsible for the pull request of the accepted application is allowed to submit milestones. 

Before submit this milestone delivery, please make sure: **The [invoice form](https://docs.google.com/forms/d/e/1FAIpQLSfxKTRtoMzvqQiBL71YXA6gxl_XSsyNBHEBksFFC2AwWReU1w/viewform?usp=sf_link) has been filled out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](milestone-deliverables-guidelines.md).**  

Please provide `https://github.com/crustio/Crust-Grants-Program/pull/9` and `Milestone 1` at following.
* **PR Link:** Provide a link to the initial accepted pull request of your application to the [Crust Grants Program repository](https://github.com/crustio/Crust-Grants-Program). 
* **Milestone Number:** The number of the milestone

Please provide a list of all deliverables of the milestone extracted from the initial application and a link to the deliverable itself. Ideally all links inside the below table should include a commit hash, which will be used for testing. If you don't provide a commit hash, we will work off the default branch of your repository. Thus, if you plan on continuing work after delivery, we suggest you create a separate branch for either the delivery or your continuing work.


| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 0a. | License - Apache 2.0 | https://github.com/skyekiwi/skyekiwi-protocol/blob/master/   |                                       |
| 0b. | Documentation |https://github.com/skyekiwi/skyekiwi-protocol/blob/master/README.md| Installation & Testing guide |
| 1. | Sample Smart Contract |https://github.com/skyekiwi/skyekiwi-protocol/tree/master/contract| Running & Testing guide provide in 0b |
| 2a. | Protocol Library |https://github.com/skyekiwi/skyekiwi-protocol/tree/master/src|  |
| 2b. | Tests |https://github.com/skyekiwi/skyekiwi-protocol/tree/master/spec| Integration & Unit tests |

**Notes on versioning:** 

1. as of submitting this delivery PR, all work except for the master `README.md` are done and tested on the master branch as of `https://github.com/skyekiwi/skyekiwi-protocol/commit/7b4ba74c285a91ae4130f9dc64582ae34cf44ccd` 
2. My local environment for testing as listed in `README.md`
3. Crust Network integration was only done on the Rocky testnet. It should be not much difference but let me know if you would like to see a main-net testing result. 



**Notes of Known Flaws:**

1. As of submitting this PR, the only known issue would be a very slow SSS Library `secret.js` but it's not easy to get another audited javascript native TSS implementation. Priority: medium. 
2. `Seal` & `EncryptionSchema` might still be a bit messy, especially on `SkyeKiwi.Driver.updateEncryptionSchema`. Priority: high. 
3. No global logger. Priority: low
4. No TypeScript standard type file. Priority: low
5. No CI/CD setup... yet. Priority: medium









