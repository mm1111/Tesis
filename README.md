# Tesis

   ### 1. hacer listas de proteinas (1 cadena, 1 mutacion, ddG Experimental). 
      PDB_ID -- CHAIN -- LENGTH -- RESOLUTION -- DDG -- AA1_RESIDUE_ AA2 -- WITH/WITHOUT_LIGAND -- Temp -- pH
   ### 2. archivo con las secuencias por PDB.
      >PDB_ID|CHAIN
      SEQUENCE
   ### 3. FoldX. 
      - LIMPIAR
      a. repair a PDB file.
      b. reconstruir cadenas laterales.
      c. repair 
      d. medir estabilidad (DG0)
      e. documnetar en GitHUB 
      - MUTAR
      a. mutar un amino acid
      b. repair
      c. medir estabilidad (DGmut).
      d. guardar PDB mutados (~4,000). 
      e. generar lista (+ DDG(pred) = DGmut - DG0.)
      PDB_ID -- CHAIN -- LENGTH -- RESOLUTION -- DDG(exp) -- DDG(pred) -- AA1_RESIDUE_ AA2 -- WITH/WITHOUT_LIGAND -- Temp -- pH
