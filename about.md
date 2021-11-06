---
layout: home_original
---


<div class="header">
	<h2>
	<center><span style="color:#b11170">Workshop on Open Problems in Learning and Verification of Neural Networks</span></center>
	</h2>
</div>

<style>
body {
text-align: justify}
</style>


Machine learning (ML) and neural networks in particular have  achieved superhuman performance in numerous applications. However, most existing ML techniques are domain specific and their results are often not interpretable. For domains where correctness is critical, ensuring that learned system provide worst-case guarantees is an open problem. Formal methods (FM) are rich in languages and algorithms to specify and ensure correctness, yet their application to systems involving learned components has been explored over few specific problems.

One of the major tasks in combining machine learning and formal methods---high performance and formal guarantees---is formulating correctness properties for learned system using formal languages that are amenable to verification or, in the other direction, expressing formal safety so that it can coexist with statistical ML methods. The challenge is making machine learning and formal methods speak a common language. This workshop encourages the discussion between ML and FM practitioners on open problems in achieving reliable ML-based technology. Our goal is to stimulate the investigation of various techniques and specifications in order to get closer to a general unifying approach to learning and verification. Scaling up FM with ML and certifying ML with FM have major implications on the research and practice on complex systems with learned components.

We aim to bring together researchers working on different aspects of machine learning and verification with the goal to discuss open problems and to establish collaborations for solving them. We intend to make this an exciting event for researchers worldwide, with presentations by leading scientists from both fields and discussion tables on current and future research directions.

**WOLVERINE 2021** was held on October 18, 2021. It was the first instance of the interactive discussion-centered workshop on open challenges at the intersection of formal methods and machine learning. We are excited to report that the event attracted around 40 participants, 20 of whom actively participated in the two-hour long round-table session in Gather.Town. Below we provide a short summary of the invited talks.

**Sheila Mcllraith** [[video]](https://youtu.be/mqEajzgfpho){:target="_blank"} emphasized that reward shaping and sample efficiency remain open challenges in reinforcement learning. We were introduced to the concept of reward machines as a formal method to shape rewards for a model-free RL agent. However, creating reward machines requires a tailored approach, where "one size does not fit all."

**Matthijs Spaan** gave an overview of the state of the art in safe reinforcement learning. The open questions yet to be answered are: 1) what is a useful prior knowledge that an RL agent can incorporate to learn safer? 2) how can we reason about discrete vs. continuous space? 3) can we protect against unforeseen events?

**Ofra Amir** [[video]](https://youtu.be/LBXEjcjSggk){:target="_blank"} introduced several open challenges of explainable artificial intelligence. In addition to explaining agent's actions, we might want to interpret the environment itself. However, existing approaches focus on visual domains and we are yet to develop techniques for non-visual domains. Most importantly, every human user is unique and explanations we generate must adapt to individuals who interpret them.

**Guy Katz** [[video]](https://youtu.be/Dizhvw3TfSM){:target="_blank"} presented a notion of adversarial robustness as a universal formal specification for neural-network based systems. Analyzing adversarial robustness, one can find the best attack for a given model. However, questions on who should be specifying the robustness bound remain on. Furthermore, perturbations not fitting into standard norms pose a significant challenge to verification.

**Markus Rabe** [[video]](https://youtu.be/bE6ow0ANWvw){:target="_blank"} discussed neural theorem provers and their applications in real-world problems. Multiple examples showed the advantages of neuro-symbolic methods.

**Aws Albarghouthi** demonstrated the importance of enforcing fair decision making and raised concerns about long-term effects of the unfair decisions taken by a learned system.

We would like to thank all participants and are looking forward to the next WOLVERINE, which will take place at [FLoC 2022](https://floc2022.org/). We plan to enhance the workshop experience with the lessons and feedback we gathered.
