# Poznámky

## Odkazy na zadání a soubory z přednášek
- [Zápočtové Úlohy](https://marian.fsik.cvut.cz/~jkarel/NMI/ZapoctoveUlohy.pdf)
- [Přednáška 1](https://marian.fsik.cvut.cz/~jkarel/NMI/Prednaska1)
- [Přednáška 3](https://marian.fsik.cvut.cz/~jkarel/NMI/Prednaska3)
- [Přednáška 4](https://marian.fsik.cvut.cz/~jkarel/NMI/Prednaska4)
- [Přednáška 5](https://marian.fsik.cvut.cz/~jkarel/NMI/Prednaska5)
- [Přednáška 7](https://marian.fsik.cvut.cz/~jkarel/NMI/Prednaska7)

## Doporučení
- úloha č.1 a č.2 - **pokud třídy nepotřebuješ, nepoužívej je**
	- ulož si matici jako vektor a indexuj A[i+j*n]
	- vypracuj úlohu č.2 před úlohou č.1
- úloha č.3 - **pokud třídy potřebuješ, používej cizí**
	- knihovna [Eigen](https://eigen.tuxfamily.org/index.php?title=Main_Page) má implementaci řídkých matic v csc formátu a obal na řešič UmfPack

## Dokumentace
- [LAPACK](http://www.netlib.org/lapack/explore-html/) > Files > File List >
	- LAPACKE > src: C subroutines 
	- SRC: Fortran subroutines (s popisem argumentů)
- [Eigen](https://eigen.tuxfamily.org/dox-devel/index.html) > Chapters > Sparce linear algebra > [Solving Sparse Linear Systems](https://eigen.tuxfamily.org/dox-devel/group__TopicSparseSystems.html)

## Použité funkce a třídy
- Úloha č.1: `LAPACK_dgeev()`
- Úloha č.2: `LAPACK_dgesv()`
- Úloha č.3: `UmfPackLU<SparseMatrix<double>>`