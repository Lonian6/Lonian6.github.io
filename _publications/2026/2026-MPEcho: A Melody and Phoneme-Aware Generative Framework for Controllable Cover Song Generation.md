---
title:          "MPEcho: A Melody and Phoneme-Aware Generative Framework for Controllable Cover Song Generation"
date:           2026-07-10
selected:       true
pub:            "International Society for Music Information Retrieval"
pub_ab:         "ISMIR"
pub_date:       "2026"
abstract: >-
    Cover song generation (CSG) should preserve the melodic and linguistic content of a reference song while recreating the remaining musical components. The state-of-the-art model SongEcho utilizes F0 sequences and voiced/unvoiced (V/UV) tags for conditioning; however, implicit linguistic information from V/UV tags cannot guarantee lyric accuracy, leading to a high phoneme error rate (PER). Inspired by singing voice synthesis (SVS), we propose MPEcho, which integrates a phoneme encoder and a length regulator (LR) into the SongEcho framework. By providing explicit phoneme-level conditioning and precise temporal boundaries, MPEcho significantly reduces PER. To enable this, we developed Phonsa, a Whisper-based automatic transcription model that provides high precision phoneme-level annotations for singing voices, overcoming the scarcity of high-quality audio-phoneme pairs. Experimental results validate the effectiveness of Phonsa for alignment and MPEcho for end-to-end CSG.
# cover: /assets/images/covers/cover_2026_Training-Efficient Text-to-Music Generation with State-Space Modeling.png
authors:
- Wei-Jaw Lee
- Hsuan-Yu Yeh
- Ting-Yi Hu
- Chih-Pin Tan
- Fang-Duo Tsai
- Yi-Hsuan Yang

links:
    Web: https://lonian6.github.io/MPEcho.github.io/
    Paper: https://arxiv.org/abs/2607.26698
    Code: https://github.com/YatingMusic/MPEcho
---