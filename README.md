# CHP-Gen-Drive-Model


## Machine & Model Validation ##

- RTRCSystemValidation.mlx
- RTRCSystemValidation.slx

These files contain the continuous time model to validate the general behavior of the high speed RTRC intended system. This model has good correlation with the RTRC provided machine datasheet. 


## Discrete Control & Autogen Code ##

- DiscereteAutogen_InitScript.mlx
- DiscereteAutogen_SystemModel.slx
- DiscereteAutogen_Controller.slx

These files contain the needed files for the autogen control code. The initialization script has machine parameters for several machines, be sure the intended machine is selected as this affects gain values. 

*This model is more sensitive to initialization parameters and states. This can cause the DC link model to not converge at the first few time steps.*