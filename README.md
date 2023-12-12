# machine-translation-project
Bridging the Language Gap with Seq2Seq and MT5

1. Flowchart for Machine Translation (English to French) using Seq2Seq
                 
![image](https://github.com/ATuL24Sh/machine-translation-project/assets/153619401/12332e9b-d335-4d80-827c-a03802d010b4)

2.  Architecture
  ![image](https://github.com/ATuL24Sh/machine-translation-project/assets/153619401/20833cc9-4d66-4470-8217-356da8fbd2a3)

The formula for the used for computing the hidden states from the encoder are as
follows :-
![image](https://github.com/ATuL24Sh/machine-translation-project/assets/153619401/e42e1c9c-f616-406c-b6fb-db7206255c27)

This is a simple multiplication of the weight vector to previous hidden state added to the
input vector. As for the decoder, following is the formula used computing the hidden
state:-
![image](https://github.com/ATuL24Sh/machine-translation-project/assets/153619401/f81f2675-a385-4b44-b75e-31306a106c2d)

The final output if no specific activation function is mentioned is computed using the
following formula:-
![image](https://github.com/ATuL24Sh/machine-translation-project/assets/153619401/c4e656c5-d927-405c-aa7b-29608fc9f030)

This implies the output is nothing but the multiplication matrix of the weight matrix
with the hidden vector of the current time step.

3. Result Analysis
   ![image](https://github.com/ATuL24Sh/machine-translation-project/assets/153619401/8e1846bd-aee3-4168-9c61-e38c847d9b56)
