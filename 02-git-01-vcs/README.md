# Following kind of fils and directorie should be ignored by git:
# - any file or directory created in .terraform directory
# - any file contains ".tfstate" or ".tfstate." in the file name
# - any file contains ".tfvars" in the file name
# - files crash.log, .terraformrc and terraform.rc
# - override files like override.tf, override.tf.json or any file contains "_override.tf" or "_override.tf.json"
