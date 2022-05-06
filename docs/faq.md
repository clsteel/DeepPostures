---
layout: default
title: FAQs
nav_order: 9
---

# FAQs
{: .no_toc }


- **Q: My TensorFlow does not expect the model format.**

    **A:** To use the library you will need specific versions of TensorFlow, please refer to [Getting Started]({{ site.baseurl }}{% link getting_started/dependencies.md %})

- **Q: What Python version should I have?**

    **A:** The bare minimum you should have is Python 3. We tested and recommend using Python 3.6 as higher Python versions may cause problems with certain dependencies.

- **Q: The script runs very slow on my machine. What should I do?**

    **A:** First you need to isolate the bottleneck and the cause of slowness. If it's from data preprocessing, consider parallel processing and follow [guide]({{ site.baseurl }}{% link advanced/parallel_processing.md %}). If it's the predicting/learning part, then you should try to enable GPU (if you have one) support by installing the GPU-version of tensorflow, or consider using a more powerful machine or a machine with GPU.
    