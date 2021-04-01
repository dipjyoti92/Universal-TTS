# Universal-TTS

Towards a Universal Multi-Speaker Multi-Style Text-to-Speech via Disentangled Representation Learning


Dipjyoti Paul<sup>a</sup>, Sankar Mukherjee<sup>b</sup>,  Yannis Pantazis<sup>c</sup> and Yannis Stylianou<sup>a</sup>

<sup>a</sup>Computer Science Department, University of Crete

<sup>c</sup>Istituto Italiano di Tecnologia, Italy

<sup>c</sup>Inst. of Applied and Computational Mathematics, Foundation for Research and Technology - Hellas

### Abstract:

The objective of multi-speaker multi-style Text-to-Speech (TTS) synthesis is to generate speech from text with speaker characteristics and speaking style similar to a given reference signal. In this paper, we implement such a universal system, referred hereafter as Universal TTS (UTTS). UTTS learns from non-parallel data and generates voices in an unsupervised manner, i.e., neither style annotation nor speaker label are required. Conventional training of the model leads to two major issues: leaking content information into the style embeddings (referred to as "content leakage") and leaking speaker information into style embeddings (referred to as "style leakage"). To overcome those limitations, we suggest a novel Renyi Divergence based Disentangled Representation framework through adversarial learning. Similar to mutual information minimization, the proposed approach explicitly estimates via a variational formula and then minimizes the Renyi divergence between the joint distribution and the product of marginals for content-style and style-speaker pairs. By doing so, content, style and speaker spaces become representative and (ideally) independent of each other. Our proposed system greatly reduces content leakage by improving the word-error-rate by approximately 17-19% relative to the baseline system. In MOS-speech-quality, the proposed algorithm achieves an improvement of about 16-20% whereas MOS-style-similarly boost up 15% relative performance.

# Audio Samples:
Audio samples can be found in [here.](https://www.csd.uoc.gr/~dipjyotipaul/Universal-TTS-IS21)


# Scripts:

Code will be coming soon!!
