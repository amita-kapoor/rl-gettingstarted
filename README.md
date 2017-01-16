### Reinforcement Learning: getting started

This repo has the Jupyter notebook I used for the first AI Engineering meetup on January 16, 2017.

To get started, make sure you have the dependencies required for OpenAI Gym/Universe. 

Please check the [Gym docs](https://gym.openai.com/docs) and [Universe repo](https://github.com/openai/universe) for details, but broadly to execute what's in the notebook these are:

+ `macOS 10.12.2`
+ `Docker`
+ `git`
+ `Python => 3.5`

#### To get started: run the included setup script.
```sh
./setup
```

This will install the RL environments as well as keras, tflearn and other convenient deep learning libraries.

Note that this is a minimalist script for macOS that assumes a bash shell. Peek inside and change the TensorFlow version if you are on Linux, for example. Sorry, there is no Windows equivalent yet but you are welcome to make a pull request. Windows users will just need to install the deps in the script manually.

#### Next, download the latest version of the A3C starter agent kit:
```sh
# alias the repo to 'starter' for convenience
git clone https://github.com/damienstanton/universe-starter-agent starter
```

Once you have the environment set up, you can open the notebook and experiment or play with the A3C demo model.

### Further reading

[Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1602.01783)

[DeepMind lecture series on RL w/ David Silver](https://damien.codes/rl)

[Reinforcement Learning with Unsupervised Auxiliary Tasks (UNREAL)](https://arxiv.org/abs/1611.05397)

### License

Copyright (C) 2017 Damien Stanton. 

Freely distributed via the MIT License. See [LICENSE](https://github.com/damienstanton/aimeetup0/blob/master/LICENSE) file for details.