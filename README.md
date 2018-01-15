# VMware-vSphere-6.5-Cookbook-Third-Edition

his is the code repository for [VMware vSphere 6.5 Cookbook - Third Edition](https://www.packtpub.com/virtualization-and-cloud/vmware-vsphere-65-cookbook-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787127418), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

## About the book

VMware vSphere 6.5 is the next-generation infrastructure for next-generation applications. VMware vSphere is a complete and robust virtualization platform, transforming datacenters into simplified cloud infrastructures, providing virtualization solutions. Our book focuses on the latest release of VMware vSphere and follows a recipe-based approach, giving you hands-on instructions with practical applications and real-world examples.

This book starts with the procedures involved in installing or upgrading your current vSphere environment to Version 6.5 and will walk you through the new features, enhancing your vSphere environment. Then this book will cover some exciting recipes on Improved vCenter Server Appliance, vSphere automation API, vSphere fault tolerance, Virtual Volume Replication, and vCenter High availability. Moving on, this book will cover increasing performance and scalability and providing high availability solutions.

Finally this book will cover Orchestrated VM Restart using HA, HTML5 vSphere Client, and Encrypted vMotion. By the end of this book, you will have mastered all the components of vSphere 6.5 and its functionalities.

## Instructions and Navigation

All of the code is organized into folders. For example, Chapter07.

```
[CmdletBinding()]
param(
  $configData,
  $outputPath = ([IO.Path]::Combine($PSScriptRoot, 'SetupTheSite'))
)

Configuration SetupTheSite
{
  Import-DscResource -Module PSDesiredStateConfiguration
  Import-DscResource -Module xWebAdministration

```


## Related Products
* [Mastering VMware vSphere 6.5](https://www.packtpub.com/virtualization-and-cloud/mastering-vmware-vsphere-65?utm_source=github&utm_medium=repository&utm_campaign=9781787286016)
* []()


