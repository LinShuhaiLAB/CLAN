# This is CLAN!:joy:
CLAN is a desktop software written in C++ for automated cardiolipin characterization.

## Functions
- [x] **Precise identification of cardiolipin**
- [x] **Rt filter of cardiolipin**
- [x] **Prediction of features without MS/MS**

---

## Download
[CLAN v1.0.0](https://github.com/LinShuhaiLAB/CLAN/releases/download/v1.0.0/)

---

## Input
### MS1
From **[mzmine](https://github.com/mzmine/mzmine3) of other peak picking software**.
### MS2
Provide **mzML** files.


## Example of output
| Compound | Rt(min) |      Structure      | Predict |
| :------: | :-----: | :-----------------: | :-----: |
| CL 56:0  |  11.0   | 14:0/14:0/14:0/14:0 |  **FALSE**  |
| CL 74:2  |  13.0   |         NA          |  **TRUE**   |
|   ...    |   ...   |         ...         |   ...   |

