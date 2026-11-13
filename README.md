# Morphogenesis

How do spatial patterns and bodies develop, maintain form and regenerate? Chemical pattern formation, computational constructions and biological interventions provide different kinds of evidence.

## Physical form and positional information

- **Physical and geometric form** - Connects organismal form to scale, growth and physical forces. Coordinate transformations compare related shapes; these geometric correspondences describe variation without identifying the developmental process that produced it. [Thompson 1917](<https://www.gutenberg.org/ebooks/55264> "On Growth and Form; Cambridge University Press (book)").
- **Positional information** - Cells interpret position relative to reference points using their genome and developmental history. Reaction-diffusion can generate signals that this interpretation uses; signal formation and positional interpretation can act together. [Wolpert 1969](<https://doi.org/10.1016/S0022-5193(69)80016-0> "Positional information and the spatial pattern of cellular differentiation; J. Theor. Biol."), [Green and Sharpe 2015](<https://doi.org/10.1242/dev.114991> "Positional information and reaction-diffusion: two big ideas in developmental biology combine; Development").
- **Mechanical reporters** - In fly embryos, genetic and optogenetic perturbations separate effects of head-cell division and tissue flows on cephalic-furrow motion. The fold reports surrounding mechanics, but displacement combines force, tissue stiffness and geometry. [Xu et al. 2026](<https://www.biorxiv.org/content/10.64898/2026.11.08.765212v1> "Endogenous Mechanical Reporters Encode the Global Mechanical Landscape of Morphogenesis; bioRxiv").

## Molecular assembly

- **Vault assembly** - Expressing rat major vault protein in insect cells produces barrel-shaped particles without supplying other vault proteins or vault RNA. Electron microscopy also reveals distorted caps and assemblies containing several half-shells. [Stephen et al. 2001](<https://doi.org/10.1074/jbc.C100226200> "Assembly of Vault-like Particles in Insect Cells Expressing Only the Major Vault Protein; J. Biol. Chem.").
    - **Vault nanocapsules** - A phage-derived protein expressed in E. coli assembles into 96-copy shells. Duplicating two wall repeats increases enclosed volume by about 20%. Single changes at subunit contacts can prevent closure. Native biological function remains unknown. [Athukoralage et al. 2026](<https://www-cdn.anthropic.com/76e55fbe85697afbaae16b839498dc00797dec30.pdf> "Prokaryotic homologs of the major vault protein form engineerable vault nanocapsules; preprint").

## Chemical pattern formation

- **Turing patterns** - Reaction and diffusion can destabilize a homogeneous chemical state and amplify small disturbances into spatial patterns. A mechanism for symmetry breaking, analyzed in idealized tissues. [Turing 1952](<https://doi.org/10.1098/rstb.1952.0012> "The Chemical Basis of Morphogenesis; Phil. Trans. R. Soc. B").
- **Belousov-Zhabotinsky waves** - Breaking a chemical wavefront creates rotating spiral waves in Winfree's experiments. Persistent wave sources organize reaction activity; visible form results from an excitable chemical medium. [Winfree 1972](<https://doi.org/10.1126/science.175.4022.634> "Spiral Waves of Chemical Activity; Science").
- **Gray-Scott patterns** - Numerical reaction-diffusion experiments produce spots that grow and divide, and overcrowded regions that collapse. The reported patterns arise from finite-amplitude perturbations. [Pearson 1993](<https://doi.org/10.1126/science.261.5118.189> "Complex Patterns in a Simple System; Science").
- **Angelfish stripe dynamics** - Stripes rearrange as marine angelfish grow, unlike a fixed pattern stretched with the skin. Reaction-diffusion simulations predict later arrangements, supporting a dynamic patterning mechanism without identifying its molecular components. [Kondo and Asai 1995](<https://doi.org/10.1038/376765a0> "A reaction–diffusion wave on the skin of the marine angelfish Pomacanthus; Nature").

## Growth and repair

- **L-systems** - Parallel rewriting rules model cell division and branching growth. Symbols encode developmental states; geometric interpretation turns their expansion into plant forms. The rules specify a developmental model, not just a final shape. [Lindenmayer 1968](<https://doi.org/10.1016/0022-5193(68)90079-9> "Mathematical models for cellular interactions in development I. Filaments with one-sided inputs; J. Theor. Biol."), [Prusinkiewicz and Lindenmayer 1990](<https://algorithmicbotany.org/papers/abop/abop.pdf> "The Algorithmic Beauty of Plants; Springer (book)").
- **Bioelectric pattern memory** - Briefly perturbing gap-junction signaling changes later planarian regeneration, including in normal-looking worms amputated again in water. Manipulating resting potential can reset the altered head-pattern outcome. [Durant et al. 2017](<https://pmc.ncbi.nlm.nih.gov/articles/PMC5443973/> "Long-Term, Stochastic Editing of Regenerative Anatomy via Targeting Endogenous Bioelectric Gradients; Biophys. J.").
- **synNotch morphogenesis** - Engineered contact signals change cell adhesion, which rearranges neighbors and alters later signals. Mouse fibroblasts form layered or asymmetric assemblies, and cut layered structures regenerate their organization. [Toda et al. 2018](<https://pmc.ncbi.nlm.nih.gov/articles/PMC6492944/> "Programming self-organizing multicellular structures with synthetic cell-cell signaling; Science").
- **Body-axis reconstruction** - Reassembled sea-anemone embryonic cells can rebuild whole polyps. Blocking Notch disrupts cell sorting and oral structures. Wnt-expressing cells restore axis formation in deficient aggregates only when Notch remains active. [Kirillova et al. 2018](<https://pmc.ncbi.nlm.nih.gov/articles/PMC5828576/> "Germ-layer commitment and axis formation in sea anemone embryonic cell aggregates; PNAS"), [Narayanaswamy et al. 2026](<https://www.nature.com/articles/s41467-026-74441-x> "Notch coordinates self-organization of germ layers and axial polarity in sea anemone gastruloids; Nature Communications").
- **Growing neural cellular automata** - Train a shared local neural rule to grow a target image. Reusing intermediate states improves persistence; exposing the model to damage strengthens repair. Local execution follows global optimization through time. [Mordvintsev et al. 2020](<https://distill.pub/2020/growing-ca/> "Growing Neural Cellular Automata; Distill"); [code](<https://github.com/google-research/self-organising-systems>), [demo](<https://colab.research.google.com/github/google-research/self-organising-systems/blob/master/notebooks/growing_ca.ipynb>).
- **CEMA (cross-embryo morphogenetic assistance)** - Grouped frog embryos survive developmental disruptors better at matched per-embryo exposure. Barriers and P2-receptor blockade weaken protection. A cellular-automaton model reproduces group-size dependence through local coupling. [Tung et al. 2024](<https://www.nature.com/articles/s41467-023-44522-2> "Embryos assist morphogenesis of others through calcium and ATP signaling mechanisms in collective teratogen resistance; Nature Communications").
    - **Topoiesis** - The same group's model makes signal diffusion, decay and boundary loss explicit. Fitted to the earlier embryo data, it predicts protected interiors and rescue by sealing boundaries at fixed group size. [Manicka and Levin 2026](<https://www.biorxiv.org/content/10.64898/2026.11.03.763900v1> "A topoietic model of collective morphogenesis and compartmentalization; bioRxiv").

## Conclusions

Body form emerges from feedback between signaling, cell arrangement and mechanics. Changes in arrangement alter which signals and forces reach each cell, while persistent physiological states influence what regenerates after injury. This makes a tissue's organization and history part of the mechanism, alongside its molecular components. The experimental interventions establish several ways to redirect development and repair; models that reproduce a shape or group-size trend still need tests that distinguish their proposed mechanism from alternatives.

## Open questions

- Which perturbations distinguish changes in a spatial signal from changes in how cells interpret that signal?
- Which repair mechanisms generalize beyond damage encountered during development, selection or training?
- Which persistent cellular states determine regenerated form, and how do targeted perturbations change the outcome?

## Related topics

- [Hyperorganism](https://hyperorganism.github.io/)
- [Distributed construction](https://hyperorganism.github.io/collective-life/#coordination-and-construction) - Robot assembly makes supplied target shapes and coordinate references explicit.
- [Digital organisms](https://hyperorganism.github.io/digital-life/#digital-organisms-and-ecologies) - Persistent computational patterns also support questions about individuality and evolution.
- [Developmental rules and accessible forms](https://hyperorganism.github.io/digital-life/#developmental-rules-and-accessible-forms) - Rule-space evolution explores which forms selection can reach; the Ruliobiology patterns record one-dimensional states over time.
- [Viability](https://hyperorganism.github.io/viability/#renewal-and-rejuvenation) - Planarian regeneration can reverse age-related loss of function, including fertility. Maintaining stem cells alone does not preserve reproductive organization.
- [Capacities and behavioral organization](https://hyperorganism.github.io/basal-cognition/#capacities-and-behavioral-organization) - Bioelectric resets change future regeneration. Tests of learning or goal adjustment must distinguish those interpretations from the physiological control already demonstrated.
- [Process-based art](https://hyperorganism.github.io/systems-aesthetics/#process-environment-and-interaction) - Patterns can be artistic material as well as scientific observations.
- [Active tissue mechanics](https://hyperorganism.github.io/active-matter/#physical-foundations-and-collective-motion) - Alignment defects link stresses to cell removal in epithelial sheets.
