# 🌐 Interpretability on legal domain

## Created by
**Author:** Hugo Alatrists-Salas <br />
**Contact Details:** hugo.alatrista_salas@devinci.fr <br />
**Collaborators:** Olga Alcantara-Francia/Miguel Nuñez del Prado <br />
**Contact Details:** hugo.alatrista_salas@devinci.fr <br />
**Institution:** De Vinci Research Center
<br />

## Description
This code implements a 5-step methodology for analysing legal documents from the agency responsible for resolving administrative sanction procedures related to consumer protection

Link to pur paper: [https://link.springer.com/article/10.1007/s12652-022-03808-x](https://link.springer.com/article/10.1007/s11135-024-01882-1)

Please, cite us using the following text (APA format).

> Alcántara Francia, O. A., Nunez-del-Prado, M., & Alatrista-Salas, H. (2024). Exploring the interpretability of legal terms in tasks of classification of final decisions in administrative procedures. Quality & Quantity, 58(5), 4833-4857.
Bibtex:
```
@article{alcantara2024exploring,
  title={Exploring the interpretability of legal terms in tasks of classification of final decisions in administrative procedures: OAA Francia et al.},
  author={Alc{\'a}ntara Francia, Olga Alejandra and Nunez-del-Prado, Miguel and Alatrista-Salas, Hugo},
  journal={Quality \& Quantity},
  volume={58},
  number={5},
  pages={4833--4857},
  year={2024},
  publisher={Springer}
}
```

4. Perform data division in train and validation dataset:

```python
# for this example have proportion 90 (train) /10 (validate)
train, validate = pdt.split_train_validation(df_patterns_weight, 0.9)
