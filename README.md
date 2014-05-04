##acdeploy

`acdeploy` is an expirimental deployment system targetting Windows, though with Mono support baked in so it can be used across platforms. 

The focus is on simplicity and ease of use. While there are many deployment systems that are designed to do erything possible, the goal of `acdeploy` is to do a few things very well - and very easily. Some envirpoments may need more complex deployment and management systems, so `acdeploy` may not be right for you. It's meant to address a limited number of use cases, to maintain that simplicity.

###Project Status

Pre-Alpha

###Project Goals

 - Deployers require minimal training. Those deploying with this system should require minimal training, so that it can be hanled by a helpdesk-level group fpor organizations that don't have DevOps type teams.
 - Easily automated, so that deployments can be performed by a scheduling system (i.e. cron, etc.).
 - Minimal dependentcies; machines being deployed to should require minimal changes or new software to support `acdeploy`
 - Easy integration; it should be easy as possible for teams to start using `acdeploy`, with minimal changes to process or systems.
 
 
 ###License
 
 This software is licensed under the terms of the MIT license. See the `LICENSE` file for details.
 