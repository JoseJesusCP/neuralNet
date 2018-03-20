# neuralNet
Adjacent neural networks in ANSI C for micro controllers

# CAUTION : Code is still under development

HARDWARE TARGET : STM32F405

IDE : XCODE

POINTS TO NOTE

-> "Neurons" matrix is used to assign number of neurons and number of layers to the Network

-> Always write plus one neuron than needed in any layer
    example if you need 5 neuron in input declare neurons as "Neurons[]={6,....}
    
-> "MAX_LAYERS" is used to define number of layers

-> This net is being trained for iris dataset
      "inputAddress" is used for providing input to the net
      "outputAddress" is used for providing labels to the net
