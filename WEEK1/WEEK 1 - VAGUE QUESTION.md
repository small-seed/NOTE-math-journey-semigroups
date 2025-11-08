# FIRST NOTE:

**Dzung** **Lai** **- Kuopio** **-** **Day** **8/11/2025**: I read about the ODE solution in three-body problem topic, it is said that there was no general closed-form (analytical) solution for the full system of ordinary differential equations (ODEs) describing the motion of three bodies under mutual gravitational attraction?

**So,** **the** **question**: I'm wondering if it's something like an analog of an irrational nummber. When you apply addition twice to a number $x$ , that's equivalented to multiplying by 2. But what does it mean to “add" 2.5 times? Or even $\sqrt {2}$ or $\{\sqrt {2}\}+i$ times? It would seem to require adding an infinite number of fractional parts of the operation-an idea that contradicts the usual definition, since addition is defined as a finite repetition of increments (while multiplication generalizes that to a discrete, countable number of additions).

Similarly, when solving certain ODEs, you can't always find a closed-form function as a solution-instead, the result often becomes an infinite series of functions. The problem can be understood like turning discrete updates into a smooth, continuous transformation a $\text {"}t\text {"}$ number of times, where t can be real/ imaginary number:

$$x_{n}=F^{t}\left(x_{n-1}\right)$$

where "t" is continuous number of times, rather than discrete number.

**After** **studying,** I found that several well-developed theories have handled this question in different fields of mathematics such as continuous (or fractional, or complex) iteration, with backbone are semi groups and flows:

$$T_{t}=e^{tA}\quad T_{s+t}=T_{s}T_{t}$$

· A is a generator (a derivative, Hamiltonian,Laplacian,etc.) describing the local rule,

· t is how long you apply to be an operator.

· $T_{t}$ is the operator that tells you what happens after that timne,

· the semigroup property $T_{t+s}=T_{t}T_{s}$ is the continuous version of "do it again." But could it take another form?

It is not new, but my institution is: arithmetic, calculus, ODEs, quantum mechanics-they're all different expressions of the same structure: $"A$ rule being applied continuously rather than discretely" and can be written in the same algebraic form as above.


<table>
<tr><th>t Value</th><th>What It Represents</th><th>Type of Physics</th><th>Example</th></tr>
<tr><td>Integer</td><td>Repeated discrete operation</td><td>Arithmetic / Iteration</td><td>Add: xₙ=3×x+3 → semigroup T³(x)=x+3c</td></tr>
<tr><td>Real</td><td>Smooth continuous time</td><td>Classical motion</td><td>ODE: dx/dt=f(x)</td></tr>
<tr><td>Fractional</td><td>Memory, anomalous diffusion</td><td>Fractional dynamics</td><td>a=1.5 → slower chaos</td></tr>
<tr><td>Imaginary</td><td>Oscillation, rotation</td><td>Quantum / wave</td><td>i∂ψ/∂t=Hψ → phase shift</td></tr>
</table>


$here=fractiona$ l order, blending t with memory (e.g., Caputo derivative). Unifies: $a=2$ classical (acceleration), $a=1QM$ (probability).

From biological algorithms perspective, particularly those embedded in the nervous system, I began to realize that the accuracy of human intuition about reality depends not only on our biological hardware, but also on the way we process sensory signals. For example, octopuses possess only a single type of photoreceptor yet can still distinguish colors through the chromatic aberration effect, while humans have multiple photoreceptor types and rely on a different processing strategy. Since there is no guarantee that the octopus's perceptual algorithm is objectively "correct," the same uncertainty applies to human perception. This suggests that our physical understanding of the world may be less certain than we assume. My intuition now is that the concept of continuous flows might hold a clue to how we should more fundamentally describe physical systems. I am keeping these notes as a record of this idea and will continue updating them as I explore this question further

License:https://creativecommons.org/licenses/by/4.0/

