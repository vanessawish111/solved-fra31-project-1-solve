Download Link: https://assignmentchef.com/product/solved-fra31-project-1-solve
<br>
<span class="kksr-muted">Rate this product</span>

The main objective of the final project is for you to learn something new and to start working in a way similar to a professional researcher or engineer.

1 Project description 1.1 Background

Complex multi-layer neural networks trained on large datasets have achieved a remarkable performance in several applications in recent years, in particular in speech and visual recognition tasks [Sutskever et al., 2014, Krizhevsky et al., 2012]. However, these rich models are susceptible to imperceptible perturbations [Szegedy et al., 2013]. A complex neural network may, for example, misclassify a traffic sign, as a result of a minor variation, which may be the presence of a small advertisement sticker on the sign. Such misclassifications can have dramatic consequences in practice, for example with self-driving cars. These concerns have motivated the study of adversarial robustness, that is the design of classifiers that are robust to small lp norm input perturbations [Goodfellow et al., 2014, Madry et al., 2017, Tsipras et al., 2018, Carlini and Wagner, 2017]. The standard 0/1 loss is then replaced with a more stringent adversarial loss, which requires a predictor to correctly classify an input point x and also to maintain the same classification for all points at a small lp distance of x. But, can we devise efficient learning algorithms with theoretical guarantees for the adversarial loss? In this project, you will be invited to think about this fundamental question.

1.2 Task

The task is to propose defense methods against white-box attacks on CIFAR-10. You could either come up with a new algorithm or improve existing algorithms in the literature for adversarial robustness. Your final goal is to generate a model (a trained neural network) that achieves the highest robust test accuracy on CIFAR-10 among the class (yes, this is a competition!). Using extra data is not allowed for the new algorithm. You could modify existing codes (see Section 1.5 for some examples available).

1.3 Evaluation

The robust test accuracy of the generated model should be evaluated by AutoAttack [Croce and Hein, 2020] on CIFAR-10 with l∞ attack of perturbation size ε = 8/255. You could consult https://github.com/fra31/ auto-attack to become more familiar with the tools for evaluating your models.

1.4 Submissions and requirement

We need you to form groups of 3 students (groups of 1 or 2 are not allowed) for the final project. Eventually you will be asked to submit a report in the pdf format, which contains three parts as follows:

• Algorithmic part. In this part, you should clearly describe your proposed algorithm. If your algorithm is based on the existing ones, you should also explain the difference compared to the previous algorithm.

1

<ul>

 <li>Theoretical part. In this part, you should explain the theory underpinning your proposed algorithm or give guarantees for the algorithm. In particular, you need to explain why you think the new algorithm will help achieve adversarial robustness compared to existing ones.</li>

 <li>Experimental part. In this part, you should implement your algorithm and report the robust test accuracy of your model (evaluated by AutoAttack, see Section 1.3 for more details) on CIFAR-10.You should share a GitHub link to your open source code, the trained model and a separate README file explaining how to run the code in the submission.1.5 ResourcesHere are some references on algorithms for adversarial robustness, which might be useful for the project.</li>

</ul>

• Towards Deep Learning Models Resistant to Adversarial Attacks. GitHub: https://github.com/

2

<pre>  MadryLab/cifar10_challenge</pre>

<ul>

 <li>Theoretically Principled Trade-off between Robustness and Accuracy. GitHub: https://github.com/ yaodongyu/TRADES</li>

 <li>Uncovering the Limits of Adversarial Training against Norm-Bounded Adversarial Examples. GitHub: https://github.com/deepmind/deepmind-research/tree/master/adversarial_robustness</li>

 <li>Adversarial Logit Pairing.</li>

 <li>Adversarial Weight Perturbation Helps Robust Generalization.</li>

 <li>Boosting Adversarial Training with Hypersphere Embedding.</li>

 <li>Learnable Boundary Guided Adversarial Training.</li>

 <li>Self-Adaptive Training: beyond Empirical Risk Minimization.</li>

 <li>Adversarial Robustness through Local Linearization.</li>

 <li>Bag of Tricks for Adversarial Training.</li>

 <li>Attacks Which Do Not Kill Training Make Adversarial Learning Stronger.</li>

 <li>Overfitting in Adversarially Robust Deep Learning.</li>

 <li>Robustness and Accuracy Could Be Reconcilable by (Proper) Definition.</li>

 <li>Towards Achieving Adversarial Robustness Beyond Perceptual Limits.</li>

 <li>Do Wider Neural Networks Really Help Adversarial Robustness? •⋯</li>

</ul>

<ul>

 <li> </li>