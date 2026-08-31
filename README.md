<div align="center">

<img src="https://ssoqe.github.io/SSoQE_website/photos/SSOQE_logo3.png" width="150" alt="SSoQE logo">

# Deep Learning

**SSoQE 2026 · Wednesday, 16 September · 11:00–12:30**

[View the slides](https://ssoqe.github.io/SSoQE-Deep_Learning_in_Ecology/) · [SSoQE website](https://ssoqe.github.io/SSoQE_website/) · [2026 programme](https://ssoqe.github.io/SSoQE_website/About/program.html)


| **📅 Course information** | **🧰 Technical** | **📌 Status** |
|:---:|:---:|:---:|
| ![SSoQE 2026](https://img.shields.io/badge/SSoQE-2026-155560) | ![Type](https://img.shields.io/badge/Type-Course_Module-155560) | ![Status](https://img.shields.io/badge/Status-Active-509A8E) |
| ![Day](https://img.shields.io/badge/Day-Wednesday-C2A337) | ![Topic](https://img.shields.io/badge/Topic-Deep_Learning-155560) | ![Tools](https://img.shields.io/badge/Tools-R_%7C_Quarto_%7C_PyTorch-276DC3) |

</div>

## 🌿 About the lesson

This lesson provides an accessible introduction to deep learning for ecologists. It explains the training, validation, and evaluation workflow and uses a mushroom-classification exercise to show how architecture and hyperparameters affect model performance.

## 🎯 Learning goals

By the end of the lesson, participants should be able to:

- explain the basic structure and training workflow of a neural network;
- distinguish training, validation, and evaluation data;
- modify key hyperparameters and interpret changes in performance;
- recognize when deep learning is, and is not, appropriate for an ecological question.

## 📚 Materials

- `Presentation/presentation.qmd` is the slide source.
- `R/Exercises/Exercise_Deep_Learning_in_Ecology.qmd` is the practical exercise.
- `Data/Input/mushrooms.csv` and `Data/Processed/mushrooms_numerical.csv` support the exercise.
- `R/render.R` renders the presentation and updates its publication copy.

The practical exercise uses PyTorch through the repository's existing teaching environment. Follow the participant setup instructions on the SSoQE website rather than creating a second environment ad hoc.

## 🛠️ Rendering

Restore dependencies only as an explicit setup step. Render the presentation from a clean session with:

```powershell
Rscript R/render.R
```

Edit the Quarto, JSON, and R sources rather than generated HTML or theme files.

## 📄 Licence

See [LICENSE](LICENSE).
