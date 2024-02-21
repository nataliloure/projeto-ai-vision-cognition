
## Projeto Bootcamp Microsoft Azure


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

### Utilização do Extract text from images

### Input:
Modelo de laudo médico 

### output:
Logomarca
Endereçocompleto(Rua,numero,bairro,cidadeeestado)
Telefonesdecontatocomddd
Códigovalidador:
xxxx
LaudoRadiográfico:
Controle:202212/111
Nome:PACIENTETESTE
Indicação:AVALIAÇÃOMÉDICA(CLÍNICO)
Datadenascimento:09/06/1986(36a.6m.)
Datadoexame:14/12/2022
Sexo:FEMININO
Convênio:SUS
TÓRAX-PAePerfil
Conclusões:
Análise:
Estruturasósseassemalteraçõesevidenciáveis.
Áreacardiacaehilospulmonaresdeaspectonormal.
Mediastinoanatómico.
Pulmõescomtransparênciaconservada.
Espaçospleuraislivres
Considerações:
Exameradiológicodeaspectonormal,
Ananindeua,14dedezembrode2022.
Dr.MédicoMaisLaudo
CRMWWW-SP/ROE:VVVV-Radiologista
Paravalidarestedocumentoacesse:appmaislaudo.com.be/Valideseulaudoeinformeoloken:xxxxxcon

### JSON:

```
[
  {
    "lines": [
      {
        "text": "Logo marca",
        "boundingPolygon": [
          {
            "x": 52,
            "y": 60
          },
          {
            "x": 101,
            "y": 60
          },
          {
            "x": 101,
            "y": 70
          },
          {
            "x": 52,
            "y": 70
          }
        ],
        "words": [
          {
            "text": "Logo",
            "boundingPolygon": [
              {
                "x": 53,
                "y": 61
              },
              {
                "x": 74,
                "y": 61
              },
              {
                "x": 74,
                "y": 70
              },
              {
                "x": 53,
                "y": 70
              }
            ],
            "confidence": 0.987
          },
          {
            "text": "marca",
            "boundingPolygon": [
              {
                "x": 76,
                "y": 61
              },
              {
                "x": 101,
                "y": 61
              },
              {
                "x": 101,
                "y": 70
              },
              {
                "x": 76,
                "y": 70
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "Endereço completo (Rua, numero, bairro, cidade e estado)",
        "boundingPolygon": [
          {
            "x": 150,
            "y": 52
          },
          {
            "x": 353,
            "y": 52
          },
          {
            "x": 353,
            "y": 63
          },
          {
            "x": 150,
            "y": 63
          }
        ],
        "words": [
          {
            "text": "Endereço",
            "boundingPolygon": [
              {
                "x": 151,
                "y": 53
              },
              {
                "x": 184,
                "y": 53
              },
              {
                "x": 183,
                "y": 63
              },
              {
                "x": 150,
                "y": 63
              }
            ],
            "confidence": 0.959
          },
          {
            "text": "completo",
            "boundingPolygon": [
              {
                "x": 186,
                "y": 53
              },
              {
                "x": 216,
                "y": 52
              },
              {
                "x": 216,
                "y": 64
              },
              {
                "x": 185,
                "y": 63
              }
            ],
            "confidence": 0.942
          },
          {
            "text": "(Rua,",
            "boundingPolygon": [
              {
                "x": 218,
                "y": 52
              },
              {
                "x": 237,
                "y": 52
              },
              {
                "x": 237,
                "y": 64
              },
              {
                "x": 218,
                "y": 64
              }
            ],
            "confidence": 0.844
          },
          {
            "text": "numero,",
            "boundingPolygon": [
              {
                "x": 239,
                "y": 52
              },
              {
                "x": 268,
                "y": 53
              },
              {
                "x": 267,
                "y": 64
              },
              {
                "x": 239,
                "y": 64
              }
            ],
            "confidence": 0.878
          },
          {
            "text": "bairro,",
            "boundingPolygon": [
              {
                "x": 270,
                "y": 53
              },
              {
                "x": 292,
                "y": 53
              },
              {
                "x": 292,
                "y": 63
              },
              {
                "x": 269,
                "y": 64
              }
            ],
            "confidence": 0.882
          },
          {
            "text": "cidade",
            "boundingPolygon": [
              {
                "x": 294,
                "y": 53
              },
              {
                "x": 317,
                "y": 53
              },
              {
                "x": 317,
                "y": 63
              },
              {
                "x": 294,
                "y": 63
              }
            ],
            "confidence": 0.959
          },
          {
            "text": "e",
            "boundingPolygon": [
              {
                "x": 319,
                "y": 53
              },
              {
                "x": 323,
                "y": 53
              },
              {
                "x": 323,
                "y": 63
              },
              {
                "x": 319,
                "y": 63
              }
            ],
            "confidence": 0.993
          },
          {
            "text": "estado)",
            "boundingPolygon": [
              {
                "x": 325,
                "y": 53
              },
              {
                "x": 353,
                "y": 53
              },
              {
                "x": 353,
                "y": 63
              },
              {
                "x": 325,
                "y": 63
              }
            ],
            "confidence": 0.959
          }
        ]
      },
      {
        "text": "Telefones de contato com ddd",
        "boundingPolygon": [
          {
            "x": 191,
            "y": 72
          },
          {
            "x": 298,
            "y": 73
          },
          {
            "x": 298,
            "y": 83
          },
          {
            "x": 191,
            "y": 83
          }
        ],
        "words": [
          {
            "text": "Telefones",
            "boundingPolygon": [
              {
                "x": 194,
                "y": 73
              },
              {
                "x": 227,
                "y": 74
              },
              {
                "x": 227,
                "y": 83
              },
              {
                "x": 194,
                "y": 83
              }
            ],
            "confidence": 0.792
          },
          {
            "text": "de",
            "boundingPolygon": [
              {
                "x": 229,
                "y": 74
              },
              {
                "x": 237,
                "y": 74
              },
              {
                "x": 238,
                "y": 83
              },
              {
                "x": 229,
                "y": 83
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "contato",
            "boundingPolygon": [
              {
                "x": 239,
                "y": 74
              },
              {
                "x": 265,
                "y": 74
              },
              {
                "x": 265,
                "y": 83
              },
              {
                "x": 240,
                "y": 83
              }
            ],
            "confidence": 0.977
          },
          {
            "text": "com",
            "boundingPolygon": [
              {
                "x": 267,
                "y": 74
              },
              {
                "x": 280,
                "y": 74
              },
              {
                "x": 280,
                "y": 83
              },
              {
                "x": 267,
                "y": 83
              }
            ],
            "confidence": 0.939
          },
          {
            "text": "ddd",
            "boundingPolygon": [
              {
                "x": 283,
                "y": 74
              },
              {
                "x": 297,
                "y": 73
              },
              {
                "x": 298,
                "y": 83
              },
              {
                "x": 283,
                "y": 83
              }
            ],
            "confidence": 0.881
          }
        ]
      },
      {
        "text": "Código validador:",
        "boundingPolygon": [
          {
            "x": 359,
            "y": 95
          },
          {
            "x": 425,
            "y": 96
          },
          {
            "x": 425,
            "y": 106
          },
          {
            "x": 359,
            "y": 105
          }
        ],
        "words": [
          {
            "text": "Código",
            "boundingPolygon": [
              {
                "x": 360,
                "y": 96
              },
              {
                "x": 387,
                "y": 97
              },
              {
                "x": 386,
                "y": 106
              },
              {
                "x": 360,
                "y": 106
              }
            ],
            "confidence": 0.992
          },
          {
            "text": "validador:",
            "boundingPolygon": [
              {
                "x": 388,
                "y": 97
              },
              {
                "x": 425,
                "y": 97
              },
              {
                "x": 425,
                "y": 106
              },
              {
                "x": 388,
                "y": 106
              }
            ],
            "confidence": 0.976
          }
        ]
      },
      {
        "text": "xxxx",
        "boundingPolygon": [
          {
            "x": 359,
            "y": 106
          },
          {
            "x": 383,
            "y": 106
          },
          {
            "x": 383,
            "y": 115
          },
          {
            "x": 359,
            "y": 115
          }
        ],
        "words": [
          {
            "text": "xxxx",
            "boundingPolygon": [
              {
                "x": 360,
                "y": 106
              },
              {
                "x": 382,
                "y": 106
              },
              {
                "x": 382,
                "y": 115
              },
              {
                "x": 360,
                "y": 115
              }
            ],
            "confidence": 0.989
          }
        ]
      },
      {
        "text": "Laudo Radiográfico:",
        "boundingPolygon": [
          {
            "x": 198,
            "y": 124
          },
          {
            "x": 280,
            "y": 124
          },
          {
            "x": 279,
            "y": 135
          },
          {
            "x": 198,
            "y": 135
          }
        ],
        "words": [
          {
            "text": "Laudo",
            "boundingPolygon": [
              {
                "x": 200,
                "y": 125
              },
              {
                "x": 223,
                "y": 126
              },
              {
                "x": 223,
                "y": 136
              },
              {
                "x": 199,
                "y": 135
              }
            ],
            "confidence": 0.989
          },
          {
            "text": "Radiográfico:",
            "boundingPolygon": [
              {
                "x": 225,
                "y": 126
              },
              {
                "x": 278,
                "y": 125
              },
              {
                "x": 278,
                "y": 136
              },
              {
                "x": 225,
                "y": 136
              }
            ],
            "confidence": 0.67
          }
        ]
      },
      {
        "text": "Controle: 202212/111",
        "boundingPolygon": [
          {
            "x": 363,
            "y": 126
          },
          {
            "x": 441,
            "y": 126
          },
          {
            "x": 441,
            "y": 135
          },
          {
            "x": 363,
            "y": 135
          }
        ],
        "words": [
          {
            "text": "Controle:",
            "boundingPolygon": [
              {
                "x": 364,
                "y": 127
              },
              {
                "x": 398,
                "y": 126
              },
              {
                "x": 398,
                "y": 135
              },
              {
                "x": 364,
                "y": 135
              }
            ],
            "confidence": 0.99
          },
          {
            "text": "202212/111",
            "boundingPolygon": [
              {
                "x": 400,
                "y": 126
              },
              {
                "x": 441,
                "y": 126
              },
              {
                "x": 441,
                "y": 136
              },
              {
                "x": 400,
                "y": 135
              }
            ],
            "confidence": 0.992
          }
        ]
      },
      {
        "text": "Nome: PACIENTE TESTE",
        "boundingPolygon": [
          {
            "x": 25,
            "y": 151
          },
          {
            "x": 119,
            "y": 151
          },
          {
            "x": 120,
            "y": 161
          },
          {
            "x": 25,
            "y": 162
          }
        ],
        "words": [
          {
            "text": "Nome:",
            "boundingPolygon": [
              {
                "x": 26,
                "y": 152
              },
              {
                "x": 50,
                "y": 152
              },
              {
                "x": 50,
                "y": 162
              },
              {
                "x": 26,
                "y": 162
              }
            ],
            "confidence": 0.993
          },
          {
            "text": "PACIENTE",
            "boundingPolygon": [
              {
                "x": 52,
                "y": 152
              },
              {
                "x": 92,
                "y": 151
              },
              {
                "x": 91,
                "y": 162
              },
              {
                "x": 52,
                "y": 162
              }
            ],
            "confidence": 0.98
          },
          {
            "text": "TESTE",
            "boundingPolygon": [
              {
                "x": 94,
                "y": 151
              },
              {
                "x": 118,
                "y": 151
              },
              {
                "x": 118,
                "y": 162
              },
              {
                "x": 93,
                "y": 162
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "Indicação: AVALIAÇÃO MÉDICA (CLÍNICO)",
        "boundingPolygon": [
          {
            "x": 253,
            "y": 151
          },
          {
            "x": 408,
            "y": 152
          },
          {
            "x": 408,
            "y": 163
          },
          {
            "x": 253,
            "y": 163
          }
        ],
        "words": [
          {
            "text": "Indicação:",
            "boundingPolygon": [
              {
                "x": 254,
                "y": 152
              },
              {
                "x": 292,
                "y": 152
              },
              {
                "x": 292,
                "y": 163
              },
              {
                "x": 254,
                "y": 163
              }
            ],
            "confidence": 0.901
          },
          {
            "text": "AVALIAÇÃO",
            "boundingPolygon": [
              {
                "x": 295,
                "y": 152
              },
              {
                "x": 337,
                "y": 152
              },
              {
                "x": 337,
                "y": 163
              },
              {
                "x": 294,
                "y": 163
              }
            ],
            "confidence": 0.905
          },
          {
            "text": "MÉDICA",
            "boundingPolygon": [
              {
                "x": 340,
                "y": 152
              },
              {
                "x": 369,
                "y": 152
              },
              {
                "x": 369,
                "y": 163
              },
              {
                "x": 340,
                "y": 163
              }
            ],
            "confidence": 0.546
          },
          {
            "text": "(CLÍNICO)",
            "boundingPolygon": [
              {
                "x": 371,
                "y": 152
              },
              {
                "x": 408,
                "y": 152
              },
              {
                "x": 409,
                "y": 164
              },
              {
                "x": 372,
                "y": 163
              }
            ],
            "confidence": 0.535
          }
        ]
      },
      {
        "text": "Data de nascimento: 09/06/1986 (36 a. 6 m.)",
        "boundingPolygon": [
          {
            "x": 26,
            "y": 166
          },
          {
            "x": 183,
            "y": 166
          },
          {
            "x": 183,
            "y": 177
          },
          {
            "x": 26,
            "y": 177
          }
        ],
        "words": [
          {
            "text": "Data",
            "boundingPolygon": [
              {
                "x": 26,
                "y": 167
              },
              {
                "x": 43,
                "y": 167
              },
              {
                "x": 43,
                "y": 178
              },
              {
                "x": 26,
                "y": 177
              }
            ],
            "confidence": 0.984
          },
          {
            "text": "de",
            "boundingPolygon": [
              {
                "x": 45,
                "y": 167
              },
              {
                "x": 53,
                "y": 167
              },
              {
                "x": 53,
                "y": 178
              },
              {
                "x": 45,
                "y": 178
              }
            ],
            "confidence": 0.995
          },
          {
            "text": "nascimento:",
            "boundingPolygon": [
              {
                "x": 55,
                "y": 167
              },
              {
                "x": 101,
                "y": 167
              },
              {
                "x": 101,
                "y": 178
              },
              {
                "x": 55,
                "y": 178
              }
            ],
            "confidence": 0.967
          },
          {
            "text": "09/06/1986",
            "boundingPolygon": [
              {
                "x": 103,
                "y": 167
              },
              {
                "x": 141,
                "y": 167
              },
              {
                "x": 141,
                "y": 178
              },
              {
                "x": 103,
                "y": 178
              }
            ],
            "confidence": 0.623
          },
          {
            "text": "(36",
            "boundingPolygon": [
              {
                "x": 143,
                "y": 167
              },
              {
                "x": 154,
                "y": 167
              },
              {
                "x": 154,
                "y": 178
              },
              {
                "x": 143,
                "y": 178
              }
            ],
            "confidence": 0.985
          },
          {
            "text": "a.",
            "boundingPolygon": [
              {
                "x": 157,
                "y": 167
              },
              {
                "x": 163,
                "y": 167
              },
              {
                "x": 162,
                "y": 178
              },
              {
                "x": 156,
                "y": 178
              }
            ],
            "confidence": 0.874
          },
          {
            "text": "6",
            "boundingPolygon": [
              {
                "x": 165,
                "y": 167
              },
              {
                "x": 168,
                "y": 167
              },
              {
                "x": 168,
                "y": 178
              },
              {
                "x": 165,
                "y": 178
              }
            ],
            "confidence": 0.993
          },
          {
            "text": "m.)",
            "boundingPolygon": [
              {
                "x": 170,
                "y": 167
              },
              {
                "x": 184,
                "y": 167
              },
              {
                "x": 183,
                "y": 178
              },
              {
                "x": 170,
                "y": 178
              }
            ],
            "confidence": 0.614
          }
        ]
      },
      {
        "text": "Data do exame: 14/12/2022",
        "boundingPolygon": [
          {
            "x": 254,
            "y": 167
          },
          {
            "x": 338,
            "y": 167
          },
          {
            "x": 338,
            "y": 176
          },
          {
            "x": 254,
            "y": 176
          }
        ],
        "words": [
          {
            "text": "Data",
            "boundingPolygon": [
              {
                "x": 255,
                "y": 167
              },
              {
                "x": 269,
                "y": 168
              },
              {
                "x": 269,
                "y": 177
              },
              {
                "x": 255,
                "y": 177
              }
            ],
            "confidence": 0.879
          },
          {
            "text": "do",
            "boundingPolygon": [
              {
                "x": 271,
                "y": 168
              },
              {
                "x": 278,
                "y": 168
              },
              {
                "x": 278,
                "y": 177
              },
              {
                "x": 270,
                "y": 177
              }
            ],
            "confidence": 0.849
          },
          {
            "text": "exame:",
            "boundingPolygon": [
              {
                "x": 280,
                "y": 168
              },
              {
                "x": 305,
                "y": 168
              },
              {
                "x": 304,
                "y": 177
              },
              {
                "x": 280,
                "y": 177
              }
            ],
            "confidence": 0.944
          },
          {
            "text": "14/12/2022",
            "boundingPolygon": [
              {
                "x": 306,
                "y": 168
              },
              {
                "x": 337,
                "y": 168
              },
              {
                "x": 337,
                "y": 176
              },
              {
                "x": 306,
                "y": 177
              }
            ],
            "confidence": 0.804
          }
        ]
      },
      {
        "text": "Sexo: FEMININO",
        "boundingPolygon": [
          {
            "x": 24,
            "y": 182
          },
          {
            "x": 87,
            "y": 182
          },
          {
            "x": 87,
            "y": 192
          },
          {
            "x": 24,
            "y": 192
          }
        ],
        "words": [
          {
            "text": "Sexo:",
            "boundingPolygon": [
              {
                "x": 26,
                "y": 182
              },
              {
                "x": 48,
                "y": 182
              },
              {
                "x": 48,
                "y": 192
              },
              {
                "x": 26,
                "y": 192
              }
            ],
            "confidence": 0.973
          },
          {
            "text": "FEMININO",
            "boundingPolygon": [
              {
                "x": 50,
                "y": 182
              },
              {
                "x": 85,
                "y": 182
              },
              {
                "x": 84,
                "y": 192
              },
              {
                "x": 50,
                "y": 192
              }
            ],
            "confidence": 0.55
          }
        ]
      },
      {
        "text": "Convênio: SUS",
        "boundingPolygon": [
          {
            "x": 255,
            "y": 181
          },
          {
            "x": 313,
            "y": 181
          },
          {
            "x": 313,
            "y": 190
          },
          {
            "x": 255,
            "y": 190
          }
        ],
        "words": [
          {
            "text": "Convênio:",
            "boundingPolygon": [
              {
                "x": 255,
                "y": 181
              },
              {
                "x": 293,
                "y": 182
              },
              {
                "x": 293,
                "y": 191
              },
              {
                "x": 255,
                "y": 190
              }
            ],
            "confidence": 0.641
          },
          {
            "text": "SUS",
            "boundingPolygon": [
              {
                "x": 295,
                "y": 181
              },
              {
                "x": 311,
                "y": 181
              },
              {
                "x": 311,
                "y": 191
              },
              {
                "x": 295,
                "y": 191
              }
            ],
            "confidence": 0.976
          }
        ]
      },
      {
        "text": "TÓRAX - PA e Perfil",
        "boundingPolygon": [
          {
            "x": 25,
            "y": 206
          },
          {
            "x": 99,
            "y": 206
          },
          {
            "x": 99,
            "y": 217
          },
          {
            "x": 25,
            "y": 217
          }
        ],
        "words": [
          {
            "text": "TÓRAX",
            "boundingPolygon": [
              {
                "x": 26,
                "y": 207
              },
              {
                "x": 52,
                "y": 207
              },
              {
                "x": 52,
                "y": 218
              },
              {
                "x": 26,
                "y": 218
              }
            ],
            "confidence": 0.688
          },
          {
            "text": "-",
            "boundingPolygon": [
              {
                "x": 54,
                "y": 207
              },
              {
                "x": 57,
                "y": 207
              },
              {
                "x": 57,
                "y": 218
              },
              {
                "x": 54,
                "y": 218
              }
            ],
            "confidence": 0.959
          },
          {
            "text": "PA",
            "boundingPolygon": [
              {
                "x": 59,
                "y": 207
              },
              {
                "x": 69,
                "y": 207
              },
              {
                "x": 69,
                "y": 218
              },
              {
                "x": 59,
                "y": 218
              }
            ],
            "confidence": 0.979
          },
          {
            "text": "e",
            "boundingPolygon": [
              {
                "x": 71,
                "y": 207
              },
              {
                "x": 76,
                "y": 207
              },
              {
                "x": 76,
                "y": 218
              },
              {
                "x": 71,
                "y": 218
              }
            ],
            "confidence": 0.647
          },
          {
            "text": "Perfil",
            "boundingPolygon": [
              {
                "x": 78,
                "y": 207
              },
              {
                "x": 99,
                "y": 207
              },
              {
                "x": 99,
                "y": 217
              },
              {
                "x": 78,
                "y": 217
              }
            ],
            "confidence": 0.854
          }
        ]
      },
      {
        "text": "Conclusões:",
        "boundingPolygon": [
          {
            "x": 40,
            "y": 224
          },
          {
            "x": 88,
            "y": 224
          },
          {
            "x": 88,
            "y": 234
          },
          {
            "x": 40,
            "y": 234
          }
        ],
        "words": [
          {
            "text": "Conclusões:",
            "boundingPolygon": [
              {
                "x": 41,
                "y": 224
              },
              {
                "x": 88,
                "y": 225
              },
              {
                "x": 88,
                "y": 234
              },
              {
                "x": 41,
                "y": 235
              }
            ],
            "confidence": 0.951
          }
        ]
      },
      {
        "text": "Análise:",
        "boundingPolygon": [
          {
            "x": 39,
            "y": 254
          },
          {
            "x": 72,
            "y": 254
          },
          {
            "x": 72,
            "y": 264
          },
          {
            "x": 39,
            "y": 263
          }
        ],
        "words": [
          {
            "text": "Análise:",
            "boundingPolygon": [
              {
                "x": 41,
                "y": 254
              },
              {
                "x": 72,
                "y": 255
              },
              {
                "x": 72,
                "y": 264
              },
              {
                "x": 41,
                "y": 264
              }
            ],
            "confidence": 0.989
          }
        ]
      },
      {
        "text": "Estruturas ósseas sem alterações evidenciáveis.",
        "boundingPolygon": [
          {
            "x": 40,
            "y": 264
          },
          {
            "x": 226,
            "y": 264
          },
          {
            "x": 226,
            "y": 274
          },
          {
            "x": 40,
            "y": 274
          }
        ],
        "words": [
          {
            "text": "Estruturas",
            "boundingPolygon": [
              {
                "x": 41,
                "y": 264
              },
              {
                "x": 80,
                "y": 265
              },
              {
                "x": 80,
                "y": 275
              },
              {
                "x": 40,
                "y": 275
              }
            ],
            "confidence": 0.987
          },
          {
            "text": "ósseas",
            "boundingPolygon": [
              {
                "x": 82,
                "y": 265
              },
              {
                "x": 110,
                "y": 265
              },
              {
                "x": 109,
                "y": 275
              },
              {
                "x": 82,
                "y": 275
              }
            ],
            "confidence": 0.959
          },
          {
            "text": "sem",
            "boundingPolygon": [
              {
                "x": 112,
                "y": 265
              },
              {
                "x": 126,
                "y": 265
              },
              {
                "x": 126,
                "y": 275
              },
              {
                "x": 111,
                "y": 275
              }
            ],
            "confidence": 0.991
          },
          {
            "text": "alterações",
            "boundingPolygon": [
              {
                "x": 130,
                "y": 265
              },
              {
                "x": 170,
                "y": 265
              },
              {
                "x": 170,
                "y": 275
              },
              {
                "x": 130,
                "y": 275
              }
            ],
            "confidence": 0.953
          },
          {
            "text": "evidenciáveis.",
            "boundingPolygon": [
              {
                "x": 172,
                "y": 265
              },
              {
                "x": 226,
                "y": 265
              },
              {
                "x": 226,
                "y": 275
              },
              {
                "x": 172,
                "y": 275
              }
            ],
            "confidence": 0.739
          }
        ]
      },
      {
        "text": "Área cardiaca e hilos pulmonares de aspecto normal.",
        "boundingPolygon": [
          {
            "x": 40,
            "y": 275
          },
          {
            "x": 245,
            "y": 275
          },
          {
            "x": 245,
            "y": 285
          },
          {
            "x": 40,
            "y": 285
          }
        ],
        "words": [
          {
            "text": "Área",
            "boundingPolygon": [
              {
                "x": 42,
                "y": 275
              },
              {
                "x": 59,
                "y": 275
              },
              {
                "x": 59,
                "y": 285
              },
              {
                "x": 41,
                "y": 285
              }
            ],
            "confidence": 0.431
          },
          {
            "text": "cardiaca",
            "boundingPolygon": [
              {
                "x": 61,
                "y": 275
              },
              {
                "x": 94,
                "y": 276
              },
              {
                "x": 94,
                "y": 285
              },
              {
                "x": 61,
                "y": 285
              }
            ],
            "confidence": 0.951
          },
          {
            "text": "e",
            "boundingPolygon": [
              {
                "x": 96,
                "y": 276
              },
              {
                "x": 101,
                "y": 276
              },
              {
                "x": 101,
                "y": 286
              },
              {
                "x": 96,
                "y": 285
              }
            ],
            "confidence": 0.955
          },
          {
            "text": "hilos",
            "boundingPolygon": [
              {
                "x": 103,
                "y": 276
              },
              {
                "x": 121,
                "y": 276
              },
              {
                "x": 121,
                "y": 286
              },
              {
                "x": 103,
                "y": 286
              }
            ],
            "confidence": 0.989
          },
          {
            "text": "pulmonares",
            "boundingPolygon": [
              {
                "x": 123,
                "y": 276
              },
              {
                "x": 168,
                "y": 276
              },
              {
                "x": 168,
                "y": 286
              },
              {
                "x": 123,
                "y": 286
              }
            ],
            "confidence": 0.975
          },
          {
            "text": "de",
            "boundingPolygon": [
              {
                "x": 170,
                "y": 276
              },
              {
                "x": 180,
                "y": 276
              },
              {
                "x": 180,
                "y": 286
              },
              {
                "x": 170,
                "y": 286
              }
            ],
            "confidence": 0.996
          },
          {
            "text": "aspecto",
            "boundingPolygon": [
              {
                "x": 182,
                "y": 276
              },
              {
                "x": 213,
                "y": 276
              },
              {
                "x": 212,
                "y": 286
              },
              {
                "x": 182,
                "y": 286
              }
            ],
            "confidence": 0.976
          },
          {
            "text": "normal.",
            "boundingPolygon": [
              {
                "x": 215,
                "y": 276
              },
              {
                "x": 245,
                "y": 275
              },
              {
                "x": 245,
                "y": 286
              },
              {
                "x": 214,
                "y": 286
              }
            ],
            "confidence": 0.726
          }
        ]
      },
      {
        "text": "Mediastino anatómico.",
        "boundingPolygon": [
          {
            "x": 40,
            "y": 285
          },
          {
            "x": 126,
            "y": 285
          },
          {
            "x": 126,
            "y": 295
          },
          {
            "x": 40,
            "y": 295
          }
        ],
        "words": [
          {
            "text": "Mediastino",
            "boundingPolygon": [
              {
                "x": 40,
                "y": 286
              },
              {
                "x": 82,
                "y": 286
              },
              {
                "x": 82,
                "y": 295
              },
              {
                "x": 40,
                "y": 295
              }
            ],
            "confidence": 0.597
          },
          {
            "text": "anatómico.",
            "boundingPolygon": [
              {
                "x": 85,
                "y": 286
              },
              {
                "x": 127,
                "y": 286
              },
              {
                "x": 127,
                "y": 295
              },
              {
                "x": 85,
                "y": 295
              }
            ],
            "confidence": 0.626
          }
        ]
      },
      {
        "text": "Pulmões com transparência conservada.",
        "boundingPolygon": [
          {
            "x": 39,
            "y": 296
          },
          {
            "x": 196,
            "y": 296
          },
          {
            "x": 196,
            "y": 306
          },
          {
            "x": 39,
            "y": 306
          }
        ],
        "words": [
          {
            "text": "Pulmões",
            "boundingPolygon": [
              {
                "x": 40,
                "y": 296
              },
              {
                "x": 74,
                "y": 296
              },
              {
                "x": 73,
                "y": 306
              },
              {
                "x": 40,
                "y": 306
              }
            ],
            "confidence": 0.877
          },
          {
            "text": "com",
            "boundingPolygon": [
              {
                "x": 76,
                "y": 296
              },
              {
                "x": 91,
                "y": 296
              },
              {
                "x": 90,
                "y": 306
              },
              {
                "x": 75,
                "y": 306
              }
            ],
            "confidence": 0.996
          },
          {
            "text": "transparência",
            "boundingPolygon": [
              {
                "x": 94,
                "y": 296
              },
              {
                "x": 147,
                "y": 296
              },
              {
                "x": 147,
                "y": 307
              },
              {
                "x": 94,
                "y": 306
              }
            ],
            "confidence": 0.662
          },
          {
            "text": "conservada.",
            "boundingPolygon": [
              {
                "x": 149,
                "y": 296
              },
              {
                "x": 196,
                "y": 296
              },
              {
                "x": 196,
                "y": 307
              },
              {
                "x": 149,
                "y": 307
              }
            ],
            "confidence": 0.843
          }
        ]
      },
      {
        "text": "Espaços pleurais livres",
        "boundingPolygon": [
          {
            "x": 40,
            "y": 306
          },
          {
            "x": 131,
            "y": 306
          },
          {
            "x": 131,
            "y": 316
          },
          {
            "x": 40,
            "y": 317
          }
        ],
        "words": [
          {
            "text": "Espaços",
            "boundingPolygon": [
              {
                "x": 41,
                "y": 306
              },
              {
                "x": 73,
                "y": 307
              },
              {
                "x": 73,
                "y": 317
              },
              {
                "x": 41,
                "y": 317
              }
            ],
            "confidence": 0.962
          },
          {
            "text": "pleurais",
            "boundingPolygon": [
              {
                "x": 75,
                "y": 307
              },
              {
                "x": 106,
                "y": 307
              },
              {
                "x": 106,
                "y": 317
              },
              {
                "x": 75,
                "y": 317
              }
            ],
            "confidence": 0.903
          },
          {
            "text": "livres",
            "boundingPolygon": [
              {
                "x": 108,
                "y": 307
              },
              {
                "x": 130,
                "y": 307
              },
              {
                "x": 130,
                "y": 316
              },
              {
                "x": 108,
                "y": 316
              }
            ],
            "confidence": 0.85
          }
        ]
      },
      {
        "text": "Considerações:",
        "boundingPolygon": [
          {
            "x": 39,
            "y": 328
          },
          {
            "x": 103,
            "y": 327
          },
          {
            "x": 103,
            "y": 337
          },
          {
            "x": 39,
            "y": 338
          }
        ],
        "words": [
          {
            "text": "Considerações:",
            "boundingPolygon": [
              {
                "x": 41,
                "y": 328
              },
              {
                "x": 103,
                "y": 328
              },
              {
                "x": 102,
                "y": 337
              },
              {
                "x": 40,
                "y": 338
              }
            ],
            "confidence": 0.883
          }
        ]
      },
      {
        "text": "Exame radiológico de aspecto normal,",
        "boundingPolygon": [
          {
            "x": 40,
            "y": 338
          },
          {
            "x": 185,
            "y": 338
          },
          {
            "x": 185,
            "y": 348
          },
          {
            "x": 40,
            "y": 348
          }
        ],
        "words": [
          {
            "text": "Exame",
            "boundingPolygon": [
              {
                "x": 41,
                "y": 338
              },
              {
                "x": 67,
                "y": 338
              },
              {
                "x": 66,
                "y": 349
              },
              {
                "x": 40,
                "y": 349
              }
            ],
            "confidence": 0.863
          },
          {
            "text": "radiológico",
            "boundingPolygon": [
              {
                "x": 69,
                "y": 338
              },
              {
                "x": 111,
                "y": 339
              },
              {
                "x": 111,
                "y": 349
              },
              {
                "x": 68,
                "y": 349
              }
            ],
            "confidence": 0.915
          },
          {
            "text": "de",
            "boundingPolygon": [
              {
                "x": 113,
                "y": 339
              },
              {
                "x": 123,
                "y": 339
              },
              {
                "x": 123,
                "y": 349
              },
              {
                "x": 113,
                "y": 349
              }
            ],
            "confidence": 0.99
          },
          {
            "text": "aspecto",
            "boundingPolygon": [
              {
                "x": 125,
                "y": 339
              },
              {
                "x": 156,
                "y": 339
              },
              {
                "x": 156,
                "y": 349
              },
              {
                "x": 125,
                "y": 349
              }
            ],
            "confidence": 0.975
          },
          {
            "text": "normal,",
            "boundingPolygon": [
              {
                "x": 158,
                "y": 339
              },
              {
                "x": 186,
                "y": 339
              },
              {
                "x": 186,
                "y": 349
              },
              {
                "x": 158,
                "y": 349
              }
            ],
            "confidence": 0.693
          }
        ]
      },
      {
        "text": "Ananindeua, 14 de dezembro de 2022.",
        "boundingPolygon": [
          {
            "x": 282,
            "y": 454
          },
          {
            "x": 415,
            "y": 454
          },
          {
            "x": 415,
            "y": 464
          },
          {
            "x": 282,
            "y": 464
          }
        ],
        "words": [
          {
            "text": "Ananindeua,",
            "boundingPolygon": [
              {
                "x": 283,
                "y": 455
              },
              {
                "x": 326,
                "y": 455
              },
              {
                "x": 325,
                "y": 465
              },
              {
                "x": 283,
                "y": 465
              }
            ],
            "confidence": 0.672
          },
          {
            "text": "14",
            "boundingPolygon": [
              {
                "x": 328,
                "y": 455
              },
              {
                "x": 335,
                "y": 455
              },
              {
                "x": 335,
                "y": 465
              },
              {
                "x": 327,
                "y": 465
              }
            ],
            "confidence": 0.992
          },
          {
            "text": "de",
            "boundingPolygon": [
              {
                "x": 337,
                "y": 455
              },
              {
                "x": 346,
                "y": 455
              },
              {
                "x": 346,
                "y": 465
              },
              {
                "x": 336,
                "y": 465
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "dezembro",
            "boundingPolygon": [
              {
                "x": 348,
                "y": 455
              },
              {
                "x": 381,
                "y": 455
              },
              {
                "x": 380,
                "y": 465
              },
              {
                "x": 347,
                "y": 465
              }
            ],
            "confidence": 0.925
          },
          {
            "text": "de",
            "boundingPolygon": [
              {
                "x": 383,
                "y": 455
              },
              {
                "x": 392,
                "y": 455
              },
              {
                "x": 391,
                "y": 465
              },
              {
                "x": 382,
                "y": 465
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "2022.",
            "boundingPolygon": [
              {
                "x": 394,
                "y": 455
              },
              {
                "x": 415,
                "y": 455
              },
              {
                "x": 415,
                "y": 465
              },
              {
                "x": 393,
                "y": 465
              }
            ],
            "confidence": 0.882
          }
        ]
      },
      {
        "text": "Dr. Médico Mais Laudo",
        "boundingPolygon": [
          {
            "x": 274,
            "y": 514
          },
          {
            "x": 356,
            "y": 514
          },
          {
            "x": 356,
            "y": 525
          },
          {
            "x": 274,
            "y": 524
          }
        ],
        "words": [
          {
            "text": "Dr.",
            "boundingPolygon": [
              {
                "x": 275,
                "y": 515
              },
              {
                "x": 285,
                "y": 515
              },
              {
                "x": 285,
                "y": 525
              },
              {
                "x": 275,
                "y": 525
              }
            ],
            "confidence": 0.983
          },
          {
            "text": "Médico",
            "boundingPolygon": [
              {
                "x": 287,
                "y": 515
              },
              {
                "x": 312,
                "y": 515
              },
              {
                "x": 312,
                "y": 525
              },
              {
                "x": 287,
                "y": 525
              }
            ],
            "confidence": 0.76
          },
          {
            "text": "Mais",
            "boundingPolygon": [
              {
                "x": 314,
                "y": 515
              },
              {
                "x": 331,
                "y": 515
              },
              {
                "x": 330,
                "y": 525
              },
              {
                "x": 314,
                "y": 525
              }
            ],
            "confidence": 0.956
          },
          {
            "text": "Laudo",
            "boundingPolygon": [
              {
                "x": 333,
                "y": 515
              },
              {
                "x": 356,
                "y": 515
              },
              {
                "x": 355,
                "y": 526
              },
              {
                "x": 332,
                "y": 525
              }
            ],
            "confidence": 0.993
          }
        ]
      },
      {
        "text": "CRM WWW - SP/ ROE: VVVV - Radiologista",
        "boundingPolygon": [
          {
            "x": 270,
            "y": 527
          },
          {
            "x": 425,
            "y": 528
          },
          {
            "x": 425,
            "y": 539
          },
          {
            "x": 270,
            "y": 538
          }
        ],
        "words": [
          {
            "text": "CRM",
            "boundingPolygon": [
              {
                "x": 271,
                "y": 528
              },
              {
                "x": 287,
                "y": 528
              },
              {
                "x": 288,
                "y": 539
              },
              {
                "x": 271,
                "y": 539
              }
            ],
            "confidence": 0.977
          },
          {
            "text": "WWW",
            "boundingPolygon": [
              {
                "x": 290,
                "y": 528
              },
              {
                "x": 306,
                "y": 528
              },
              {
                "x": 306,
                "y": 539
              },
              {
                "x": 291,
                "y": 539
              }
            ],
            "confidence": 0.186
          },
          {
            "text": "-",
            "boundingPolygon": [
              {
                "x": 312,
                "y": 528
              },
              {
                "x": 316,
                "y": 528
              },
              {
                "x": 316,
                "y": 539
              },
              {
                "x": 313,
                "y": 539
              }
            ],
            "confidence": 0.371
          },
          {
            "text": "SP/",
            "boundingPolygon": [
              {
                "x": 318,
                "y": 528
              },
              {
                "x": 332,
                "y": 528
              },
              {
                "x": 332,
                "y": 539
              },
              {
                "x": 318,
                "y": 539
              }
            ],
            "confidence": 0.938
          },
          {
            "text": "ROE:",
            "boundingPolygon": [
              {
                "x": 334,
                "y": 528
              },
              {
                "x": 352,
                "y": 528
              },
              {
                "x": 352,
                "y": 539
              },
              {
                "x": 334,
                "y": 539
              }
            ],
            "confidence": 0.779
          },
          {
            "text": "VVVV",
            "boundingPolygon": [
              {
                "x": 354,
                "y": 528
              },
              {
                "x": 374,
                "y": 528
              },
              {
                "x": 375,
                "y": 539
              },
              {
                "x": 354,
                "y": 539
              }
            ],
            "confidence": 0.597
          },
          {
            "text": "-",
            "boundingPolygon": [
              {
                "x": 377,
                "y": 528
              },
              {
                "x": 380,
                "y": 528
              },
              {
                "x": 380,
                "y": 539
              },
              {
                "x": 377,
                "y": 539
              }
            ],
            "confidence": 0.655
          },
          {
            "text": "Radiologista",
            "boundingPolygon": [
              {
                "x": 382,
                "y": 529
              },
              {
                "x": 425,
                "y": 529
              },
              {
                "x": 425,
                "y": 539
              },
              {
                "x": 382,
                "y": 539
              }
            ],
            "confidence": 0.789
          }
        ]
      },
      {
        "text": "Para validar este documento acesse: app maislaudo.com.be/Valideseulaudo e informe o loken:xxxxxcon",
        "boundingPolygon": [
          {
            "x": 41,
            "y": 637
          },
          {
            "x": 399,
            "y": 637
          },
          {
            "x": 399,
            "y": 647
          },
          {
            "x": 41,
            "y": 648
          }
        ],
        "words": [
          {
            "text": "Para",
            "boundingPolygon": [
              {
                "x": 42,
                "y": 638
              },
              {
                "x": 57,
                "y": 638
              },
              {
                "x": 57,
                "y": 648
              },
              {
                "x": 42,
                "y": 648
              }
            ],
            "confidence": 0.999
          },
          {
            "text": "validar",
            "boundingPolygon": [
              {
                "x": 59,
                "y": 638
              },
              {
                "x": 82,
                "y": 638
              },
              {
                "x": 82,
                "y": 648
              },
              {
                "x": 59,
                "y": 648
              }
            ],
            "confidence": 0.999
          },
          {
            "text": "este",
            "boundingPolygon": [
              {
                "x": 84,
                "y": 638
              },
              {
                "x": 98,
                "y": 638
              },
              {
                "x": 98,
                "y": 648
              },
              {
                "x": 84,
                "y": 648
              }
            ],
            "confidence": 1
          },
          {
            "text": "documento",
            "boundingPolygon": [
              {
                "x": 100,
                "y": 638
              },
              {
                "x": 137,
                "y": 638
              },
              {
                "x": 137,
                "y": 648
              },
              {
                "x": 100,
                "y": 648
              }
            ],
            "confidence": 1
          },
          {
            "text": "acesse:",
            "boundingPolygon": [
              {
                "x": 139,
                "y": 638
              },
              {
                "x": 165,
                "y": 637
              },
              {
                "x": 165,
                "y": 648
              },
              {
                "x": 139,
                "y": 648
              }
            ],
            "confidence": 0.993
          },
          {
            "text": "app",
            "boundingPolygon": [
              {
                "x": 167,
                "y": 637
              },
              {
                "x": 179,
                "y": 637
              },
              {
                "x": 179,
                "y": 648
              },
              {
                "x": 167,
                "y": 648
              }
            ],
            "confidence": 0.998
          },
          {
            "text": "maislaudo.com.be/Valideseulaudo",
            "boundingPolygon": [
              {
                "x": 181,
                "y": 637
              },
              {
                "x": 295,
                "y": 637
              },
              {
                "x": 295,
                "y": 648
              },
              {
                "x": 181,
                "y": 648
              }
            ],
            "confidence": 0.166
          },
          {
            "text": "e",
            "boundingPolygon": [
              {
                "x": 297,
                "y": 637
              },
              {
                "x": 301,
                "y": 637
              },
              {
                "x": 300,
                "y": 648
              },
              {
                "x": 297,
                "y": 648
              }
            ],
            "confidence": 1
          },
          {
            "text": "informe",
            "boundingPolygon": [
              {
                "x": 303,
                "y": 637
              },
              {
                "x": 328,
                "y": 637
              },
              {
                "x": 328,
                "y": 648
              },
              {
                "x": 302,
                "y": 648
              }
            ],
            "confidence": 0.999
          },
          {
            "text": "o",
            "boundingPolygon": [
              {
                "x": 330,
                "y": 637
              },
              {
                "x": 334,
                "y": 637
              },
              {
                "x": 334,
                "y": 648
              },
              {
                "x": 330,
                "y": 648
              }
            ],
            "confidence": 0.999
          },
          {
            "text": "loken:xxxxxcon",
            "boundingPolygon": [
              {
                "x": 336,
                "y": 637
              },
              {
                "x": 398,
                "y": 637
              },
              {
                "x": 398,
                "y": 648
              },
              {
                "x": 336,
                "y": 648
              }
            ],
            "confidence": 0.064
          }
        ]
      }
    ]
  }
]
````





















