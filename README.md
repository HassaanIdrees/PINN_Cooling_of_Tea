# 🍵 PINN_Cooling_of_Tea: Physics-Informed Neural Networks for Cooling Your Morning Tea 🌱

We all love a perfect cup of tea in the morning. But let's be honest—sometimes it's just too hot, and we're impatiently waiting for it to cool to that delightful sipping temperature. Ever wondered about the science behind this cooling process? Welcome to an intuitive exploration of Newton's Law of Cooling using Physics-Informed Neural Networks (PINNs)!

## 📖 What's Brewing Here?
Newton's Law of Cooling describes how your tea cools down to match the room temperature. Mathematically, it is expressed as:

$$
\frac{dT}{dt} = -k \left(T - T_{\text{ambient}}\right)
$$

where:
- \( T(t) \) is the temperature of your tea at time \( t \).
- \( Tambient \) is the room (ambient) temperature.
- \( k \) is a constant related to how fast your tea cools.

### 🔍 Exact Solution
The exact analytical solution to this equation, predicting the tea’s temperature at any given time, is:

$$
T(t) = T_{\text{ambient}} + \left(T_0 - T_{\text{ambient}}\right) e^{-kt}
$$

## 🧠 Why PINNs?
Physics-Informed Neural Networks (PINNs) combine the powerful learning capabilities of neural networks with fundamental physical laws, enabling accurate predictions even with limited data.

- 📌 **Efficient:** Needs fewer measurements.
- 📌 **Reliable:** Ensures results obey the laws of physics.
- 📌 **Adaptable:** Easily tackles complex physical phenomena.

## 🚀 What's Included?
- **Google Colab Notebook:** Ready-to-run PINN implementation.
- **Clear Visualization:** Watch how the neural network learns to mimic your tea's cooling over time.
- **Comparison:** Clearly compare PINN predictions to the exact analytical solution.

## ⚙️ Getting Started on Google Colab
1. Open the notebook directly on [Google Colab](https://colab.research.google.com/).
2. Run the cells sequentially.
3. Enjoy the visualizations of your tea’s cooling process!

## 🐞 Found Something Interesting?
Feel free to open an issue or submit a pull request. Collaboration is warmly welcomed!

## 🌟 Happy Cooling!
Enjoy discovering the harmony between artificial intelligence and everyday physics. May your tea always be just the right temperature. 🍃🍵✨
