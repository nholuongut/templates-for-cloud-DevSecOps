# OCI Template

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)

OCI templates will help onboard applications with application security integration. The Fortify platform supports OCI DevOps Service so DevOps teams will be able to directly leverage these templates as part of pipeline automation. OCI DevOps Service supports Continuous Delivery using defined YML files during build and release. 


1.	Build_Spec.yml : This template is used to build and generate artifacts using OCI DevOps services.


## Integrating Fortify with OCI DevOps Projects
Integrating Fortify with the CI process is fairly simple pull and push switch using the templates given in the above folders.  Fortify can be integrated using the following steps:

1. Identify your Fortify solution (Fortify on-premises or Fortify on Demand)
2. Identify the type of scan you like to integrate, then go to **SAST** folder
3. Pull and merge `build_spect_<<solution>>_template.yaml` into your local repo buildspec.yaml file.
4. Set the OCI Vault variables in the templates pulled from the repo
   - Open `build_spec.yaml`
   - Add the variables in your secret vault
6. Push it to your repository i.e. OCI Repo / GitHub
	
### Trigger the build, and you are done !!

# I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](bitfield.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.
