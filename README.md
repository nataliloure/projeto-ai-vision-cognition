
## Projeto Bootcamp Microsoft 


### Utilização do Detect faces in an image 

### input:
Pacientes de mascara em uma sala de espera

### output:
Face #1
Face mask: yes
Face mask covering nose and mouth: yes
Face #2
Face mask: yes
Face mask covering nose and mouth: yes
Face #3
Face mask: yes
Face mask covering nose and mouth: yes
Face #4
Face mask: yes
Face mask covering nose and mouth: yes

### JSON:
````
[
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 121,
      "height": 163,
      "left": 432,
      "top": 236
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 523,
        "y": 304
      },
      "pupilRight": {
        "x": 544.5,
        "y": 306.9
      },
      "noseTip": {
        "x": 547.5,
        "y": 329.9
      },
      "mouthLeft": {
        "x": 525.1,
        "y": 353.6
      },
      "mouthRight": {
        "x": 540.6,
        "y": 353.5
      },
      "eyebrowLeftOuter": {
        "x": 516.3,
        "y": 292.8
      },
      "eyebrowLeftInner": {
        "x": 534.6,
        "y": 292.2
      },
      "eyeLeftOuter": {
        "x": 516.6,
        "y": 303.3
      },
      "eyeLeftTop": {
        "x": 525.2,
        "y": 301.1
      },
      "eyeLeftBottom": {
        "x": 522.3,
        "y": 306.6
      },
      "eyeLeftInner": {
        "x": 527.7,
        "y": 305.1
      },
      "eyebrowRightInner": {
        "x": 543.6,
        "y": 294
      },
      "eyebrowRightOuter": {
        "x": 550.4,
        "y": 300.3
      },
      "eyeRightInner": {
        "x": 539.8,
        "y": 307.2
      },
      "eyeRightTop": {
        "x": 545.4,
        "y": 303.7
      },
      "eyeRightBottom": {
        "x": 545.1,
        "y": 309.5
      },
      "eyeRightOuter": {
        "x": 547.6,
        "y": 307.4
      },
      "noseRootLeft": {
        "x": 533.9,
        "y": 307.7
      },
      "noseRootRight": {
        "x": 540.4,
        "y": 307.6
      },
      "noseLeftAlarTop": {
        "x": 531.2,
        "y": 324.7
      },
      "noseRightAlarTop": {
        "x": 542.8,
        "y": 324.1
      },
      "noseLeftAlarOutTip": {
        "x": 528.3,
        "y": 333.3
      },
      "noseRightAlarOutTip": {
        "x": 541.3,
        "y": 333.5
      },
      "upperLipTop": {
        "x": 539.9,
        "y": 348.3
      },
      "upperLipBottom": {
        "x": 537.6,
        "y": 351.9
      },
      "underLipTop": {
        "x": 536.4,
        "y": 356.7
      },
      "underLipBottom": {
        "x": 536.2,
        "y": 362.1
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "faceMask",
        "noseAndMouthCovered": true
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 71,
      "height": 95,
      "left": 694,
      "top": 375
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 724.5,
        "y": 400.1
      },
      "pupilRight": {
        "x": 746.9,
        "y": 402.6
      },
      "noseTip": {
        "x": 742.6,
        "y": 423.2
      },
      "mouthLeft": {
        "x": 720.4,
        "y": 436.2
      },
      "mouthRight": {
        "x": 737.9,
        "y": 436.6
      },
      "eyebrowLeftOuter": {
        "x": 719.3,
        "y": 388.6
      },
      "eyebrowLeftInner": {
        "x": 738,
        "y": 391.8
      },
      "eyeLeftOuter": {
        "x": 718.4,
        "y": 398.6
      },
      "eyeLeftTop": {
        "x": 726.7,
        "y": 398.7
      },
      "eyeLeftBottom": {
        "x": 723.5,
        "y": 401.9
      },
      "eyeLeftInner": {
        "x": 729.5,
        "y": 401
      },
      "eyebrowRightInner": {
        "x": 747.2,
        "y": 393.2
      },
      "eyebrowRightOuter": {
        "x": 754.2,
        "y": 394.2
      },
      "eyeRightInner": {
        "x": 742.4,
        "y": 402.6
      },
      "eyeRightTop": {
        "x": 748,
        "y": 401
      },
      "eyeRightBottom": {
        "x": 747,
        "y": 404.4
      },
      "eyeRightOuter": {
        "x": 750.1,
        "y": 402.3
      },
      "noseRootLeft": {
        "x": 735.3,
        "y": 403.2
      },
      "noseRootRight": {
        "x": 741.7,
        "y": 403.5
      },
      "noseLeftAlarTop": {
        "x": 730.5,
        "y": 416.1
      },
      "noseRightAlarTop": {
        "x": 742.4,
        "y": 416
      },
      "noseLeftAlarOutTip": {
        "x": 726.8,
        "y": 422
      },
      "noseRightAlarOutTip": {
        "x": 741,
        "y": 422.3
      },
      "upperLipTop": {
        "x": 735.5,
        "y": 435.2
      },
      "upperLipBottom": {
        "x": 733.2,
        "y": 437.5
      },
      "underLipTop": {
        "x": 732.2,
        "y": 440.5
      },
      "underLipBottom": {
        "x": 731.2,
        "y": 445.2
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "faceMask",
        "noseAndMouthCovered": true
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 60,
      "height": 72,
      "left": 1605,
      "top": 416
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 1623.9,
        "y": 448.9
      },
      "pupilRight": {
        "x": 1651.4,
        "y": 444.8
      },
      "noseTip": {
        "x": 1640.8,
        "y": 465.9
      },
      "mouthLeft": {
        "x": 1629.6,
        "y": 474.3
      },
      "mouthRight": {
        "x": 1650,
        "y": 471.6
      },
      "eyebrowLeftOuter": {
        "x": 1614.7,
        "y": 445.2
      },
      "eyebrowLeftInner": {
        "x": 1631.9,
        "y": 444.3
      },
      "eyeLeftOuter": {
        "x": 1618.9,
        "y": 448.9
      },
      "eyeLeftTop": {
        "x": 1624.2,
        "y": 447.9
      },
      "eyeLeftBottom": {
        "x": 1623.6,
        "y": 450.3
      },
      "eyeLeftInner": {
        "x": 1628.9,
        "y": 448.4
      },
      "eyebrowRightInner": {
        "x": 1643.5,
        "y": 442.7
      },
      "eyebrowRightOuter": {
        "x": 1659.1,
        "y": 438.6
      },
      "eyeRightInner": {
        "x": 1646.6,
        "y": 445.8
      },
      "eyeRightTop": {
        "x": 1651,
        "y": 444
      },
      "eyeRightBottom": {
        "x": 1651.8,
        "y": 446
      },
      "eyeRightOuter": {
        "x": 1656.1,
        "y": 443.5
      },
      "noseRootLeft": {
        "x": 1634.3,
        "y": 450
      },
      "noseRootRight": {
        "x": 1642.3,
        "y": 449.1
      },
      "noseLeftAlarTop": {
        "x": 1632.7,
        "y": 459.7
      },
      "noseRightAlarTop": {
        "x": 1645.8,
        "y": 457.7
      },
      "noseLeftAlarOutTip": {
        "x": 1630.8,
        "y": 464.4
      },
      "noseRightAlarOutTip": {
        "x": 1648.1,
        "y": 462
      },
      "upperLipTop": {
        "x": 1641.1,
        "y": 473.9
      },
      "upperLipBottom": {
        "x": 1640.6,
        "y": 475.1
      },
      "underLipTop": {
        "x": 1640.5,
        "y": 476
      },
      "underLipBottom": {
        "x": 1640.8,
        "y": 478.4
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "faceMask",
        "noseAndMouthCovered": true
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 54,
      "height": 74,
      "left": 1073,
      "top": 402
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 1094.5,
        "y": 434.9
      },
      "pupilRight": {
        "x": 1118.9,
        "y": 433.7
      },
      "noseTip": {
        "x": 1111.2,
        "y": 452.4
      },
      "mouthLeft": {
        "x": 1095.3,
        "y": 459.9
      },
      "mouthRight": {
        "x": 1114.7,
        "y": 458.3
      },
      "eyebrowLeftOuter": {
        "x": 1087,
        "y": 430.3
      },
      "eyebrowLeftInner": {
        "x": 1103.7,
        "y": 430.3
      },
      "eyeLeftOuter": {
        "x": 1089.4,
        "y": 434.6
      },
      "eyeLeftTop": {
        "x": 1095.3,
        "y": 433.7
      },
      "eyeLeftBottom": {
        "x": 1093.9,
        "y": 436.4
      },
      "eyeLeftInner": {
        "x": 1099.2,
        "y": 435
      },
      "eyebrowRightInner": {
        "x": 1114.1,
        "y": 430.3
      },
      "eyebrowRightOuter": {
        "x": 1125.4,
        "y": 428.8
      },
      "eyeRightInner": {
        "x": 1114.7,
        "y": 434.3
      },
      "eyeRightTop": {
        "x": 1119,
        "y": 432.5
      },
      "eyeRightBottom": {
        "x": 1119.2,
        "y": 435.1
      },
      "eyeRightOuter": {
        "x": 1122.6,
        "y": 432.8
      },
      "noseRootLeft": {
        "x": 1104.8,
        "y": 437
      },
      "noseRootRight": {
        "x": 1112.1,
        "y": 436.9
      },
      "noseLeftAlarTop": {
        "x": 1102.2,
        "y": 446.1
      },
      "noseRightAlarTop": {
        "x": 1114.2,
        "y": 445.2
      },
      "noseLeftAlarOutTip": {
        "x": 1099.6,
        "y": 450.4
      },
      "noseRightAlarOutTip": {
        "x": 1115,
        "y": 449.4
      },
      "upperLipTop": {
        "x": 1108.2,
        "y": 460.2
      },
      "upperLipBottom": {
        "x": 1107.1,
        "y": 461.3
      },
      "underLipTop": {
        "x": 1106.8,
        "y": 462.9
      },
      "underLipBottom": {
        "x": 1106.7,
        "y": 465.4
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "faceMask",
        "noseAndMouthCovered": true
      }
    }
  }
]
````
