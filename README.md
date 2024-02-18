# Yield curves building  

$$ \frac{Price}{4} (DF_{3m} + DF_{6m} + DF_{9m} + DF_{12m}) = \frac{1}{4}\left( Benchmark_{3M}(0)\cdot DF_{3m} + Benchmark_{3M}(3)\cdot DF_{6m} + Benchmark_{3M}(6)\cdot DF_{9m} + Benchmark_{3M}(9) \cdot DF_{12m}     \right) $$

$ Benchmark_{3M}(0) $ 

$ Benchmark_{3M}(3,6,9)$ 

$ DF_{3m} = \frac{1}{1 + 0.25\cdot {L_3}}$

$ DF_{6m} = \frac{DF_{3m}}{1 + 0.25\cdot {L_{3,6}}}$

$ DF_{9m} = \frac{DF_{6m}}{1 + 0.25\cdot {L_{6,9}}}$

$ DF_{12m} = \frac{DF_{9m}}{1 + 0.25\cdot {L_{9,12}}}$
