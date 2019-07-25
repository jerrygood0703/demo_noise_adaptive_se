# Introduction

This is the demo page of the experiments in [Noise Adaptive Speech Enhancement using Domain Adversarial Training](https://arxiv.org/abs/1807.07501).

In the paper we trained a set of models to adapt to the BabyCry noise, here we also show another set of models that are adapted to the cafeteria noise.

## Cafeteria noise

 &nbsp; &nbsp; &nbsp; Noisy &nbsp; &nbsp; &nbsp; &nbsp; BLSTM-L(Baseline) &nbsp; &nbsp; &nbsp; &nbsp; BLSTM-60 &nbsp; &nbsp; &nbsp; &nbsp; BLSTM-220 &nbsp; &nbsp; &nbsp; &nbsp; BLSTM-U(Upperbound)

<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/noisy/FDHC0_SI929.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/base/FDHC0_SI929.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/60/FDHC0_SI929.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/220/FDHC0_SI929.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/upper/FDHC0_SI929.wav" type="audio/wav" />
</audio>



