# Introduction

This is the demo page of the expiriments in [Noise Adaptive Speech Enhancement using Domain Adversarial Training](https://arxiv.org/abs/1807.07501).

In the paper we trained a set of models to adapt to the BabyCry noise, here we also show another set of models that are adapted to the cafeteria noise.

## Cafeteria noise

<audio style="width:200px" controls="controls">
	<source src="wavs/cafe/noisy/FDHC0_SI929.wav" type="audio/wav" />
</audio>
<audio style="width:200px" controls="controls">
	<source src="wavs/cafe/base/FDHC0_SI929.wav" type="audio/wav" />
</audio>
<audio style="width:200px" controls="controls">
	<source src="wavs/cafe/60/FDHC0_SI929.wav" type="audio/wav" />
</audio>
<audio style="width:200px" controls="controls">
	<source src="wavs/cafe/220/FDHC0_SI929.wav" type="audio/wav" />
</audio>
<audio style="width:200px" controls="controls">
	<source src="wavs/cafe/upper/FDHC0_SI929.wav" type="audio/wav" />
</audio>

Noisy BLSTM-L(Baseline) BLSTM-60 BLSTM-220 BLSTM-U(Upperbound)
