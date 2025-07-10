# Mathematical-Foundations-of-Machine-and-Deep-Learning
# Regularyzacja w regresji liniowej: L1, L2 i Elastic Net

Celem projektu była analiza wpływu regularyzacji L1 (Lasso), L2 (Ridge) oraz Elastic Net na modele regresji liniowej. Projekt obejmuje zarówno część teoretyczną, jak i praktyczną, skupiając się na wpływie regularyzacji na wartości współczynników, złożoność modelu i jego zdolność do generalizacji.

---

## Zakres projektu

W części teoretycznej omówiono:
- funkcje celu stosowane w modelach Lasso i Ridge,
- sposób działania regularyzacji na współczynniki regresji,
- powody, dla których Ridge można rozwiązać analitycznie, a Lasso wymaga metod iteracyjnych,
- różnice geometryczne między karami L1 i L2 oraz wpływ regularyzacji na trajektorie współczynników.

---

## Eksperymenty

W części praktycznej użyto dwóch zestawów danych:
- **BodyFat** – rzeczywisty zbiór danych o zawartości tłuszczu w ciele,
- **Dane syntetyczne** – wygenerowane przy użyciu `make_regression()` z kontrolowaną liczbą cech i poziomem szumu.

Dla każdego zestawu danych porównano następujące modele:
- regresja liniowa (OLS),
- Ridge,
- Lasso,
- Elastic Net.

Przeanalizowano:
- wartości współczynników,
- wpływ regularyzacji na prostotę modelu,
- błędy MSE,
- wyniki walidacji krzyżowej.

---

## Kluczowe wnioski

- **Ridge** zmniejsza współczynniki proporcjonalnie, co stabilizuje model.
- **Lasso** wyzerowuje część współczynników, co umożliwia selekcję cech.
- **Elastic Net** łączy oba podejścia, dając większą elastyczność i często lepsze wyniki.
- Regularyzacja poprawia zdolność do generalizacji, szczególnie w przypadku szumu lub nadmiaru cech.

---

## 💻 Kod

 [Zobacz kod](Kod.ipynb)

---
