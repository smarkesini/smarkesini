## Stefano Marchesini

I work on computational imaging with X-rays: the algorithms and instruments that turn
diffraction measurements into pictures. I developed Shrinkwrap (2003), a phase-retrieval
method that reconstructs an image from a diffraction pattern alone, with no prior knowledge
of the object, used for the first images recorded at a soft X-ray free-electron laser. I
introduced massively parallel X-ray holography (*Nature Photonics*, 2008) and led the
ptychographic microscopy work at the Advanced Light Source that reached 3 nm resolution.
Fellow of Optica (2023). At LCLS I work on real-time data reduction and indexing for serial
femtosecond crystallography.

SLAC National Accelerator Laboratory, LCLS · [ORCID 0000-0002-6798-2913](https://orcid.org/0000-0002-6798-2913)

### GLINT

Blind GPU indexing for serial crystallography: candidate lattices per frame, the unit cell
derived *across* frames by consensus, then every frame registered against it. On one A100 over
480 sparse lysozyme frames it matches the strongest blind indexer tested (361 frames against
xgandalf's 350) at about 450× the throughput, and it discovers the cell rather than being
handed it.

→ [slac-lcls/glint](https://github.com/slac-lcls/glint) · [arXiv:2609.07722](https://arxiv.org/abs/2609.07722)

### Earlier work

- **Shrinkwrap**: *Phys. Rev. B* 68, 140101(R) (2003).
- **Iterative projection algorithms for phase retrieval**: *Rev. Sci. Instrum.* 78, 011301 (2007).
- **Massively parallel X-ray holography**: *Nature Photonics* 2, 560 (2008).
- **SHARP**, a distributed GPU ptychographic solver: *J. Appl. Cryst.* 49, 1245 (2016).

Most other repositories here are forks of instrument and analysis code I use at LCLS.
