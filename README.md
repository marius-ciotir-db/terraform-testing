# terraform - testing

In this terraform testing guide, we will talk about most popular tools which are available for testing Terraform code. For the moment, the analysis is done using
- Test kitchen-terrafrom plugin and GCP InSpec plugin

**Highlights**


**Kitchen Terraform Plugin**
- This plugin is designed to work with tool test kitchen.
- The tool test kithen is written in Ruby.
- The infra is being launched using terraform driver with test variables.
- The verification is done using inspec.
- For more detailed documentation - please check readme under kithen folder

### demo_test

