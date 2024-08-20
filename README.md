# HashiCorp Packer Labs

This repository contains a series of labs designed to help you master HashiCorp Packer, a tool for creating machine images for multiple platforms from a single source configuration. Each lab focuses on different aspects of Packer, from writing templates to building images across multiple regions and clouds.

## Labs Overview

### Lab 0 - Install Packer
This lab guides you through the installation of Packer on your local machine. You'll learn how to set up your environment to start building images with Packer.

### Lab 01 - Writing Packer Template
Learn the basics of writing a Packer template. This lab covers the structure of a Packer template and the essential elements required to define an image build.

### Lab 02 - Packer CLI
Explore the Packer Command Line Interface (CLI) in this lab. You'll learn how to use various Packer commands to validate, inspect, and build images from your templates.

### Lab 03 - Building Images in Multiple Regions
Discover how to build machine images across multiple regions. This lab focuses on leveraging Packer to create consistent images in different geographical locations.

### Lab 04 - Provisioners
In this lab, you'll learn how to use provisioners to customize images during the build process. Provisioners allow you to install software, configure settings, and perform other tasks on your images.

### Lab 05 - Post Processors
Explore the use of post-processors to automate tasks after an image is built. This lab covers how to compress, upload, and share your images with post-processors.

### Lab 06 - Packer Variables
Learn how to use variables in Packer templates to create flexible and reusable configurations. This lab demonstrates the use of variable files and environment variables in Packer.

### Lab 07a - Building Multiple Image Types - Linux
Focus on building different types of images for Linux environments. This lab shows how to configure Packer templates to create AMIs, Docker images, and other formats.

### Lab 07b - Building Multiple Image Types - Windows
Similar to Lab 07a, this lab focuses on building multiple image types, but for Windows environments. You'll learn how to create various Windows images using Packer.

### Lab 08 - Validate Image with Terraform
Learn how to validate the images you build using Terraform. This lab demonstrates the integration between Packer and Terraform for automated image validation.

### Lab 09 - Building Images in Multiple Clouds
Explore how to build images in multiple cloud environments. This lab shows you how to use Packer to create images for AWS, Azure, GCP, and other cloud providers.

### Lab 10 - Code Organization
Understand the best practices for organizing your Packer code. This lab covers how to structure your templates, variables, and scripts for maintainability and scalability.

### Lab 11 - Targeting Cloud Builds
Learn how to target specific cloud environments for your image builds. This lab focuses on configuring Packer to build images tailored for AWS, Azure, and other clouds.

### Lab 12 - Packer Debug
Discover debugging techniques for Packer. This lab shows how to use Packer's built-in debugging tools to troubleshoot and resolve issues during image builds.

### Lab 13 - Packer Breakpoints
Explore the use of breakpoints in Packer to pause the build process at specific points. This lab teaches you how to inspect and modify your builds interactively.

### Lab 14 - Packer and Terraform
Learn how to integrate Packer with Terraform to create and manage infrastructure. This lab demonstrates the workflow of building images with Packer and deploying them using Terraform.

### Lab Optional - Converting Packer JSON Templates to HCL
Explore the process of converting existing Packer JSON templates to the new HCL (HashiCorp Configuration Language) format. This lab helps you transition to the modern syntax for Packer templates.
