# PyTorch zapiski

Osebni zvezek za učenje PyTorcha. Vsebuje razlago in kodo. 

## Vsebina

- tenzorji (ustvarjanje, oblika, tip, naprava)
- osnove avtograda
- operacije: `*` vs `@`, redukcije, indeksiranje, reshape, stack, squeeze, permute
- PyTorch in NumPy, ponovljivost (seme), GPU
- linearna regresija po korakih: podatki, model, loss, optimizator, učna zanka, shranjevanje modela
- forward in backward pass ter gradient descent, napisan ročno
- `torch.nn`: Linear, ReLU, GELU, Softmax, Embedding, LayerNorm, Dropout
- končni model z `nn.Module` in Adamom

## Zahteve

- Python 3.12
- PyTorch 2.14.1 (zvezek je bil zagnan s to različico)
- NumPy, pandas, Matplotlib
- Jupyter Notebook, JupyterLab ali VS Code z razširitvijo za Jupyter
 
Narejeno s Pythonom 3.12 in PyTorchem 2.14.1. GPU ni nujen, zvezek deluje tudi na CPU.

## Viri

- [PyTorch dokumentacija](https://docs.pytorch.org/docs/2.14/index.html)
- [Predavanje 1: Daniel Bourke](https://www.youtube.com/watch?v=V_xro1bcAuA)
- [Predavanje 2: Zachary Huang](https://www.youtube.com/watch?v=r1bquDz5GGA)
- [Video: Andrej P. Škraba](https://www.youtube.com/watch?v=woSNI-aejnU)

Nekatere slike so iz teh virov in pripadajo svojim avtorjem.
