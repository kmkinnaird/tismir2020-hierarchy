# Automatic hierarchy expansion for structure and chord evaluation
Associated code for *Automatic hierarchy expansion for improved structure and chord evaluation*
submitted to TISMIR in 2020. Accepted 2021.

This code extends [*Improving structure evaluation through automatic hierarchy expansion*](https://brianmcfee.net/papers/ismir2019expansion.pdf) (ISMIR 2019)

## Code Organization
The code is organized into four jupyter notebook files:   
- `Matching-TUT-ISO` - explains how we created a matching between two human-generated annotations of Beatles recordings: TUT and Isophonics datasets
- `IsoTUT-AHE-extension` - extends the 2019 paper to a broader collection of structure labels and includes a parser for a broader variety of structure labels than those present in SALAMI
- `AHE-for-chord` -  extends the 2019 paper to chord evaluation, for annotations that include any chord label within the [Harte et. al. grammar](https://ismir2005.ismir.net/proceedings/1080.pdf) (ISMIR 2005)
- `Chord results` - summarizes the results from `AHE-for-chord` in a series of visualizations

Much of the paths in this code are hard-coded to our particular machines. We have also included several of the intermediate and output files. 
