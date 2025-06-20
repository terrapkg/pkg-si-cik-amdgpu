# si-cik-amdgpu
Modprobe config to enable the amdgpu drivers on Southern Islands (SI) and CIK (Sea Islands).

Forcing these generations of cards to use the amdgpu driver generally improves performance, especially for gaming.

## Disclaimer
Using the amdgpu driver with SI and CIK GPUs is NOT officially supported and you SHOULD NOT report any issues with doing so to AMD or Mesa.

Using this driver with these GPUs is known in some cases to cause a higher power draw. If this is not a potential tradeoff you are comfortable with, please do not use this config.
