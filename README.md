# A Complete Guide to Efficient Transformations of data frames

This is a tutorial on [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl)
operation specification syntax
prepared for [JuliaCon2022](https://juliacon.org/2022/).

In order to run the tutorial make sure that you have Julia executable installed.
The tutorial was updated to Julia 1.9.0 and DataFrames.jl 1.5.0.

The simplest way to run it is to proceed as follows:
1. Clone the
   [tutorial repository](https://github.com/bkamins/JuliaCon2022-DataFrames-Tutorial)
   to a local folder on your computer.
2. Start Julia in your local folder using the `julia --project` command.
3. Run the following commands (this step needs to be run only once per installation and is made to double check that you have proper versions of packages downloaded):
```
using Pkg
Pkg.instantiate()
Pkg.status()
```
4. Start Jupyter Notebook with:
```
using IJulia
notebook(dir=pwd())
```
5. In the Jupyter Notebook open the *juliacon2022.ipynb* file and follow the tutorial.

---

*Preparation of this workshop has been supported by the Polish National Agency for Academic Exchange under the Strategic Partnerships programme, grant number BPI/PST/2021/1/00069/U/00001.*

![SGH & NAWA](logo.png)