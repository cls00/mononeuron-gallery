# Tensorial Mononeuron — results gallery

Interactive showcase for the **Tensorial Mononeuron** — an architecture with a single
interaction site (one neuron). Its inputs are signal flows; the site combines them in
one tensor contraction, which forms products across flows, instead of weighted sums.
Self-loop wires carry signals back to the input at later steps — earlier inputs, past
outputs, or a loop's own internal state.

**Live site: [cls00.github.io/mononeuron-gallery](https://cls00.github.io/mononeuron-gallery/)**

Each task is presented as a gallery of specimens — one single-interaction-site
controller per card. A card shows a still poster and plays an animated replay on
hover (desktop) or tap (mobile). Where a controller came from a search, the page
opens on a progression — representative stages from the untrained site to the
solved result — with a toggle to all the saved checkpoints, sortable by metric.

## Tasks

- **Cart-pole swing-up** — one site swings a pole up from hanging and holds it
  balanced, within the rail.
- **Double pendulum** — a cart-actuated double inverted pendulum swung up, caught,
  and held with a single horizontal force.
- **Bouncing ball (video → video)** — one site predicts a ball bouncing in a box
  from pixels alone; the gallery covers the behaviours that emerge over training,
  from early collapse through to tracking the bounce, including the failure modes.
- **Conditional MNIST generation** — one site generates the ten digits by iterating
  the image as its own recurrent state (a self-loop): the training progression, each
  digit forming from noise, morphs between digits, and a scratch-and-regenerate
  robustness demo.
