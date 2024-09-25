# What Could an Artificial Intelligence Theater Be?

Read [this essay in Cantonese](https://artismonline.hk/issues/2023-06/574) at [Artism](https://artismonline.hk)

While my current research is concerned with artificial intelligence, my background is in experimental music theater. Surprisingly, this kind of trajectory, from theater to computation, or at least from performance art to computer art, is somewhat common, and a number of my academic mentors and peers have lived versions of it. In this brief post, I explore some of the intersections of theater and computation in general, and theater and machine learning in particular that I suggest enable this trajectory. Based on this exploration, I present some speculative thoughts on potential future developments at the interface of theater and machine learning.

There is a long history of optical media use in theater, starting in the early 17th century with Nicola Sabbatini's mechanisms.[^1] Film projections were used in theater as early as the 1920s, in the theater of Erwin Piscator. Now, the increased availability of cheap computing power and both sophisticated and robust hardware and software tools (Kinects and other depth sensors, Max/MSP, etc.) have established digital workflows in many areas of theatrical production. Digital video projectors are now common theatrical devices, projecting digitally rendered video or computer graphics, and computers control lighting and sound. Among other things, this development has drawn theater and performance art -- which has embraced digital tools much earlier, as it has always intersected with media art -- closer together, although institutionally they remain worlds apart.

I argue, however, that there exists a more abstract, more powerful commonality between theater and computation than the utilization of the latter within the former. This commonality is a focus on *discrete state transformations*.

Computers, at their Turing core, are discrete state machines, i.e. all Turing-complete computers can be sufficiently described by a set of possible discrete states and transition rules.[^2] Importantly, these states are, in the last instance, physical states: configurations of electric charges in the vast integrated circuitry of the hyperobject[^3] that is the computer. "There is no software", as Friedrich Kittler famously states.[^4] Computer are thus fluid, ever-changing objects, jumping from one state to the other, with countless repetitions, loops, and variations.

We find the same kind of objects in theater. We could even say that we find *only* the same kind of objects in theater: on stage, objects are never static, never resting, always recontextualized with the flow of time. They change when the lighting changes, when the scene changes, when they are picked up or put down. They even change under the gaze of the audience. After all, in the theater, the spectator has the freedom to let their gaze flow freely and focus only on parts of the image that is constructed before them. More importantly however, all of these states are *discrete* because they are *composed*. The mis-en-scene establishes a set of theatrical states and transition rules that include each and every thing on stage.

Bertold Brecht has famously proposed to make this discrete nature of theater visible -- to exhibit the artificiality of state changes, and even make them more explicit by means of a "Verfremdungseffekt". Today, the discrete nature of theater is lucidly explored in the contemporary works of Robert Wilson or Heiner Goebbels (both of which are, of course, building upon Brechtian principles). The focus on discrete state transformations is even more obvious in dance, where the set of theatrical states is often clearly defined as the set of states of a number of human bodies in all of its permutations.

<figure class="figure my-4">
  <img src="https://static1.squarespace.com/static/52797371e4b0f7d3b5b349c7/527bf87de4b004b622ba068c/527bf883e4b04a4b5511bb08/1426551461999/6993390241_08f3c4ab8a_b.jpg" class="figure-img img-fluid" alt="...">
  <figcaption class="figure-caption">Robert Wilson's <i>Einstein on the Beach</i> in a 2012 production. The discrete nature of theater is perhaps nowhere as visible as in Wilson's works, where the composition of theatrical elements is made explicit by an intentionally slowed-down time.</figcaption>
</figure>

There is, however, a big problem with this hypothesis: it ignores one of the main features of theater, the singularity of the performance. It is exactly the fact that performances can not be repeated that makes the medium of theater unique. Performances can not be repeated because theatrical states are often not clearly defined, or even left open completely: things are allowed to happen, consequences are allowed to unfold beyond the direct control of the director or the performers.

In other words, some theatrical states (or: some more than others) are *probabilistic* states: they contain nothing but a probability distribution of things that *could* happen. These probabilistic states are almost always manufactured by introducing some outside, real-life element to the theater space: from improvised lines over audience participation to live video from outside the theater space.

<figure class="figure my-4">
  <img src="https://www.heinergoebbels.com/db/img/std/p100/769_ariette-armella-foto-ruhr-triennale-europeras1-7.jpg" class="figure-img img-fluid" alt="...">
  <figcaption class="figure-caption">John Cage, <i>Europeras I + II</i>, by Heiner Goebbels, is a "classic" demonstration of probabilistic theatrical states: the order of scenes, and the set of theatrical elements in each scene, is defined by a random process.</figcaption>
</figure>

In other words, probabilistic theatrical states connect the "black box" of the performance to the outside world, and let outside influences reign, for the limited duration of that state. It is again Brecht that has proposed this "outside eye" emerging naturally from the medium of theater as a designated effect, a tool of composition. One of the aesthetic functions of theater is to construct a bi-directional relation between the model reality in the black box and the real reality outside of it. If, with Adorno, art is the social antithesis to society,[^5] i.e. if art oscillates between being part of the world and being outside of it, probabilistic theatrical states are exactly an implementation of this function.

This is where an intersection of theater and machine learning emerges: after all, machine learning deals exactly with the problem of extracting probability distributions from idiosyncratic real world data outside of the "black box" that the machine learning system itself provides. Both theater and machine learning are thus integrating real-life probability distributions into a highly artificial, "black boxed" assemblage[^6] of states and transition rules for the sake of *making sense* of these real-life probability distributions. In other words: what theater and machine learning have in common is the setting up of an elaborate, controlled apparatus for making sense of everything that is outside of this apparatus: real life in the case of theater, real life *data* in the case of machine learning.

<figure class="figure my-4">
  <img src="/md/blog/img/anth3.jpg" class="figure-img img-fluid" alt="...">
  <figcaption class="figure-caption"><i>Anthroposcene</i>, an experimental music theater performance by Laurent Durupt, Jan Rohwedder, and myself. Using a custom machine learning system, debris on stage is transformed into imaginary satellite images that slowly transform into real video images of a weather balloon floating into the night sky outside.</figcaption>
</figure>

Importantly, I posit that this commonality can do more than validate the personal trajectories mentioned above: it can inform a "future artificial intelligence theater". An artificial intelligence theater would be a theater that not only uses machine learning for visual effect or to defend its own relevance in the face of hypercapitalism, but a theater that realizes this commonality by employing machine learning in a non-trivial way, in its function as a sense-making tool.

I have proposed in a previous post that the idea of Verfremdungseffekt can be used productively to think about the latent spaces created by generative adversarial networks (GANs). In the best case, an artificial intelligence theater would also be a Brechtian artificial intelligence theater that not only employs, but exhibits the artificiality of machine learning systems, and the process of making sense of the world *outside* of the black box with the apparatus *inside* of the black box.

---

[^1]: Nicola Sabbatini, *Pratica Di Fabricar Scene E Machine Ne' Teatri*, 1638.
[^2]: Alan Mathison Turing, "On Computable Numbers, with an Application to the Entscheidungsproblem," *Proceedings of the London Mathematical Society* 2, no. 1 (1936): 230--65; John E. Hopcroft and Jeffrey D. Ullman, *Introduction to Automata Theory, Languages, and Computation* (Boston, MA: Addison-Wesley, 1979).
[^3]: Timothy Morton's concept of "hyperobjects" in comes in handy here in its exact overlap with the computer science concept of "hyperobjects" as n-dimensional, non-local objects: the exact kind of object that machine learning systems represent. Timothy Morton, *Hyperobjects: Philosophy and Ecology After the End of the World* (University of Minnesota Press, 2013).
[^4]: Friedrich A. Kittler, "Es Gibt Keine Software," in *Die Wahrheit Der Technischen Welt. Essays Zur Genealogie Der Gegenwart*, ed. Hans Ulrich Gumbrecht (Suhrkamp, 2013).
[^5]:Theodor W. Adorno, "Ästhetische Theorie," in *Gesammelte Schriften*, ed. Rolf Tiedemann, vol. 7 (Suhrkamp, 2003).
[^6]: Manuel DeLanda, *Assemblage Theory* (Edinburgh University Press, 2016).