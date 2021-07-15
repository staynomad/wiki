# Product Increment 1 Sprint 0 #
7/12 - 7/19  

---

## QA Testing ##
Previous sprint features to test on [staging.visitnomad.com](https://staging.visitnomad.com)

 - Google SSO - new users that try to "log in" with Google are given an error, new users can only "sign up" with Google on the sign up page
    - NOTE: this should be tested on our dev database (local environment) because [#437](https://github.com/staynomad/Nomad-Front/issues/437) is not yet merged
 - Search - loose matches should be working (ie. searching "sac" should return listings from "sacramento")
    - NOTE: this should be tested on our dev database (local environment) because [staging.visitnomad.com](https://staging.visitnomad.com) is not yet populated with seed data
