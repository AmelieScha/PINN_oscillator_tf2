# PINN_oscillator_tf2

The notebook in this repository is based on Ben Moseley's blog post ["So, what is a physics-informed neural network?"](https://benmoseley.blog/my-research/so-what-is-a-physics-informed-neural-network/) and his original code which can be found [here](https://github.com/benmoseley/harmonic-oscillator-pinn). Please refer to Ben's blog post and code if you're interested.

My code differs from the original in that it
 - is based on **tensorflow 2** (instead of PyTorch) for neural network implementation
 - adds the option to **learn model parameters** while training the neural network

In this code, we use a simple physical example problem to explain how PINNs work, how to implement them, and demonstrate their benefit compared to regular neural nets as function approximators.

## environment setup
conda create -n pinn python=3.8   
conda activate pinn  
pip install -r requirements.txt  
