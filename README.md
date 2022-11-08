# Dataset - Modelos Preditivos Conexionistas 2022.01

### Afonso Isaque Araujo de Souza 

|**Tipo de Projeto**|**Qtde de imagens por classe**|**Qtde de classes**|
|--|--|--|
| Deteção de Objetos | =>75 | 4 |

### Informações Adicionais

A ideia é que fosse algo ligado a alguma aplicação real. Desse modo, foram escolhidos 4 tipos de EPI's (equipamento de proteção individual) de modo que o algoritmo consiga fazer a identificação desses objetos em imagens. Sendo EPI algo de utilização obrigatória em alguns ambientes e a última barreira de proteção entre um individuo e um acidente, que fosse possivel identificar/fiscalizar a utilização dele através deste modelo.


# Projeto Final - Modelos Preditivos Conexionistas

### Afonso Isaque Araujo de Souza


|**Deteção de Objetos**|**YOLOv5**|**PyTorch**|

## Performance

O modelo treinado possui performance de **88,88%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
     Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      0/999       3.7G     0.1184    0.01227    0.04996         57        320: 100% 4/4 [00:04<00:00,  1.11s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.66s/it]
                   all         63         79    0.00137      0.412    0.00204   0.000538
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      1/999       3.7G     0.1162    0.01135    0.04884         43        320: 100% 4/4 [00:01<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.30it/s]
                   all         63         79    0.00157      0.453    0.00298   0.000714
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      2/999       3.7G     0.1088    0.01367    0.04802         58        320: 100% 4/4 [00:01<00:00,  3.21it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.60it/s]
                   all         63         79    0.00171      0.463    0.00346   0.000827
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      3/999       3.7G     0.1021    0.01303    0.04592         40        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.55it/s]
                   all         63         79    0.00196      0.524    0.00781    0.00205
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      4/999       3.7G    0.09578    0.01455    0.04389         37        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.17it/s]
                   all         63         79    0.00262      0.622     0.0153    0.00406
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      5/999       3.7G    0.09207    0.01574    0.04212         51        320: 100% 4/4 [00:01<00:00,  3.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.69it/s]
                   all         63         79    0.00308      0.702     0.0209    0.00561
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      6/999       3.7G    0.08684    0.01648    0.04012         50        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.71it/s]
                   all         63         79      0.003      0.712     0.0421     0.0132
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      7/999       3.7G    0.08208    0.01776    0.03693         58        320: 100% 4/4 [00:01<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.76it/s]
                   all         63         79    0.00307      0.728     0.0786     0.0233
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      8/999       3.7G    0.07702    0.01784    0.03646         48        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.74it/s]
                   all         63         79     0.0389       0.38     0.0402      0.011
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      9/999       3.7G    0.07327    0.01717    0.03632         44        320: 100% 4/4 [00:01<00:00,  2.78it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.03it/s]
                   all         63         79       0.35      0.154      0.124     0.0333
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     10/999       3.7G    0.06711    0.01927    0.03058         45        320: 100% 4/4 [00:01<00:00,  3.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.29it/s]
                   all         63         79     0.0174      0.753     0.0583     0.0166
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     11/999       3.7G    0.06524    0.01799    0.03057         44        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.64it/s]
                   all         63         79      0.311      0.589      0.141      0.053
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     12/999       3.7G     0.0622    0.01742    0.02997         41        320: 100% 4/4 [00:01<00:00,  3.61it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.53it/s]
                   all         63         79       0.41      0.391      0.208     0.0788
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     13/999       3.7G    0.05742    0.01678    0.02722         35        320: 100% 4/4 [00:01<00:00,  3.53it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.69it/s]
                   all         63         79      0.377      0.453      0.226     0.0802
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     14/999       3.7G    0.05694    0.01705      0.028         43        320: 100% 4/4 [00:01<00:00,  3.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.59it/s]
                   all         63         79      0.428      0.302      0.283     0.0948
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     15/999       3.7G     0.0589    0.01785     0.0264         45        320: 100% 4/4 [00:01<00:00,  3.43it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.71it/s]
                   all         63         79      0.496      0.329      0.374      0.143
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     16/999       3.7G    0.05711      0.018    0.02645         60        320: 100% 4/4 [00:01<00:00,  3.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.21it/s]
                   all         63         79       0.57      0.286      0.389       0.17
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     17/999       3.7G    0.05642    0.01587    0.02633         41        320: 100% 4/4 [00:01<00:00,  3.60it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.49it/s]
                   all         63         79      0.692      0.328      0.392      0.132
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     18/999       3.7G    0.05616    0.01635    0.02279         51        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79      0.727      0.331      0.303     0.0887
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     19/999       3.7G    0.05826     0.0165    0.02447         51        320: 100% 4/4 [00:01<00:00,  3.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.81it/s]
                   all         63         79      0.731      0.397      0.409      0.181
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     20/999       3.7G     0.0556     0.0149    0.02414         43        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.58it/s]
                   all         63         79      0.242      0.612      0.432      0.189
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     21/999       3.7G    0.05407    0.01566    0.02179         52        320: 100% 4/4 [00:01<00:00,  3.56it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.50it/s]
                   all         63         79       0.53      0.583      0.491      0.233
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     22/999       3.7G    0.05391    0.01485    0.01996         50        320: 100% 4/4 [00:01<00:00,  3.95it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.16it/s]
                   all         63         79      0.508       0.69      0.548      0.227
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     23/999       3.7G    0.05292    0.01403    0.01912         44        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.93it/s]
                   all         63         79      0.458      0.721       0.63      0.255
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     24/999       3.7G    0.05174    0.01327    0.02028         34        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.89it/s]
                   all         63         79      0.291      0.634      0.457      0.164
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     25/999       3.7G    0.05369    0.01239    0.02156         51        320: 100% 4/4 [00:01<00:00,  2.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.43it/s]
                   all         63         79      0.511      0.762       0.64      0.241
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     26/999       3.7G    0.05003    0.01428    0.02012         46        320: 100% 4/4 [00:01<00:00,  2.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.12it/s]
                   all         63         79      0.538      0.792      0.655      0.297
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     27/999       3.7G    0.04927    0.01373    0.02039         40        320: 100% 4/4 [00:01<00:00,  2.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.69it/s]
                   all         63         79      0.528      0.755      0.594      0.281
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     28/999       3.7G    0.04708    0.01292    0.02035         42        320: 100% 4/4 [00:01<00:00,  2.53it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.27it/s]
                   all         63         79      0.504      0.533      0.582      0.282
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     29/999       3.7G    0.04836    0.01308    0.02051         44        320: 100% 4/4 [00:01<00:00,  3.99it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.10it/s]
                   all         63         79      0.707      0.493       0.48       0.21
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     30/999       3.7G    0.04621    0.01289    0.01796         48        320: 100% 4/4 [00:01<00:00,  3.94it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.27it/s]
                   all         63         79      0.462      0.481      0.525      0.224
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     31/999       3.7G    0.04658    0.01173    0.01945         41        320: 100% 4/4 [00:01<00:00,  3.57it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.68it/s]
                   all         63         79      0.475      0.456      0.488      0.212
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     32/999       3.7G    0.04415    0.01262    0.02076         58        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.91it/s]
                   all         63         79      0.857      0.505        0.6       0.25
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     33/999       3.7G    0.04508    0.01251    0.01887         43        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.94it/s]
                   all         63         79      0.413      0.544      0.548      0.225
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     34/999       3.7G    0.04707    0.01258    0.01814         36        320: 100% 4/4 [00:01<00:00,  3.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.73it/s]
                   all         63         79      0.695      0.378      0.354      0.135
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     35/999       3.7G    0.04418    0.01247    0.01686         50        320: 100% 4/4 [00:01<00:00,  3.60it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.93it/s]
                   all         63         79      0.649      0.437      0.424       0.21
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     36/999       3.7G    0.04264    0.01183    0.01503         45        320: 100% 4/4 [00:01<00:00,  3.54it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.96it/s]
                   all         63         79       0.58      0.648      0.689      0.359
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     37/999       3.7G    0.04287    0.01158    0.01787         48        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.99it/s]
                   all         63         79      0.672      0.748      0.731      0.415
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     38/999       3.7G    0.04367    0.01096    0.02048         38        320: 100% 4/4 [00:01<00:00,  3.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79       0.73      0.549       0.64       0.29
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     39/999       3.7G    0.04276    0.01236    0.01529         41        320: 100% 4/4 [00:01<00:00,  3.63it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.66it/s]
                   all         63         79      0.779      0.555      0.626      0.311
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     40/999       3.7G    0.04334    0.01269    0.01842         55        320: 100% 4/4 [00:01<00:00,  3.54it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.89it/s]
                   all         63         79      0.563      0.748      0.683      0.345
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     41/999       3.7G    0.04083    0.01121     0.0178         51        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.725      0.716      0.756        0.4
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     42/999       3.7G    0.04203    0.01167    0.01713         57        320: 100% 4/4 [00:01<00:00,  3.69it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.47it/s]
                   all         63         79       0.79      0.725      0.719      0.362
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     43/999       3.7G    0.03934    0.01247    0.01464         46        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.58it/s]
                   all         63         79      0.729      0.712      0.737      0.356
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     44/999       3.7G     0.0411    0.01209    0.01408         53        320: 100% 4/4 [00:01<00:00,  3.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.81it/s]
                   all         63         79      0.814      0.548      0.617      0.345
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     45/999       3.7G    0.04063    0.01097    0.01854         50        320: 100% 4/4 [00:01<00:00,  3.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.487      0.481      0.518      0.273
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     46/999       3.7G    0.03881    0.01066    0.01717         33        320: 100% 4/4 [00:01<00:00,  3.61it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.62it/s]
                   all         63         79       0.55      0.551      0.573      0.288
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     47/999       3.7G    0.03863    0.01169    0.01732         40        320: 100% 4/4 [00:01<00:00,  3.57it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.86it/s]
                   all         63         79      0.636      0.552      0.588      0.304
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     48/999       3.7G    0.03845    0.01193    0.01755         54        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.95it/s]
                   all         63         79      0.899      0.567      0.617      0.322
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     49/999       3.7G    0.03963    0.01058    0.01903         57        320: 100% 4/4 [00:01<00:00,  3.58it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.86it/s]
                   all         63         79      0.863      0.565      0.595      0.274
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     50/999       3.7G    0.03827    0.01192    0.01732         54        320: 100% 4/4 [00:01<00:00,  3.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.00it/s]
                   all         63         79      0.806      0.587      0.638      0.336
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     51/999       3.7G    0.03815     0.0108    0.01629         35        320: 100% 4/4 [00:01<00:00,  3.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.08it/s]
                   all         63         79      0.799      0.547      0.589      0.275
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     52/999       3.7G    0.03895    0.01251     0.0165         60        320: 100% 4/4 [00:01<00:00,  3.53it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.00it/s]
                   all         63         79      0.809      0.528      0.528      0.242
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     53/999       3.7G    0.03974    0.01028    0.01732         36        320: 100% 4/4 [00:01<00:00,  3.78it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.38it/s]
                   all         63         79      0.791      0.513      0.537      0.302
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     54/999       3.7G    0.03665    0.01177    0.01562         54        320: 100% 4/4 [00:01<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79      0.878      0.568      0.608      0.333
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     55/999       3.7G    0.03688    0.01151    0.01362         51        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.87it/s]
                   all         63         79      0.694      0.632      0.667      0.374
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     56/999       3.7G    0.03722    0.01117    0.01361         49        320: 100% 4/4 [00:01<00:00,  3.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.96it/s]
                   all         63         79      0.815      0.687      0.739      0.422
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     57/999       3.7G    0.03609    0.01198    0.01505         65        320: 100% 4/4 [00:01<00:00,  3.53it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.94it/s]
                   all         63         79      0.887      0.547      0.623      0.335
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     58/999       3.7G    0.03765    0.01232    0.01231         66        320: 100% 4/4 [00:01<00:00,  3.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.75it/s]
                   all         63         79      0.667      0.543      0.608      0.344
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     59/999       3.7G    0.03771    0.01125    0.01473         47        320: 100% 4/4 [00:01<00:00,  3.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.00it/s]
                   all         63         79      0.796      0.703      0.758      0.425
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     60/999       3.7G    0.03688    0.01088     0.0151         51        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.86it/s]
                   all         63         79      0.899      0.739      0.755      0.402
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     61/999       3.7G    0.03712    0.01158    0.01398         57        320: 100% 4/4 [00:01<00:00,  3.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.96it/s]
                   all         63         79      0.696      0.674      0.685      0.373
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     62/999       3.7G    0.03418    0.01168    0.01443         49        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.11it/s]
                   all         63         79      0.674       0.61      0.662      0.339
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     63/999       3.7G    0.03696    0.01017    0.01614         46        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.74it/s]
                   all         63         79      0.622      0.586      0.595      0.295
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     64/999       3.7G    0.03575     0.0106    0.01321         50        320: 100% 4/4 [00:01<00:00,  3.62it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.46it/s]
                   all         63         79      0.777      0.608      0.654      0.356
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     65/999       3.7G    0.03876    0.01144    0.01624         55        320: 100% 4/4 [00:01<00:00,  3.80it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.54it/s]
                   all         63         79      0.799      0.635      0.673      0.367
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     66/999       3.7G    0.03663    0.01035     0.0145         41        320: 100% 4/4 [00:01<00:00,  3.43it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.82it/s]
                   all         63         79      0.807      0.774      0.791      0.462
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     67/999       3.7G    0.03677    0.01118    0.01318         43        320: 100% 4/4 [00:01<00:00,  3.90it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.30it/s]
                   all         63         79      0.923      0.631      0.711      0.413
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     68/999       3.7G    0.03444    0.01127    0.01413         53        320: 100% 4/4 [00:01<00:00,  3.71it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.77it/s]
                   all         63         79      0.736      0.672      0.726       0.41
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     69/999       3.7G    0.03486     0.0102    0.01509         58        320: 100% 4/4 [00:01<00:00,  3.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.95it/s]
                   all         63         79       0.78      0.648      0.683      0.394
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     70/999       3.7G    0.03431    0.01069    0.01736         47        320: 100% 4/4 [00:01<00:00,  3.55it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79       0.81      0.637      0.677      0.389
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     71/999       3.7G    0.03664    0.01105    0.01376         54        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.781      0.673       0.72      0.381
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     72/999       3.7G    0.03491    0.01118    0.01293         57        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.81it/s]
                   all         63         79      0.826      0.686      0.732      0.422
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     73/999       3.7G    0.03601    0.01105    0.01613         48        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79      0.704      0.625      0.647      0.371
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     74/999       3.7G    0.03511     0.0107    0.01489         50        320: 100% 4/4 [00:01<00:00,  3.96it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.10it/s]
                   all         63         79      0.851      0.762        0.8      0.407
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     75/999       3.7G    0.03464     0.0116      0.014         56        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.89it/s]
                   all         63         79      0.859      0.762      0.826      0.463
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     76/999       3.7G    0.03588    0.01029    0.01277         34        320: 100% 4/4 [00:01<00:00,  3.67it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.58it/s]
                   all         63         79      0.812      0.726      0.758        0.4
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     77/999       3.7G    0.03537    0.01069    0.01464         52        320: 100% 4/4 [00:01<00:00,  3.63it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.52it/s]
                   all         63         79      0.767      0.703      0.707      0.423
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     78/999       3.7G    0.03332    0.01113    0.01442         58        320: 100% 4/4 [00:01<00:00,  3.79it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.49it/s]
                   all         63         79      0.768      0.756      0.787      0.454
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     79/999       3.7G    0.03365    0.01076    0.01292         39        320: 100% 4/4 [00:01<00:00,  3.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.85it/s]
                   all         63         79      0.773      0.761      0.817      0.474
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     80/999       3.7G    0.03286    0.01115    0.01297         61        320: 100% 4/4 [00:01<00:00,  3.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.87it/s]
                   all         63         79       0.72      0.772      0.786      0.483
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     81/999       3.7G     0.0335    0.01101    0.01439         49        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.796      0.815      0.786      0.461
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     82/999       3.7G    0.03255    0.01032    0.01502         37        320: 100% 4/4 [00:01<00:00,  3.82it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.61it/s]
                   all         63         79      0.753      0.702      0.695      0.405
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     83/999       3.7G    0.03319   0.009696     0.0151         39        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.796      0.739      0.735      0.427
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     84/999       3.7G    0.03313    0.01074    0.01365         49        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.75it/s]
                   all         63         79      0.808      0.818      0.806      0.493
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     85/999       3.7G    0.03205    0.01039    0.01536         49        320: 100% 4/4 [00:01<00:00,  3.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.89it/s]
                   all         63         79      0.826      0.832      0.823      0.513
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     86/999       3.7G    0.03317    0.00968    0.01549         40        320: 100% 4/4 [00:01<00:00,  3.60it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.61it/s]
                   all         63         79      0.756      0.723      0.753      0.425
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     87/999       3.7G    0.03353    0.01049    0.01454         53        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79      0.816      0.752      0.769      0.457
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     88/999       3.7G    0.03266    0.01011    0.01602         46        320: 100% 4/4 [00:01<00:00,  3.73it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.36it/s]
                   all         63         79      0.829       0.76       0.77      0.493
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     89/999       3.7G    0.03302    0.01066    0.01606         45        320: 100% 4/4 [00:01<00:00,  3.61it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.63it/s]
                   all         63         79      0.861      0.719       0.74      0.444
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     90/999       3.7G    0.03022   0.009387    0.01548         42        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.91it/s]
                   all         63         79      0.908      0.594      0.692      0.421
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     91/999       3.7G     0.0315   0.009677    0.01641         36        320: 100% 4/4 [00:01<00:00,  3.58it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.66it/s]
                   all         63         79      0.767      0.707       0.76      0.429
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     92/999       3.7G    0.03131    0.01022    0.01357         50        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.733      0.696      0.735      0.421
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     93/999       3.7G    0.03175   0.009989    0.01489         48        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.84it/s]
                   all         63         79      0.866      0.619       0.66      0.368
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     94/999       3.7G    0.03265   0.009757    0.01446         37        320: 100% 4/4 [00:01<00:00,  3.54it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.95it/s]
                   all         63         79      0.779      0.623      0.673      0.402
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     95/999       3.7G     0.0326   0.009884    0.01612         45        320: 100% 4/4 [00:01<00:00,  3.78it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.33it/s]
                   all         63         79      0.809      0.777      0.773      0.454
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     96/999       3.7G    0.03062    0.01045    0.01494         53        320: 100% 4/4 [00:01<00:00,  3.75it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.13it/s]
                   all         63         79      0.785      0.829       0.81      0.412
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     97/999       3.7G    0.03177    0.01098    0.01179         65        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.06it/s]
                   all         63         79      0.746      0.792      0.783      0.477
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     98/999       3.7G    0.03297     0.0105    0.01736         37        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.89it/s]
                   all         63         79      0.814      0.736      0.775      0.477
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     99/999       3.7G     0.0328    0.01075    0.01252         56        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         63         79      0.857      0.706      0.759      0.413
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    100/999       3.7G    0.03043    0.01031    0.01469         54        320: 100% 4/4 [00:01<00:00,  2.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.87it/s]
                   all         63         79      0.779      0.635      0.696       0.41
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    101/999       3.7G    0.03226    0.01007    0.01636         57        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.79it/s]
                   all         63         79      0.719      0.618      0.665      0.371
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    102/999       3.7G    0.03106    0.01015    0.01309         42        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.04it/s]
                   all         63         79      0.807      0.798      0.817      0.458
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    103/999       3.7G    0.03231     0.0105     0.0128         58        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.10it/s]
                   all         63         79      0.814       0.65      0.694      0.406
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    104/999       3.7G     0.0293    0.00953     0.0149         47        320: 100% 4/4 [00:01<00:00,  3.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.791      0.713      0.792      0.453
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    105/999       3.7G    0.02899   0.009481    0.01501         43        320: 100% 4/4 [00:01<00:00,  3.86it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.29it/s]
                   all         63         79      0.813      0.741      0.799      0.424
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    106/999       3.7G    0.02872   0.009048     0.0148         46        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.83it/s]
                   all         63         79      0.802      0.723      0.732      0.408
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    107/999       3.7G    0.02954   0.009436    0.01387         53        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.84it/s]
                   all         63         79      0.823      0.753      0.765      0.453
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    108/999       3.7G    0.03131    0.01035     0.0141         59        320: 100% 4/4 [00:01<00:00,  3.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.84it/s]
                   all         63         79      0.859      0.784      0.802      0.473
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    109/999       3.7G    0.03041     0.0106    0.01417         65        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.99it/s]
                   all         63         79       0.82      0.777      0.801      0.479
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    110/999       3.7G    0.02995   0.009238    0.01203         48        320: 100% 4/4 [00:01<00:00,  3.10it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.85it/s]
                   all         63         79      0.821        0.8      0.806      0.499
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    111/999       3.7G    0.03117   0.009663    0.01159         57        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.89it/s]
                   all         63         79      0.827      0.808      0.834      0.503
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    112/999       3.7G    0.03052    0.01008    0.01274         43        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.72it/s]
                   all         63         79      0.805      0.809      0.804      0.429
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    113/999       3.7G    0.03034    0.01023    0.01279         62        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.766        0.7       0.77      0.436
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    114/999       3.7G     0.0283   0.009983    0.01279         50        320: 100% 4/4 [00:01<00:00,  3.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.84it/s]
                   all         63         79      0.738      0.681      0.732      0.417
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    115/999       3.7G    0.03088   0.009158    0.01212         43        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.67it/s]
                   all         63         79      0.759      0.768      0.783      0.477
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    116/999       3.7G     0.0287    0.01086     0.0118         58        320: 100% 4/4 [00:01<00:00,  3.54it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.70it/s]
                   all         63         79      0.784       0.79      0.791      0.466
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    117/999       3.7G    0.02911    0.00914     0.0146         36        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.74it/s]
                   all         63         79      0.804      0.781      0.796      0.464
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    118/999       3.7G    0.03032     0.0095    0.01333         48        320: 100% 4/4 [00:01<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.57it/s]
                   all         63         79      0.766      0.715       0.75      0.451
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    119/999       3.7G    0.02993   0.009559    0.01296         37        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.89it/s]
                   all         63         79      0.845      0.735      0.799      0.484
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    120/999       3.7G    0.03003   0.009756    0.01204         44        320: 100% 4/4 [00:01<00:00,  3.61it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.35it/s]
                   all         63         79      0.831      0.778      0.798      0.491
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    121/999       3.7G    0.03059   0.009425     0.0142         46        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.87it/s]
                   all         63         79      0.849      0.816      0.816      0.505
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    122/999       3.7G    0.02925   0.009646    0.01339         54        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79      0.771      0.755      0.765      0.438
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    123/999       3.7G     0.0294   0.009603     0.0113         41        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.87it/s]
                   all         63         79      0.825       0.68      0.715      0.407
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    124/999       3.7G    0.02912    0.00941     0.0121         55        320: 100% 4/4 [00:01<00:00,  3.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.84it/s]
                   all         63         79      0.888      0.638      0.722      0.404
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    125/999       3.7G    0.02948   0.009574     0.0139         43        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.57it/s]
                   all         63         79      0.842      0.709      0.784      0.483
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    126/999       3.7G    0.02978   0.009803    0.01515         58        320: 100% 4/4 [00:01<00:00,  3.61it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.88it/s]
                   all         63         79      0.887      0.739      0.801      0.502
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    127/999       3.7G    0.03036   0.009031    0.01303         51        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.87it/s]
                   all         63         79      0.895       0.73      0.795      0.468
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    128/999       3.7G    0.02848   0.009346    0.01373         39        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.61it/s]
                   all         63         79      0.803       0.78      0.804      0.503
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    129/999       3.7G    0.02826   0.009106    0.01208         60        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.49it/s]
                   all         63         79      0.834      0.812      0.817      0.491
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    130/999       3.7G    0.02885   0.009643    0.01748         60        320: 100% 4/4 [00:01<00:00,  3.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.98it/s]
                   all         63         79      0.868      0.767      0.786      0.475
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    131/999       3.7G    0.03111   0.008421    0.01334         33        320: 100% 4/4 [00:01<00:00,  3.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.66it/s]
                   all         63         79      0.935      0.808      0.837      0.538
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    132/999       3.7G    0.02904    0.01023    0.01175         70        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.93it/s]
                   all         63         79      0.865      0.741      0.802      0.502
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    133/999       3.7G    0.02909    0.00936    0.01247         60        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.862      0.753      0.816      0.491
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    134/999       3.7G     0.0287   0.008813    0.01174         46        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.66it/s]
                   all         63         79      0.866      0.822      0.867      0.546
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    135/999       3.7G    0.02735   0.009386    0.01636         51        320: 100% 4/4 [00:01<00:00,  3.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.96it/s]
                   all         63         79      0.829      0.787      0.841      0.519
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    136/999       3.7G     0.0296   0.009375    0.01353         51        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79      0.868      0.737      0.762      0.491
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    137/999       3.7G    0.02858   0.008782    0.01255         38        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.65it/s]
                   all         63         79      0.861      0.645      0.728      0.441
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    138/999       3.7G    0.02605   0.009051    0.01414         51        320: 100% 4/4 [00:01<00:00,  3.75it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.36it/s]
                   all         63         79      0.854      0.663      0.774      0.485
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    139/999       3.7G    0.02855   0.009395    0.01485         52        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.81it/s]
                   all         63         79      0.828      0.761      0.815      0.527
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    140/999       3.7G    0.02826   0.008915    0.01113         38        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.85it/s]
                   all         63         79      0.902      0.725      0.793      0.506
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    141/999       3.7G    0.02668   0.009214    0.01215         41        320: 100% 4/4 [00:01<00:00,  3.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.25it/s]
                   all         63         79      0.864      0.789      0.822      0.516
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    142/999       3.7G    0.02886   0.008767    0.01534         44        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.804       0.84       0.82      0.508
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    143/999       3.7G    0.02995   0.008973    0.01554         42        320: 100% 4/4 [00:01<00:00,  3.66it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.42it/s]
                   all         63         79      0.835      0.844      0.849       0.53
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    144/999       3.7G    0.02694   0.008658    0.01147         38        320: 100% 4/4 [00:01<00:00,  3.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.853      0.883      0.852      0.526
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    145/999       3.7G    0.02597   0.009078    0.01421         46        320: 100% 4/4 [00:01<00:00,  3.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.833       0.81      0.826      0.502
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    146/999       3.7G    0.02553   0.009441   0.009095         53        320: 100% 4/4 [00:01<00:00,  3.55it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.88it/s]
                   all         63         79      0.798      0.803      0.805        0.5
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    147/999       3.7G     0.0288    0.00893     0.0149         35        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.94it/s]
                   all         63         79      0.821      0.793       0.79      0.486
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    148/999       3.7G    0.02741   0.008702    0.01218         44        320: 100% 4/4 [00:01<00:00,  3.55it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.58it/s]
                   all         63         79      0.841      0.801      0.812      0.507
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    149/999       3.7G     0.0281   0.009056    0.01309         62        320: 100% 4/4 [00:01<00:00,  3.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.86it/s]
                   all         63         79      0.863      0.819      0.833       0.51
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    150/999       3.7G     0.0293   0.009193    0.01287         55        320: 100% 4/4 [00:01<00:00,  3.81it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.26it/s]
                   all         63         79      0.853      0.799      0.834      0.492
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    151/999       3.7G    0.02822   0.008817    0.01395         48        320: 100% 4/4 [00:01<00:00,  2.97it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.26it/s]
                   all         63         79      0.912      0.778      0.833      0.493
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    152/999       3.7G    0.02731    0.00893     0.0147         36        320: 100% 4/4 [00:01<00:00,  2.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.34it/s]
                   all         63         79      0.896      0.781      0.848      0.499
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    153/999       3.7G    0.02973   0.009257    0.01246         54        320: 100% 4/4 [00:01<00:00,  2.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.15it/s]
                   all         63         79      0.835      0.834      0.879      0.521
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    154/999       3.7G    0.02594   0.008561     0.0116         43        320: 100% 4/4 [00:01<00:00,  2.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.43it/s]
                   all         63         79      0.811      0.857      0.863      0.514
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    155/999       3.7G    0.02697   0.009353    0.01208         52        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.72it/s]
                   all         63         79       0.84      0.842      0.851      0.528
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    156/999       3.7G    0.02687   0.008984    0.01088         48        320: 100% 4/4 [00:01<00:00,  3.84it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.10it/s]
                   all         63         79       0.82      0.819      0.806       0.53
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    157/999       3.7G    0.02782   0.008644    0.01627         46        320: 100% 4/4 [00:01<00:00,  3.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79      0.822      0.708      0.776      0.508
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    158/999       3.7G    0.02666   0.008735    0.01263         42        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.72it/s]
                   all         63         79      0.766      0.767      0.771      0.481
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    159/999       3.7G    0.02567   0.009102    0.01201         54        320: 100% 4/4 [00:01<00:00,  3.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.98it/s]
                   all         63         79      0.809      0.778      0.785      0.498
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    160/999       3.7G    0.02618   0.008408    0.01451         43        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.97it/s]
                   all         63         79      0.717      0.725       0.74      0.475
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    161/999       3.7G    0.02574   0.008437    0.01425         44        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.763      0.741      0.763      0.514
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    162/999       3.7G    0.02747   0.008519    0.01581         50        320: 100% 4/4 [00:01<00:00,  3.63it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.56it/s]
                   all         63         79      0.768      0.785       0.79      0.493
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    163/999       3.7G     0.0252   0.009203    0.01253         53        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.99it/s]
                   all         63         79      0.708      0.676      0.711      0.443
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    164/999       3.7G    0.02786   0.008905    0.01217         42        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.05it/s]
                   all         63         79      0.717      0.679      0.715      0.447
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    165/999       3.7G    0.02665   0.008707     0.0138         39        320: 100% 4/4 [00:01<00:00,  3.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.817       0.77      0.779      0.486
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    166/999       3.7G    0.02666    0.00868    0.01168         42        320: 100% 4/4 [00:01<00:00,  3.74it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.52it/s]
                   all         63         79      0.838       0.75      0.796      0.503
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    167/999       3.7G    0.02785   0.009274    0.01178         44        320: 100% 4/4 [00:01<00:00,  3.43it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.75it/s]
                   all         63         79      0.832      0.759      0.819      0.511
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    168/999       3.7G    0.02693   0.008733    0.01442         56        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.04it/s]
                   all         63         79      0.904      0.737      0.819      0.502
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    169/999       3.7G    0.02342   0.008244    0.01217         43        320: 100% 4/4 [00:01<00:00,  3.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.93it/s]
                   all         63         79      0.906      0.745      0.822      0.507
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    170/999       3.7G    0.02585   0.009652     0.0111         52        320: 100% 4/4 [00:01<00:00,  3.76it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.29it/s]
                   all         63         79      0.914      0.746      0.847      0.511
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    171/999       3.7G    0.02648   0.008348    0.01278         45        320: 100% 4/4 [00:01<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.83it/s]
                   all         63         79      0.878      0.742      0.806      0.468
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    172/999       3.7G    0.02685   0.008541    0.01327         42        320: 100% 4/4 [00:01<00:00,  3.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.844      0.754      0.827      0.502
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    173/999       3.7G    0.02536   0.008282    0.01204         37        320: 100% 4/4 [00:01<00:00,  3.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.66it/s]
                   all         63         79      0.888      0.813      0.838      0.532
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    174/999       3.7G    0.02479   0.008098    0.01241         49        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.84it/s]
                   all         63         79      0.843      0.801      0.813      0.515
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    175/999       3.7G    0.02468   0.008915    0.01029         39        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.79it/s]
                   all         63         79      0.889      0.827      0.847      0.566
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    176/999       3.7G    0.02632   0.008232    0.01162         47        320: 100% 4/4 [00:01<00:00,  3.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.892       0.84      0.841      0.532
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    177/999       3.7G    0.02695   0.008613    0.01345         40        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79      0.854      0.792       0.81      0.483
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    178/999       3.7G     0.0272   0.008675    0.01334         33        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.98it/s]
                   all         63         79       0.83      0.779      0.811      0.531
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    179/999       3.7G    0.02702   0.007769     0.0143         47        320: 100% 4/4 [00:01<00:00,  3.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.63it/s]
                   all         63         79      0.821      0.707      0.774      0.453
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    180/999       3.7G    0.02544   0.008988     0.0119         48        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.802      0.743      0.779      0.482
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    181/999       3.7G    0.02457   0.009275    0.01241         55        320: 100% 4/4 [00:01<00:00,  3.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.85it/s]
                   all         63         79       0.85      0.798      0.808      0.507
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    182/999       3.7G    0.02627    0.00841    0.01318         47        320: 100% 4/4 [00:01<00:00,  3.53it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.82it/s]
                   all         63         79      0.837      0.821       0.81      0.496
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    183/999       3.7G    0.02599   0.008699    0.01192         35        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.806      0.809      0.801      0.475
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    184/999       3.7G    0.02719   0.008365    0.01514         48        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.875      0.802      0.812        0.5
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    185/999       3.7G     0.0244   0.008259    0.01061         43        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.895      0.753      0.842      0.551
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    186/999       3.7G    0.02635   0.007986    0.01519         46        320: 100% 4/4 [00:01<00:00,  3.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.821      0.784       0.83      0.505
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    187/999       3.7G    0.02565   0.008761    0.01298         40        320: 100% 4/4 [00:01<00:00,  3.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.76it/s]
                   all         63         79      0.892      0.787      0.862      0.541
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    188/999       3.7G    0.02512   0.008524     0.0115         44        320: 100% 4/4 [00:01<00:00,  3.43it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.04it/s]
                   all         63         79      0.821      0.819      0.834      0.531
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    189/999       3.7G    0.02644   0.008746      0.011         52        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.95it/s]
                   all         63         79      0.927      0.761      0.822      0.513
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    190/999       3.7G    0.02496   0.008135    0.01399         38        320: 100% 4/4 [00:01<00:00,  3.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.74it/s]
                   all         63         79       0.88      0.777      0.831      0.497
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    191/999       3.7G    0.02443   0.008825     0.0125         62        320: 100% 4/4 [00:01<00:00,  3.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.80it/s]
                   all         63         79      0.856      0.816      0.858       0.54
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    192/999       3.7G    0.02605   0.008398    0.01297         32        320: 100% 4/4 [00:01<00:00,  3.60it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.37it/s]
                   all         63         79      0.831      0.838      0.863       0.53
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    193/999       3.7G    0.02603   0.008605    0.01238         53        320: 100% 4/4 [00:01<00:00,  3.55it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.79it/s]
                   all         63         79      0.829      0.816      0.837      0.514
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    194/999       3.7G    0.02386   0.007967    0.01153         39        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.99it/s]
                   all         63         79      0.828      0.807      0.828      0.528
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    195/999       3.7G    0.02526   0.009338    0.01433         57        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.91it/s]
                   all         63         79      0.853      0.836      0.854      0.545
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    196/999       3.7G    0.02454   0.008442    0.01252         51        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.95it/s]
                   all         63         79      0.848      0.831      0.828      0.542
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    197/999       3.7G    0.02556    0.00785    0.01221         53        320: 100% 4/4 [00:01<00:00,  3.02it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.77it/s]
                   all         63         79       0.84      0.806      0.837      0.519
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    198/999       3.7G    0.02376   0.008519    0.01071         39        320: 100% 4/4 [00:01<00:00,  3.61it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.65it/s]
                   all         63         79      0.945      0.632      0.765       0.48
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    199/999       3.7G    0.02719    0.00818    0.01343         44        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         63         79      0.819      0.711       0.79       0.47
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    200/999       3.7G    0.02524   0.008377    0.01428         43        320: 100% 4/4 [00:01<00:00,  2.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.94it/s]
                   all         63         79      0.726      0.795      0.784      0.488
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    201/999       3.7G    0.02296   0.007901    0.01277         46        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.97it/s]
                   all         63         79      0.784      0.749      0.772      0.445
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    202/999       3.7G    0.02545   0.008048    0.01471         29        320: 100% 4/4 [00:01<00:00,  3.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79      0.795      0.713      0.772      0.452
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    203/999       3.7G    0.02433   0.008558    0.01101         53        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.75it/s]
                   all         63         79      0.898      0.616       0.69      0.394
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    204/999       3.7G    0.02377   0.008952     0.0147         53        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.91it/s]
                   all         63         79       0.89       0.71      0.751      0.445
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    205/999       3.7G    0.02576   0.008926     0.0122         53        320: 100% 4/4 [00:01<00:00,  3.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.12it/s]
                   all         63         79      0.865      0.741      0.786      0.491
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    206/999       3.7G    0.02664   0.008284    0.01301         46        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.85it/s]
                   all         63         79      0.916      0.744      0.809      0.481
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    207/999       3.7G    0.02556   0.008232    0.01073         49        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.05it/s]
                   all         63         79      0.906      0.705      0.808       0.47
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    208/999       3.7G    0.02508    0.00831    0.01286         53        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.99it/s]
                   all         63         79       0.91      0.715      0.838      0.487
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    209/999       3.7G    0.02494   0.008386    0.01375         37        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.67it/s]
                   all         63         79      0.772      0.761      0.771      0.449
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    210/999       3.7G     0.0255   0.007751    0.01426         41        320: 100% 4/4 [00:01<00:00,  3.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.91it/s]
                   all         63         79      0.851      0.745      0.763      0.456
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    211/999       3.7G    0.02539   0.007726   0.009961         42        320: 100% 4/4 [00:01<00:00,  3.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.82it/s]
                   all         63         79      0.818      0.759       0.79       0.49
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    212/999       3.7G    0.02414   0.009787    0.01447         68        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.04it/s]
                   all         63         79       0.81      0.805      0.809      0.496
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    213/999       3.7G    0.02319   0.008777    0.01369         62        320: 100% 4/4 [00:01<00:00,  3.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.64it/s]
                   all         63         79      0.834      0.859      0.838      0.511
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    214/999       3.7G    0.02374   0.008508    0.01163         49        320: 100% 4/4 [00:01<00:00,  3.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.844       0.83      0.853      0.514
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    215/999       3.7G    0.02345   0.007581    0.01433         32        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.68it/s]
                   all         63         79      0.855      0.807      0.857      0.529
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    216/999       3.7G    0.02545   0.008759     0.0106         37        320: 100% 4/4 [00:01<00:00,  3.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79      0.855       0.82      0.841      0.514
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    217/999       3.7G    0.02623   0.008455     0.0142         46        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.891      0.835      0.875      0.508
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    218/999       3.7G    0.02553   0.008116    0.01129         49        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79      0.869      0.799      0.831      0.491
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    219/999       3.7G    0.02393   0.008445    0.01187         55        320: 100% 4/4 [00:01<00:00,  3.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.96it/s]
                   all         63         79      0.764      0.755      0.762      0.463
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    220/999       3.7G    0.02367   0.008847     0.0122         42        320: 100% 4/4 [00:01<00:00,  3.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.06it/s]
                   all         63         79      0.739      0.704      0.749      0.443
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    221/999       3.7G    0.02559   0.008589    0.01213         40        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.60it/s]
                   all         63         79       0.86      0.807      0.854      0.511
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    222/999       3.7G    0.02568   0.008135     0.0136         47        320: 100% 4/4 [00:01<00:00,  3.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79       0.84      0.809      0.838      0.482
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    223/999       3.7G    0.02529   0.008335   0.009396         50        320: 100% 4/4 [00:01<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.83it/s]
                   all         63         79      0.828      0.768      0.814       0.48
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    224/999       3.7G    0.02315   0.008706    0.01168         51        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.91it/s]
                   all         63         79      0.871       0.83      0.837      0.525
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    225/999       3.7G    0.02185   0.007832    0.01277         50        320: 100% 4/4 [00:01<00:00,  3.79it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.20it/s]
                   all         63         79       0.85      0.792      0.814      0.521
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    226/999       3.7G    0.02436   0.008962    0.01352         63        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.873      0.805      0.803      0.535
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    227/999       3.7G    0.02481   0.008874    0.01294         44        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.67it/s]
                   all         63         79      0.832      0.781      0.798       0.51
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    228/999       3.7G    0.02371   0.007954    0.01312         49        320: 100% 4/4 [00:01<00:00,  3.62it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.39it/s]
                   all         63         79       0.86      0.817       0.83      0.529
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    229/999       3.7G    0.02313   0.008159    0.01403         38        320: 100% 4/4 [00:01<00:00,  3.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.86it/s]
                   all         63         79       0.79      0.809      0.808       0.49
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    230/999       3.7G    0.02397    0.00775    0.01498         40        320: 100% 4/4 [00:01<00:00,  3.76it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.18it/s]
                   all         63         79      0.859      0.784      0.811      0.497
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    231/999       3.7G    0.02375   0.009019    0.01145         49        320: 100% 4/4 [00:01<00:00,  3.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.77it/s]
                   all         63         79      0.894      0.808      0.833      0.504
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    232/999       3.7G    0.02479   0.008392    0.01322         49        320: 100% 4/4 [00:01<00:00,  3.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.84it/s]
                   all         63         79      0.874      0.736       0.81      0.472
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    233/999       3.7G    0.02362   0.007606    0.01504         42        320: 100% 4/4 [00:01<00:00,  3.43it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.85it/s]
                   all         63         79      0.808      0.792      0.815      0.492
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    234/999       3.7G    0.02515   0.008511    0.01224         52        320: 100% 4/4 [00:01<00:00,  3.61it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.54it/s]
                   all         63         79      0.799      0.759      0.813      0.497
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    235/999       3.7G    0.02413   0.007321      0.011         34        320: 100% 4/4 [00:01<00:00,  3.62it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.54it/s]
                   all         63         79      0.832      0.804      0.824      0.515
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    236/999       3.7G    0.02562   0.008665      0.014         47        320: 100% 4/4 [00:01<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.70it/s]
                   all         63         79      0.838      0.795      0.853      0.523
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    237/999       3.7G    0.02393    0.00773    0.01388         43        320: 100% 4/4 [00:01<00:00,  3.18it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.97it/s]
                   all         63         79       0.86      0.782       0.85      0.521
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    238/999       3.7G     0.0212   0.008192    0.01327         43        320: 100% 4/4 [00:01<00:00,  3.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.77it/s]
                   all         63         79      0.878      0.775      0.841      0.543
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    239/999       3.7G     0.0218   0.008066    0.01277         53        320: 100% 4/4 [00:01<00:00,  3.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.00it/s]
                   all         63         79      0.861      0.799      0.848      0.538
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    240/999       3.7G    0.02238   0.007802    0.01127         46        320: 100% 4/4 [00:01<00:00,  3.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.94it/s]
                   all         63         79      0.833       0.81      0.847      0.546
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    241/999       3.7G    0.02324   0.008582   0.009788         38        320: 100% 4/4 [00:01<00:00,  3.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.94it/s]
                   all         63         79      0.823      0.833      0.852      0.553
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    242/999       3.7G    0.02243   0.007909    0.01101         49        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.40it/s]
                   all         63         79      0.844      0.817      0.857       0.54
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    243/999       3.7G    0.02331   0.007496    0.01363         46        320: 100% 4/4 [00:01<00:00,  3.85it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.97it/s]
                   all         63         79      0.833      0.824      0.863      0.535
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    244/999       3.7G     0.0226   0.007969    0.01327         44        320: 100% 4/4 [00:01<00:00,  3.54it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.74it/s]
                   all         63         79      0.817      0.798      0.842      0.533
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    245/999       3.7G    0.02296   0.007882    0.01037         60        320: 100% 4/4 [00:01<00:00,  3.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.804      0.778      0.837      0.525
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    246/999       3.7G    0.02384   0.007846    0.01653         50        320: 100% 4/4 [00:01<00:00,  3.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.85it/s]
                   all         63         79      0.821      0.762      0.839      0.522
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    247/999       3.7G    0.02153   0.007715    0.01345         38        320: 100% 4/4 [00:01<00:00,  3.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.77it/s]
                   all         63         79      0.846      0.783      0.833      0.516
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    248/999       3.7G    0.02304   0.008425    0.01012         52        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.76it/s]
                   all         63         79       0.82      0.785       0.82      0.508
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    249/999       3.7G    0.02263    0.00798    0.01045         56        320: 100% 4/4 [00:01<00:00,  3.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.95it/s]
                   all         63         79      0.829      0.762      0.807      0.517
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    250/999       3.7G    0.02254   0.007397    0.01361         36        320: 100% 4/4 [00:01<00:00,  3.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79      0.877      0.783      0.836       0.53
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    251/999       3.7G    0.02312   0.007422   0.009921         55        320: 100% 4/4 [00:01<00:00,  3.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.02it/s]
                   all         63         79      0.921       0.79      0.827      0.537
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    252/999       3.7G    0.02233   0.007313    0.01306         37        320: 100% 4/4 [00:01<00:00,  3.79it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.17it/s]
                   all         63         79      0.885      0.808      0.835      0.534
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    253/999       3.7G    0.02339   0.007874    0.01155         50        320: 100% 4/4 [00:01<00:00,  3.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.67it/s]
                   all         63         79      0.863       0.78      0.835      0.544
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    254/999       3.7G    0.02388    0.00805     0.0108         46        320: 100% 4/4 [00:01<00:00,  3.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79       0.83      0.753      0.812      0.528
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    255/999       3.7G    0.02411   0.007804    0.01152         57        320: 100% 4/4 [00:01<00:00,  3.62it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.44it/s]
                   all         63         79      0.771      0.696      0.763      0.494
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    256/999       3.7G    0.02302   0.006908    0.01303         32        320: 100% 4/4 [00:01<00:00,  3.72it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.37it/s]
                   all         63         79      0.807       0.63       0.72       0.43
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    257/999       3.7G    0.02334   0.007612   0.009617         43        320: 100% 4/4 [00:01<00:00,  3.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.797      0.684      0.742      0.472
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    258/999       3.7G    0.02197   0.007685    0.01219         39        320: 100% 4/4 [00:01<00:00,  3.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.88it/s]
                   all         63         79      0.854      0.736      0.791      0.475
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    259/999       3.7G    0.02231   0.008295    0.01253         47        320: 100% 4/4 [00:01<00:00,  3.53it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.49it/s]
                   all         63         79      0.856      0.788      0.824      0.505
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    260/999       3.7G    0.02241   0.007404     0.0126         38        320: 100% 4/4 [00:01<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.72it/s]
                   all         63         79      0.825      0.803      0.826      0.527
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    261/999       3.7G    0.02368   0.008053    0.01039         45        320: 100% 4/4 [00:01<00:00,  3.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.90it/s]
                   all         63         79      0.847      0.769      0.812       0.51
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    262/999       3.7G    0.02323   0.007923    0.01212         57        320: 100% 4/4 [00:01<00:00,  3.88it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.22it/s]
                   all         63         79      0.838      0.743      0.783      0.486
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    263/999       3.7G    0.02189   0.007756    0.01194         52        320: 100% 4/4 [00:01<00:00,  3.53it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.91it/s]
                   all         63         79      0.804      0.693      0.766      0.486
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    264/999       3.7G    0.02193   0.008082    0.01073         41        320: 100% 4/4 [00:01<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.05it/s]
                   all         63         79      0.801      0.635      0.737      0.458
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    265/999       3.7G    0.02194   0.007734    0.01131         46        320: 100% 4/4 [00:01<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.825      0.663      0.793       0.51
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    266/999       3.7G    0.02225   0.008037    0.01224         63        320: 100% 4/4 [00:01<00:00,  3.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79      0.843      0.759       0.82      0.534
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    267/999       3.7G    0.02252   0.007782    0.01099         47        320: 100% 4/4 [00:01<00:00,  3.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.01it/s]
                   all         63         79      0.799      0.773      0.826      0.527
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    268/999       3.7G    0.02323   0.007621    0.01167         49        320: 100% 4/4 [00:01<00:00,  3.62it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.60it/s]
                   all         63         79      0.776       0.71      0.765      0.474
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    269/999       3.7G    0.02269   0.008201    0.01148         48        320: 100% 4/4 [00:01<00:00,  3.43it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.92it/s]
                   all         63         79      0.876      0.631      0.738      0.461
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    270/999       3.7G    0.02146   0.007979     0.0122         50        320: 100% 4/4 [00:01<00:00,  3.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.89it/s]
                   all         63         79      0.839      0.714      0.765      0.501
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    271/999       3.7G    0.02227    0.00731    0.01189         55        320: 100% 4/4 [00:01<00:00,  3.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.07it/s]
                   all         63         79      0.929      0.642      0.768      0.519
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    272/999       3.7G    0.02171    0.00809    0.01179         54        320: 100% 4/4 [00:01<00:00,  3.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.27it/s]
                   all         63         79      0.865      0.737      0.785      0.524
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    273/999       3.7G    0.02305   0.008095    0.01207         47        320: 100% 4/4 [00:01<00:00,  3.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.73it/s]
                   all         63         79      0.898      0.729      0.802      0.521
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    274/999       3.7G    0.02146   0.007612   0.008951         49        320: 100% 4/4 [00:01<00:00,  3.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  2.91it/s]
                   all         63         79      0.885      0.789      0.802      0.506
      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    275/999       3.7G    0.02231   0.007732   0.009946         53        320: 100% 4/4 [00:01<00:00,  3.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  3.03it/s]
                   all         63         79      0.828      0.792      0.794      0.505
  ```
</details>

### Evidências do treinamento

Nessa seção você deve colocar qualquer evidência do treinamento, como por exemplo gráficos de perda, performance, matriz de confusão etc.

Exemplo de adição de imagem:
(![Métricas de treinamento](https://user-images.githubusercontent.com/116462121/200436568-86567846-b46c-481e-b545-435d07122836.png)

## Roboflow

 [Roboflow](https://app.roboflow.com/cesar-school-ps-graduao/projeto-final-modelos-preditivos-conexionistas/1)

## HuggingFace

[HuggingFace](https://huggingface.co/spaces/afonsoaraujoo/Projeto_Modelos_Preditivos/tree/main)
