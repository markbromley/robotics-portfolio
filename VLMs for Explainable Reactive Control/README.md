<h1>VLMs for Explainable Reactive Control of Mobile Robots</h1>

<table width="100%">
  <tr>
    <td width="60%" valign="top">

<p><strong>Vision-Language Model (VLM)-based reactive navigation system deployed on TurtleBot 3.</strong></p>
<p>Tested in simulation and transferred to real hardware.</p>

<h3>System Overview</h3>

<p>
Reactive vision-language navigation system deployed on TurtleBot3 (sim → real).
</p>

<p>
Given a natural language instruction and a single RGB camera frame, the VLM selects an action from a motion primitive library at each timestep. Primitives execute via closed-loop velocity control using odometry feedback, and the loop repeats with the updated visual state.
</p>

<p><strong>Key Features:</strong></p>
<ul>
  <li>Fully reactive (single-frame visual input + conversation history)</li>
  <li>Closed-loop control with discrete motion primitives</li>
  <li>Robust to odometry noise and action imprecision</li>
  <li>Identical architecture in simulation and real-world deployment</li>
  <li>Logs trajectories, images, and model dialogue for evaluation</li>
  <li>Minimises sim-to-real transfer gap via consistent system design</li>
</ul>
<h3>System Architecture</h3>

<p>A systems-level schematic representation of the experimental setup and interface integration:</p>
  <img src="media/system-architecture.png">
  <br />
  <br />
  <p><i>(videos shown at 10x speed)</i></p>
    </td>
    <td width="40%" valign="top" align="center">

<p><strong>Simulation</strong></p>
  <video src="https://github.com/user-attachments/assets/097051df-f059-4c3d-b18a-9c79dcfea41c"></video>
<br/><br/>

<p><strong>Real Robot</strong></p>
  <video src="https://github.com/user-attachments/assets/67e36325-70ea-49c7-bf68-b36b1c3fee37"></video>
    </td>
  </tr>
</table>
<p><a href="../">← Main Page</a></p>
<p>Copyright (c) 2026 Mark Bromley</p>
<p>All Rights Reserved.</p>
