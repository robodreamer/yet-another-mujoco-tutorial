# Yet Another MuJoCo Tutorial

Our beloved [MuJoCo](https://github.com/deepmind/mujoco) has depricated the previous [MuJoCo Python bindings](https://github.com/deepmind/mujoco/blob/main/python/README.md). However, thanks to generous [DeepMind](https://www.deepmind.com/), MuJoCo is now open and free to the public and it seems like a good timing to make a tutorial for this.

One of the greatest adavantages of using MuJoCo is that we can simply install with CLI:
```
pip install mujoco
```
You may also want to install the custom viewer as well:
```
pip install mujoco-python-viewer
```

For setting up 3D mouse (SpaceMouse) driver, please refer to [pyspacemouse](https://pypi.org/project/pyspacemouse/) package.
I have used [3Dconnexion Spacemouse Wireless](https://www.amazon.com/3Dconnexion-SpaceMouse-Wireless-universal-receiver/dp/B079V367MM/ref=pd_ci_mcx_mh_mcx_views_0?pd_rd_w=qMccn&content-id=amzn1.sym.1bcf206d-941a-4dd9-9560-bdaa3c824953&pf_rd_p=1bcf206d-941a-4dd9-9560-bdaa3c824953&pf_rd_r=S17BZG2P2DAB3SSVAJQ1&pd_rd_wg=zCI1T&pd_rd_r=e7f144e0-be12-446d-af68-63cf84ec3548&pd_rd_i=B079V367MM) for the examples.

This repo has been forked from the original repo from [Sungjoon Choi](https://github.com/sjchoi86/yet-another-mujoco-tutorial). I have added some additional features to the original repo, including:
- Added Spot Model
- Added interactive IK examples with [flex-ik-solver](https://github.com/robodreamer/flex-ik-lib) using a 3D mouse input device


Contact: Andy Park <andypark.purdue@gmail.com>
