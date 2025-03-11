Introduction to the Module Block

A module is used to combine resources that are frequently used together into a reusable container. 
Individual modules can be used to construct a holistic solution required to deploy applications. 
The goal is to develop modules that can be reused in a variety of different ways, therefore reducing the amount of code that needs to be developed. 
Modules are called by a parent or root module, and any modules called by the parent module are known as child modules.

Modules can be sourced from a number of different locations, including remote, such as the Terraform module registry, or locally within a folder. 
While not required, local modules are commonly saved in a folder named modules, and each module is named for its respective function inside that folder

Modules are defined in a module block with a unique name for each module. 
Within the module block, the source indicates the local path of the module or the remote source where Terraform should download the module. 
You can also specify the version of the module to use, along with inputs that are passed to the child module.
