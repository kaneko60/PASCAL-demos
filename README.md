# PASCAL-demos

Demo clips for the PASCAL paper.

The ANC task using the stereo neckband array setup is simulated. A monopole noise source is placed at position (x,y,z) = (2m,1m,0) in the Cartesian coordinates, where the origin of the coordinate is the center of the listener's head and the listener is looking towards the positive direction of the y-axis. The transfer functions from the source to the ears and microphones were computed for frequencies up to 8kHz with frequency step of 62.5Hz. The ANC filters were computed as described in the paper. The binaural noise and binaural signal were synthesized by frequency-domain convolution of the impulse responses (from the noise source and signal source to the ear positions) with the monaural noise clip and monaural signal clip, respectively. The sound files with "beforeANC" in their file names are the superposition of the binaural noise and binaural signal. It is assumed that the binaural signal which the system is presenting to the listener and the transfer functions from the neckband loudspeakers to the ears/microphones is known to the ANC system and hence perfect separation of the noise from the recorded signal is possible. The sound files with "afterANC" in their file names are the superposition of the binaural noise suppressed by the ANC algorithm, superposed with the binaural signal.

0-1_noise0_raw.wav ... monaural sound clip used to synthesize the binaural noise  
0-2_signal0_raw.wav ... monaural sound clip used to synthesize the binaural signal  
0-3_noise0_with_signal0_beforeANC.wav ... binaural noise superposed with the binaural signal  
0-4_noise0_with_signal0_afterANC.wav ... binaural noise after ANC superposed with the binaural signal  


The following files are for different noise/signal sound materials. The same naming convention applies.

1-1_noise1_raw.wav  
1-2_signal1_raw.wav  
1-3_noise1_with_signal1_beforeANC.wav  
1-4_noise1_with_signal1_afterANC.wav  

2-1_noise2_raw.wav  
2-2_signal2_raw.wav  
2-3_noise2_with_signal2_beforeANC.wav  
2-4_noise2_with_signal2_afterANC.wav  

3-1_noise3_raw.wav  
3-2_signal3_raw.wav  
3-3_noise3_with_signal3_beforeANC.wav  
3-4_noise3_with_signal3_afterANC.wav

4-1_noise4_raw.wav  
4-2_signal4_raw.wav  
4-3_noise4_with_signal4_beforeANC.wav  
4-4_noise4_with_signal4_afterANC.wav
