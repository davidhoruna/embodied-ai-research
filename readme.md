# Research Vision NONHUMAN

## Topics

The idea is basically to have a structure that allows your robot to become better. But what does it mean for your robot to be better? There are several problems we will be mapping out to answer this question. Some of the most important ones are:

* **[Collection of data](topics/data_collection.md)**: This problem is essentially about how you can generate or collect data in such a way that it makes your model smarter and also able to generalize better across different states. This needs to be done in a very efficient way. 

* **[Corrections](topics/corrections.md)**: Your robot must be able to correct its own mistakes. This is closely related to the out-of-distribution problem; however, there are specific approaches to this—it’s not just about training your robot to self-correct. 

* **[Data filtering](topics/data_filtering.md)**: This problem is about how you can design an algorithm to filter the data for imitation learning algorithms. Basically, how can you measure the quality of your data? 

* **[Low-latency systems](topics/low_latency.md)**: Another line of work under evaluation is how to make these systems low-latency. This is because VLMs generally suffer from high latency when processing their architecture. Asynchronous systems can help address this problem.

* **[Low-memory systems](topics/low_memory.md)**: 

* **[Out-of-distribution](topics/ood.md)**: Many of these models are highly susceptible to distribution shifts within their states due to the limited data they have been exposed to. How do you handle this? 

* **[Reasoning in VLAs](topics/vla_reasoning.md)**: Another important aspect is how to improve your model’s capabilities using the same concept that emerged in LLMs: reasoning. There are several works such as Molmo ACT, where reasoning essentially consists of adding more sources of information that the VLM must predict, with discretized actions such as strokes or depth tokens. Other works, like COT VLA, focus on achieving reasoning by generating intermediate images that provide this visual information before completing a task. This is strongly related to world models.

* **[Reward model](topics/reward_models.md)**: Another important research line is reward models—systems that include an indicator to measure reward, i.e., how subtasks are being accomplished. The goal here is essentially to train the model so it can identify the states it is in and determine whether or not it can fulfill its task. 

* **[Spatial Reasoning](topics/spatial_reasoning.md)**: There are also works, such as those from NVIDIA, that aim to improve the spatial reasoning capabilities of VLMs so they can better understand the world and how physical objects behave.

* **[User interaction](topics/user_interaction.md)**: There are also challenges around improving how robots interact with humans. This problem is essentially about making these systems more natural and useful in human interaction.

* **[VLAs](topics/vlas.md)**: In general, when working with VLAs, several important features are considered. Among the main ones are **language following**, **dexterous movements**, **long-horizon tasks**, **spatial reasoning**, **low-latency systems**, and **low-memory systems**.

* **[World models](topics/world_models.md)**: Another emerging approach is how to integrate world models into VLAs. This is driven by the promise that these models will be capable of understanding the environment, which in turn can improve the policy. 

## Labs that are worth to look:

* Physicall Intelligence: https://www.physicalintelligence.company/
* Ai2: https://allenai.org/
* SkilDAi: https://www.skild.ai/