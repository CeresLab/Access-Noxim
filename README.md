# command 
#./noxim -dimx 8 -dimy 8 -dimz 4 -traffic random -pir 0.025 possion -routing xyz -sim 100000 -warmup 10000 -seed 0 -clean 5000 -#throt vertical -buffer 8 -size 8 8 -tquota 1 -predict 0 -tsh 98.0 -tla 1 -sen_alloc table ./doc/random_placement.txt -#temp_recover regression ./doc/random_linear_coef.txt ./doc/random_linear_coef1.txt ./doc/random_linear_ref.txt

./noxim -dimx 8 -dimy 8 -dimz 4 -traffic bitreversal -pir 0.025 possion -routing xyz -sim 10000000 -warmup 10000 -seed 0 -throt vertical -buffer 8 -size 8 8 -tquota 0
./noxim -dimx 8 -dimy 8 -dimz 4 -traffic butterfly -pir 0.025 possion -routing xyz -sim 10000000 -warmup 10000 -seed 0 -throt vertical -buffer 8 -size 8 8 -tquota 0
#-tquota 1
#-predict 0
#-tsh 98.0
#-tla 1
#-sen_alloc table ./doc/random_placement.txt
#-temp_recover regression ./doc/random_linear_coef.txt ./doc/random_linear_coef1.txt ./doc/random_linear_ref.txt

#real table:
#fft_1024_alg1
#fft_1024_alg3
#LDPC.txt
#LDPC_802_11n.txt
#Robot_table
#RS-32_28_8_enc_table
#traffic-16e.txt

#FFT-1024_table
#Fpppp_table
#H264-1080p_dec_table
#H264-720p_dec_table
#LDPC_802_16e.txt
#RS-32_28_8_dec_table
#Sparse_table
