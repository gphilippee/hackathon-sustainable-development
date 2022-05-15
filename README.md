# Hackathon ODD

https://github.com/Garage-ISEP/hackathon-ia-developpement-durable

**Quelle méthode pour identifier les cibles ODD (Objectifs de Développement Durable) dans un texte?**

- ODD 12 : « Consommation et production responsables » (11 cibles)
https://sdgs.un.org/goals/goal12
- ODD 15 : « Vie terrestre » (12 cibles)
https://sdgs.un.org/goals/goal15
- ODD 16 : « Paix, justice et institutions efficaces » (12 cibles)
https://sdgs.un.org/goals/goal16

## Ressources

* OSDG Data (https://github.com/osdg-ai/osdg-data)
* Benchmarking Zero-shot Text Classification: Datasets, Evaluation and Entailment Approach
Wenpeng Yin, Jamaal Hay, Dan Roth 2019 (https://arxiv.org/abs/1909.00161)
* HF DistilBART MNLI (https://huggingface.co/valhalla/distilbart-mnli-12-9)

## Results

### Highest score

```shell
               precision    recall  f1-score   support
               
        12.1       0.00      0.00      0.00         0
        12.2       0.00      0.00      0.00         1
        12.3       0.00      0.00      0.00         2
        12.4       0.63      0.44      0.52        27
        12.5       0.17      0.09      0.12        11
        12.6       0.00      0.00      0.00         0
        12.7       0.00      0.00      0.00         1
        12.8       0.00      0.00      0.00         0
        12.a       0.00      0.00      0.00         2
        12.b       0.00      0.00      0.00         0
        12.c       0.00      0.00      0.00         0
        15.1       0.30      0.20      0.24        15
        15.2       1.00      0.17      0.29         6
        15.3       0.00      0.00      0.00         4
        15.4       0.00      0.00      0.00         0
        15.5       0.00      0.00      0.00         7
        15.6       0.00      0.00      0.00         4
        15.7       0.00      0.00      0.00         0
        15.8       0.00      0.00      0.00         0
        15.9       0.00      0.00      0.00         0
        15.a       0.00      0.00      0.00         0
        15.b       0.00      0.00      0.00         0
        15.c       0.00      0.00      0.00         0
        16.1       0.00      0.00      0.00         4
        16.2       0.00      0.00      0.00         0
        16.3       0.00      0.00      0.00         1
        16.4       0.00      0.00      0.00         0
        16.5       0.67      0.20      0.31        10
        16.6       0.28      0.50      0.36        10
        16.7       0.36      0.57      0.44         7
        16.8       0.00      0.00      0.00         0
        16.9       0.00      0.00      0.00         0
       16.10       0.00      0.00      0.00         1
        16.a       0.00      0.00      0.00         5
           0       0.00      0.00      0.00        31

   micro avg       0.19      0.19      0.19       149
   macro avg       0.10      0.06      0.06       149
weighted avg       0.28      0.19      0.20       149
```

![output](https://user-images.githubusercontent.com/55877031/168450966-34b32ab6-681b-4f80-b5d9-006f141c186f.png)

### Top 3 highest score

```shell
               precision    recall  f1-score   support

        12.1       0.00      0.00      0.00         0
        12.2       0.02      1.00      0.05         1
        12.3       0.00      0.00      0.00         2
        12.4       0.87      0.74      0.80        27
        12.5       0.78      0.64      0.70        11
        12.6       0.00      0.00      0.00         0
        12.7       0.50      1.00      0.67         1
        12.8       0.00      0.00      0.00         0
        12.a       1.00      0.50      0.67         2
        12.b       0.00      0.00      0.00         0
        12.c       0.00      0.00      0.00         0
        15.1       0.62      0.53      0.57        15
        15.2       1.00      0.17      0.29         6
        15.3       1.00      0.25      0.40         4
        15.4       0.00      0.00      0.00         0
        15.5       0.55      0.86      0.67         7
        15.6       0.00      0.00      0.00         4
        15.7       0.00      0.00      0.00         0
        15.8       0.00      0.00      0.00         0
        15.9       0.00      0.00      0.00         0
        15.a       0.00      0.00      0.00         0
        15.b       0.00      0.00      0.00         0
        15.c       0.00      0.00      0.00         0
        16.1       0.00      0.00      0.00         4
        16.2       0.00      0.00      0.00         0
        16.3       0.00      0.00      0.00         1
        16.4       0.00      0.00      0.00         0
        16.5       0.83      0.50      0.62        10
        16.6       0.50      0.90      0.64        10
        16.7       0.56      0.71      0.63         7
        16.8       0.00      0.00      0.00         0
        16.9       0.00      0.00      0.00         0
       16.10       0.25      1.00      0.40         1
        16.a       1.00      0.20      0.33         5
           0       0.00      0.00      0.00        31

   micro avg       0.45      0.45      0.45       149
   macro avg       0.27      0.26      0.21       149
weighted avg       0.54      0.45      0.45       149
```

<img width="877" alt="Capture d’écran 2022-05-15 à 01 11 25" src="https://user-images.githubusercontent.com/55877031/168461695-d39078ee-bbb5-4c8a-97c5-3da1cdbbf367.png">

### Top 5 highest score

```shell
               precision    recall  f1-score   support

        12.1       0.00      0.00      0.00         0
        12.2       0.03      1.00      0.06         1
        12.3       0.00      0.00      0.00         2
        12.4       0.96      0.85      0.90        27
        12.5       0.82      0.82      0.82        11
        12.6       0.00      0.00      0.00         0
        12.7       0.50      1.00      0.67         1
        12.8       0.00      0.00      0.00         0
        12.a       1.00      0.50      0.67         2
        12.b       0.00      0.00      0.00         0
        12.c       0.00      0.00      0.00         0
        15.1       0.74      0.93      0.82        15
        15.2       1.00      0.50      0.67         6
        15.3       1.00      0.25      0.40         4
        15.4       0.00      0.00      0.00         0
        15.5       0.78      1.00      0.88         7
        15.6       1.00      0.25      0.40         4
        15.7       0.00      0.00      0.00         0
        15.8       0.00      0.00      0.00         0
        15.9       0.00      0.00      0.00         0
        15.a       0.00      0.00      0.00         0
        15.b       0.00      0.00      0.00         0
        15.c       0.00      0.00      0.00         0
        16.1       0.00      0.00      0.00         4
        16.2       0.00      0.00      0.00         0
        16.3       0.00      0.00      0.00         1
        16.4       0.00      0.00      0.00         0
        16.5       0.89      0.80      0.84        10
        16.6       0.53      0.90      0.67        10
        16.7       0.56      0.71      0.63         7
        16.8       0.00      0.00      0.00         0
        16.9       0.00      0.00      0.00         0
       16.10       0.25      1.00      0.40         1
        16.a       1.00      0.20      0.33         5
           0       0.00      0.00      0.00        31

   micro avg       0.57      0.57      0.57       149
   macro avg       0.32      0.31      0.26       149
weighted avg       0.61      0.57      0.55       149
```

<img width="868" alt="Capture d’écran 2022-05-15 à 01 12 04" src="https://user-images.githubusercontent.com/55877031/168461699-176c0314-b8dc-4209-9516-0724a881906e.png">
