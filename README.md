# Quantum Convolutional Neural Network

This is a GitHub repository for the Quantum Convolutional Neural Network (QCNN) project of the Qiskit Fall Fest Hackathon, held at the University of Montpellier from 15 to 22 October 2021.

This project implements a simplified Quantum Convolutional Neural Network (QCNN), a quantum analogue to a classical convolutional neural network. Convolutional neural networks are used in a variety of application fields, a.o. in remote sensing, which is the classification of satellite images to detect natural phenomena and suspicious activities.

This project follows the work of Iris Cong, Soonwon Choi and Mikhail D Lukin (https://arxiv.org/abs/1810.03787). They showed that this QCNN makes use of only O(log N) parameters for input sizes of N qubits, instead of O(N) parameters in the classical algorithm. This allows for an efficient training and implementation on quantum devices.

This work is also inspired by the implementation of QCNN using the Cirq API, as described in https://www.tensorflow.org/quantum/tutorials/qcnn.

You will find more details in the Jupyter Notebook included in this repository (https://github.com/YPadawan/qiskit-hackathon/blob/main/qcnn/QCNN_with_pytorch_and_qiskit.ipynb)

During the implementation of this project, we encountered a bug with the global phase in Qiskit and misleading text in the Qiskit primer which were reported to IBM. The bug reports are included in the papers directory. The bug was reported on the Qiskit repository: https://github.com/Qiskit/qiskit-terra/issues/5845#issuecomment-950140348

This work was performed by:

Idriss Alaoui Amini<br>
https://www.linkedin.com/in/idriss-alaoui-amini-11096160/

Matthijs van Waveren, CS GROUP<br>
https://www.linkedin.com/in/mvanwaveren/

Donchi Isaac<br>
https://www.linkedin.com/in/isaac-christ-donchi-kamga-501557200/

Nilesh Vyas
