# READ ME 

R script written to generate similar resultats as the KEGG Mapper Reconstruct tool, more specifically to indicate which module are complete VS non-complete. 

**About KEGG modules**

KEGG modules are defined by a Boolean combination of KEGG Orthologs (KOs). 
Completeness of modules is evaluated by checking whether the required KO combination for every step (block) in the Boolean expression is present; alternatives (OR), complexes (AND/“+”), and optional components (“–”) are handled explicitly. 

