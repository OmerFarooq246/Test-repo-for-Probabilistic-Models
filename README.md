# Test-repo-for-Probabilistic-Models
A test notebook where i test probabilistic changes and validate results before actually implementing it to the dental implants project.

<h3>Making a Probabilistic version of ResNet50V2</h3>
<p>The goal is to convert deterministic conv layers in the last 50 layers of ResNet50V2 to their probabilistic version. Following are the steps:</p>
<ol>
  <li>Identifying conv layers in last 3 blocks: 13 Conv2D layers identified.</li>
  <li>Making 13 Convolution2DFlipout layers, each having the same no. of filters and filter size as their corresponding Conv2D layers.</li>
  <li>Replacing the Conv2D layers with their probabilistic versions.</li>
  <li>Reestablishing layers' connections to maintain the original model architecture.</li>
</ol>
<p>Details of each step are shown separately in the notebook.</p>
