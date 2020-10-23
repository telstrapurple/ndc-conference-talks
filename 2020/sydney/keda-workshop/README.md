# KEDA, Scale Your Kubernetes Workload on Your Own Terms

As part of NDC Sydney 2020, Emad Alashi has conducted a workshop titled "*KEDA, Scale Your Kubernetes Workload on Your Own Terms*". Below is a summary of the workshop, the presentation and the workshop content can be [found here](https://github.com/eashi/keda-workshop/).

## Summary

Kubernetes is a powerful platform to host various kind of workloads, and these workloads vary in their need of scale. For that, Kubernetes has built-in functionality to scale these workloads based on their resources consumption like CPU and memory. 

However, there is no built-in way to scale workloads based on events that happen outside of the cluster; e.g. the length of a storage queue in the cloud. 

KEDA came in to fill this gap with various built-in scalers that come with the package. You can also write your own scaler that responds to your own events and needs. 

In this session we will understand what KEDA is, how it works, and how we can build our own scaler that scales our workloads to our own events and needs. 

## About Emad Alashi

[Emad Alashi](https://emadashi.com) is a software developer whose main interest is in web development, Software Architecture, Software Management, and the human interaction caught in between.

Emad speaks regularly in conferences and user groups, including NDC Sydney, Microsoft Ignite Australia, and in local user groups and code camps like Vic.Net, Azure Meetup, Azure Bootcamps, and Alt.Net in Melbourne Australia.

He is 4-times ASP.NET/IIS MVP, he hosts the DotNetArabi technical podcast, and on whatever time left he writes to his blog on [emadashi.com](https://emadashi.com).

Emad is currently works as a Managing Consultant Telstra Purple, he can be found on Twitter [@emadashi](https://twitter.com/emadashi).