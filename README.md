# Strabo.io
A greeklish to greek translation keyboard for Android

## Authors
[Fotios Bistas](https://github.com/FotiosBistas "Fotios Bistas"), [Georgios E. Syros](https://github.com/gsiros "Georgios E. Syros"), [Anastasios Toumazatos](https://github.com/toumazatos "Anastasios Toumazatos")

## Background
Strabo.io is a custom Android software keyboard that leverages advances Machine Learning techniques to translate from Greeklish[^1] text to Greek in real time as the user types. Its core functionality revolves around the translation model. Training data is collected and sent anonymously and encrypted to a central server where model retraining occurs. If a model is produced with better loss than the current, it gets distributed upon client request to the end nodes.

<p align="center">
  <img src="https://github.com/gsiros/Strabo.io/assets/47118034/bae7a4a9-33b1-45c1-b18f-3ca2c4164104" width="300" height="220">
</p>

<p align="center">
  <i><b>Figure 1</b>. Keyboard nodes send training data to the server.</i>
</p>

<p align="center">
  <img src="https://github.com/gsiros/Strabo.io/assets/47118034/966c3547-d372-44c6-b35f-f5600fcbea68" width="300" height="220">
</p>

<p align="center">
  <i><b>Figure 2</b>. The server distributes the new model.</i>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/47118034/231530358-0c451796-5b1e-4252-8105-d669da5a69c3.gif" alt="Brief demo of the prototype" width="300" height="650">
</p>

<p align="center">
  <i><b>Screenshot 1</b>. Keyboard translation demo.</i>
</p>

<p align="center">
<img src="https://github.com/gsiros/Strabo.io/assets/47118034/6c888810-8bdf-479d-a244-46bd51e84e79"  width="300" height="650">
</p>

<p align="center">
  <i><b>Screenshot 2</b>. Keyboard settings.</i>
</p>

<p align="center">
<img src="https://github.com/gsiros/Strabo.io/assets/47118034/633242fd-d714-4ad0-b759-ca2c95319ca5"  width="300" height="650">
</p>

<p align="center">
  <i><b>Screenshot 3</b>. New model popup.</i>
</p>

<p align="center">
<img src="https://github.com/gsiros/Strabo.io/assets/47118034/4e163484-3072-431a-b27c-7fe5ff7dd7ec"  width="300" height="650">
</p>

<p align="center">
  <i><b>Screenshot 4</b>. Model downloading.</i>
</p>

[^1]: https://en.wikipedia.org/wiki/Greeklish
