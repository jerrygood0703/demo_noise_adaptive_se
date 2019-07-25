# Introduction

This is the demo page of the experiments in [Noise Adaptive Speech Enhancement using Domain Adversarial Training](https://arxiv.org/abs/1807.07501).

In the paper we trained a set of models to adapt to the BabyCry noise, here we also show another set of models that are adapted to the cafeteria noise.

From left to right are: 
1. Noisy 2. BLSTM-L(Baseline) 3. BLSTM-60 4. BLSTM-220 5. BLSTM-U(Upperbound)


## Cafeteria noise

###### FDHC0_SI929
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

###### MBPM0_SI1584
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/noisy/MBPM0_SI1584.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/base/MBPM0_SI1584.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/60/MBPM0_SI1584.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/220/MBPM0_SI1584.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/cafe/upper/MBPM0_SI1584.wav" type="audio/wav" />
</audio>
