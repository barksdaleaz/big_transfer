## Summary of Transfer Learning

Children learn at an astonishing rate due in part to a phenomenon called transfer learning. In humans, transfer learning refers to the ability to generalize across a large number of classes and accurately identify objects---or more abstract concepts---based on as few as one single example [(Brown & Kane, 1988)](https://experts.umn.edu/en/publications/preschool-children-can-learn-to-transfer-learning-to-learn-and-le). If a child is shown a picture of a cow, they will then be able to extrapolate from that one image and point to cows on a farm. The child may also point to a giraffe because both cows and giraffes have spots and four legs; based on the two prominent features of a cow, this guess aligns with Edward Thorndike’s foundational theories that physical or perceptual similarity is necessary for transfer learning (Brown & Kane, 1988; [Thorndike 1913](https://psycnet.apa.org/record/2009-03129-000)). Within the realm of artificial intelligence and machine learning, “transfer learning” is based on the same concept of using prior knowledge in order to identify objects or complete tasks in a novel but similar domain. 

In stark contrast to humans, a traditional object-classification system requires a large number of training examples, and addresses isolated tasks [(Li, 2006)](https://www.semanticscholar.org/paper/Knowledge-transfer-in-learning-to-recognize-visual-Fei-Fei/35a198cc4d38bd2db60cda96ea4cb7b12369fd3c). Depending on the dimensionality of the image representations and the specific algorithm, the number of training examples could range from hundreds to thousands, resulting in an expensive and time-consuming computation process (Li, 2006). Transfer learning aims to mitigate this issue [(Torrey & Shavlik, 2009)](http://pages.cs.wisc.edu/~shavlik/abstracts/torrey.handbook09.abstract.html). To back up the claim that transfer learning does indeed improve learning, there are three metrics used: the initial performance using only transfer learning, the amount of time it takes to fully learn the task given transferred knowledge compared to the time it takes to learn the task from scratch, and the final performance level achievable in the target task compared to learning from scratch (Torrey & Shavlik, 2009). The different forms of knowledge transfer can be categorized by model parameters, feature or part sharing, or contextual information (Li, 2006). Contextual information refers to the fact that objects typically do not exist by themselves but rather surrounded by other objects that interact together. Use of the environment is common to help recognize objects (Li, 2006). Naturally, it has been observed that a learning agent in a real-life setting is more likely to encounter situations that require transfer learning (Torrey & Shavlik, 2009).

Unfortunately, it is possible for transfer learning to backfire. This undesirable outcome is called negative transfer, and causes performance to decrease (Torrey & Shavlik, 2009). Negative transfer may occur when the source task is not sufficiently related, or the relationship is not well leveraged by the transfer method (Torrey & Shavlik, 2009). Transfer methods should ideally produce positive transfer and avoid negative transfer in situations where the tasks are not a good match; however, this has been shown to be difficult to achieve simultaneously (Torrey & Shavlik, 2009). When safeguards are put in place to avoid negative transfer, there is a weaker positive effect, but aggressive transfer methods that produce large positive effects have no protections against negative transfer (Torrey & Shavlik, 2009). Three ways of avoiding negative transfer include rejecting bad information while learning the target task, choosing the best source task, and modeling the similarity between tasks and including this information in the transfer method (Torrey & Shavlik, 2009).

Transfer learning as a whole is a promising and desirable avenue in the realm of machine learning. Relevant challenges include avoiding negative transfer and automating task mapping, something easy to perform for humans but difficult to recreate in artificial intelligence (Torrey & Shavlik, 2009). The field of transfer learning is also moving toward enabling transfer between diverse tasks and performing transfer with more complex tasks. Overall, transfer learning is poised to become a standard in the field of machine learning and artificial intelligence.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/barksdaleaz/big_transfer/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
