Download Link: https://assignmentchef.com/product/solved-236200-homework-3
<br>
<h1>I      Theory</h1>

<h2>1.        On Circulant Matrices</h2>

<table width="0">

 <tbody>

  <tr>

   <td width="218">01 a. Consider the matrix <em>J </em>= 0…0 In particular, what is <em>J<sup>n</sup></em>?</td>

   <td width="30"><em>…</em>01…<em>…</em></td>

   <td width="31"><em>…</em>…0…0</td>

   <td width="29">0………1</td>

   <td width="245">10<sub></sub><sup> </sup>∈ R <sup>×<em>n</em></sup>. For <em>k </em>∈ N, compute <em>J<sup>k</sup></em>.0<sub>        </sub><em>n</em>…<sub></sub>0</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Compute the eigenvalues of <em>J</em>.</li>

 <li>Do the full eigendecomposition of <em>J</em>. Is <em>J </em>diagonalisable? If yes, can it be diagonalised in a unitary basis?</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="362"> <em>h</em><sub>0</sub> <em>h</em>1d. Consider the general circulant matrix <em>H </em>= <sup> <em>h</em></sup>2 …<em>h</em><em>n</em>−1</td>

   <td width="44"><em>h</em><em>n</em>−1 <em>h</em><sub>0 </sub><em>h</em><sub>1</sub>…<em>h</em><em>n</em>−2</td>

   <td width="44"><em>h</em><em>n</em>−2 <em>h</em><em>n</em>−1 <em>h</em><sub>0</sub>…<em>h</em><em>n</em>−3</td>

   <td width="30"><em>…</em><em>…</em><em>…</em>…<em>…</em></td>

   <td width="75"><em>h</em><sub>1</sub> <em>h</em>2 <em><sup>h</sup></em>3<sup></sup>. Show… <sub></sub><em>h</em><sub>0</sub></td>

  </tr>

 </tbody>

</table>

that <em>H </em>and <em>J </em>are linked by a polynomial expression, i.e. find a polynomial <em>P </em>such that <em>H </em>= <em>P</em>(<em>J</em>).

<ol>

 <li>Compute the full eigendecomposition of <em>H</em>. Is it diagonalisable and if so is it in a unitary basis?</li>

 <li>Show that the diagonalisation basis matrix <em>B </em>can be chosen as the <em>DFT</em><sup>∗ </sup></li>

 <li>Prove that the eigenvalues, stacked in a column, equals to the product of <em>B </em>and the first row of <em>H </em>rewritten in column form, i.e. if <em>λ</em><sub>0</sub><em>,…,λ<sub>n</sub></em><sub>−1 </sub>are the eigenvalues of <em>H </em>then:</li>

</ol>

.

<ol start="2">

 <li>Consider two circulant matrices <em>H</em><sub>1 </sub>and <em>H</em><sub>2</sub>. Show that they commute. Compute <em>H</em><sub>1</sub><em>H</em><sub>2</sub>, is this matrix circulant?</li>

 <li>Compute <em>DFT<sup>k </sup></em>for <em>k </em>∈ N. What are the resulting matrices?</li>

 <li>Prove that a convolution of <em>n</em>-dimensional signals can be computed by point-wise multiplication of the signals in the Fourier domain. This means prove that if <em>z </em>= <em>x</em>⊗<em>y </em>where ⊗ the convolution operator, then ( where is the Hadamard product.</li>

</ol>

<h2>2.          Convolutional Neural Networks (CNN)</h2>

In this exercise we will set ourselves in the trendy context of Convolutional Neural networks. The input signals are typically 2D images but are reshaped as a 1D vector. The layers of the network can be seen as successive operators applied to the input. We want to study some basic properties, seen from the perspective of the class, of these transforms. Please provide appropriate mathematical justifications for all your claims.

<ol>

 <li>Consider a convolution operator, also known as layer, <em>C</em><sub>1</sub>. Is this layer linear? Is it shift-invariant?</li>

 <li>Assume layer <em>C</em><sub>1 </sub>is followed by another convolutional layer <em>C</em><sub>2</sub>. Is the operator <em>C</em><sub>1<em>,</em>2 </sub>= <em>C</em><sub>2 </sub>◦ <em>C</em><sub>1 </sub>defined as the composition of the two convolutional layers linear? Is it shift-invariant?</li>

 <li>Show that the result of a succession of any number of convolutional layers is equivalentto the result of a single convolutional layer.</li>

 <li>We now wish to introduce a non linear layer to the network. Consider the relu operator. This operator applies for each entry of its input signal <em>x </em>the new entry <em>x</em><sup>+ </sup>= max{<em>x,</em>0} of the its output signal. Is this layer linear? Is it shift invariant? Is the current network (the successive convolutions and relu layers) linear? Is it shift-invariant?</li>

 <li>We now add to the architecture of the network successive alternations of convolutionallayers and relu layers. The network provides a deep vector, also called embedding, on the input signal to the network. The embedding is to be used for various purposes, such as providing as low dimensional compact and informative representation of the signal that is appropriate for classification. Is the embedding a linear transform of the input signal? Is it shift-invariant with respect to the input signal?</li>

</ol>

<h2>3.         Optimal Basis for Smooth Signals</h2>

Complete the proof of Theorem 3 (Optimal Basis for Smooth Signals) by showing the uniqueness of the Fourier basis for the case of a simple spectrum with:

0 <em>&lt; λ</em><sub>1 </sub><em>&lt; λ</em><sub>2 </sub><em>&lt; λ</em><sub>3 </sub><em>&lt; …</em>

Your proof should rely on Poincar`e’s “magic trick” that appears also in the uniqueness proof given in the following paper for a general spectrum: Haim Brezis and David GomezCastro, ”Rigidity of optimal bases for signal spaces”, Comptes Rendus Mathematique 355.7 (2017): 780-785.

Your proof should be a simplified version of the proof in the above paper, as we consider here the simple spectrum defined above (and in the lecture notes).

<h2>4.      Fourier Transform</h2>

<ol>

 <li>Given two functions <em>f</em>(<em>t</em>) and <em>g</em>(<em>t</em>) and denote the convolution of the two functions by <em>h</em>(<em>t</em>), that is</li>

</ol>

<em>f</em>(<em>t</em>) ∗ <em>g</em>(<em>t</em>) = <em>h</em>(<em>t</em>)                                                                  (1)

What is <em>f</em>(<em>t </em>− 1) ∗ <em>g</em>(<em>t </em>+ 1) in terms of <em>h</em>(<em>t</em>)?

<ol>

 <li>Given two functions <em>f</em>(<em>t</em>) and <em>g</em>(<em>t</em>), show that the following condition holds</li>

</ol>

(2)

where F(<em>u</em>) and G(<em>u</em>) are the Fourier transform of <em>f</em>(<em>t</em>) and <em>g</em>(<em>t</em>) respectively.

Hint: you should represent the function by convolution and apply the convolution theorem in Fourier domain. Note that the inverse Fourier transform should be taken into accounts.

<ol>

 <li>Using the results from the previous question. Given two functions <em>f</em>(<em>t</em>) and <em>g</em>(<em>t</em>), show that the following condition holds</li>

</ol>

(3)

<ol>

 <li>Compute the following integral</li>

</ol>

(4)

Hint: the continuous Fourier transform of the normalized sinc(<em>t</em>) (to ordinary frequency) is rect(<em>u</em>),

<h1>II       Matlab</h1>

The purpose of this exercise is to get familiar with the concept of functional maps. We will transform images/signal in some ways and consider these transforms as the result of remapping the image after some changes in the parametrisation. In class, you saw that when the transform is known then the link between the coefficients of orthonormal basis in the first image/signal and in the second image/signal are linked by a linear transform, i.e. a matrix called the functional map. However, here we do not provide you with the corresponding transform but you can still recover approximately the functional map.

Instruction:

<ul>

 <li>Figures should be titled in a appropriate font size.</li>

 <li>Submit the code and a report describing the results and your understanding of the exercise.</li>

 <li>Note that the additional image files and audio files provided in the course website with this homework assignment.</li>

 <li>It is recommended to normalize the graylevels to the range [0,1] after loading the images.</li>

</ul>

<h2>1.       Image example</h2>

Consider the mandril image and its distorted version. The distortion was found by applying a transform of the <em>x </em>parameter space, by squeezing and strecthing the <em>x </em>axis. Here, we consider one signal as a row of the image. Thus each row of the original image has been squeezed and stretched in the same way, giving the rows of the distorted image.

The basis of interest, both in the original image domain and in the distorted image domain is the DFT matrix basis. The DFT has as many columns (and rows) than the signals have entries, i.e. as many columns as the images.

<ol>

 <li>Compute the DFT representation coefficients for each row signal in the original anddistorted image. Denote <em>α<sub>r,i </sub></em>(resp. <em>β<sub>r,i</sub></em>) the <em>i</em>-th coefficient of the <em>r</em>-th row in the original (resp. distorted) image. As usual with the DFT, we start indexing at 0 (be careful in your matlab implementations as indexing starts at 1 in this programming language).</li>

 <li>Denote, using the notations in the lecture, e<em>c<sub>i,j </sub></em>the <em>i,j</em>-th coefficient of the functional map <em>C</em>. Recall that then <em>β<sub>r,j </sub></em>= <sup>P</sup><em>α<sub>r,k</sub></em><sub>e</sub><em>c<sub>k,j</sub></em>. We can rewrite this in a more compact</li>

</ol>

<em>i</em>

matrix formulation for each row <em>r </em>as <em>b</em><sub>e<em>r </em></sub>= <em>a<sub>r</sub>C</em>, where <em>a<sub>r </sub></em>(resp. <em>b</em><sub>e<em>r</em></sub>) is the representation row of coefficients of the <em>r</em>-th row of the original (resp. distorted) row in the DFT basis. We can stack this matrix formulation into an even more compact formulation by writing <em>B</em><sub>e </sub>= <em>AC </em>where the <em>r</em>-th row of <em>A </em>(resp. <em>B</em><sub>e</sub>) is <em>a<sub>r </sub></em>(resp. <em>b</em><sub>e<em>r</em></sub>). When the transform mapping is known, <em>C </em>can be explicitly computed. Unfortunately, it is here considered as unknown and slight errors may exist leading to noise effects. Thus stacking each row allows to improve the stability of the recovered functional map. We wish to compute empirically <em>C </em>using a least squares approach. That is compute

<em>C</em><sub>b </sub>such that <em>C</em><sub>b </sub>∈ argmin. Least squares is a well-known problem and it

<em>C</em>

can be solved, with some assumptions on the rank of <em>A </em>with pseudo inversion. Show that the matrix <em>A </em>is full rank, and so computing the pseudo inverse is legal. If it is not full rank remove redundant columns from the problem until you get a full rank matrix. Find then <em>C</em><sub>b</sub>. You might want to consider using the matlab built-in function <em>pinv </em>for pseudo inversion.

<ol>

 <li>Distort the original image rows using your approximation of the functional map <em>C</em><sub>b</sub>. Note that you must go into the DFT domain to do your calculations and back to the normal domain to display an image understandable for a human being. Compare your result with the given distorted image.</li>

 <li>Distort the ‘butterfly’ image by distorting its rows using <em>C</em><sub>b</sub>.</li>

</ol>

<h2>2.       Audio example</h2>

Consider two audio signals (skycastle.wav and skycastle-distortion.wav) note that skycastledistortion signal is the distortional signal of skycastle. Assume that the period of the distortion is known and it is 512 in entry unit.

Utilizing the same approach as with the image case, estimate an approximate functional map between the clean signal and the noisy signal. Use the DFT basis for the basis functions. (Hint: Note that the distortion is independent from the true signal and it is periodic, then the transformation can be done periodically as well. You might want to divide your signal into successive non overlapping small signals.) Use the matrices to denoise the other audio signal (totoro-distortion.wav). Compare the obtained result with the corresponding true audio signal (totoro.wav) by graph. What is the MSE error?

To read the audiofiles you can use the <em>audioread </em>function. To run a vector in audio (i.e. send it to your speakers and hear your signal), you can use the <em>sound </em>function. For these audio signals, set the sample frequency to be <em>Fs </em>= 48000 when sounding them (since it is the sampling frequency).