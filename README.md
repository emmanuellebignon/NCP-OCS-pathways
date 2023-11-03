# NCP-OCS-pathways
Supplementary Materials for: Cysteine hyperoxidation rewires communication pathways in the nucleosome and destabilizes the dyad

## MD inputs for NAMD simulations ##
_run.namd: minimization/equilibration input

_run_prod.namd: production input

## In OCS-parameters ##
OCS.lib: AMBER library file for the OCS residue (sulfonylated cysteine)

OCS.frcmod: additional parameters file for the OCS residue

## In prep-inputs-1kx5 ##
_tleap: tleap input file for adding water and ions, and generating topology/coordinates/pdb files

1kx5_box.prmtop.zip: topology file

1kx5_box_hmr.prmtop.zip: topology file with HMR

1kx5_box.pdb.zip: pdb file

1kx5_box.fix.zip: pdb file with labels in the B-factor column for restraints during the equilibration

## In prep-inputs-1kx5-ocs ##
_tleap: tleap input file for adding water and ions, and generating topology/coordinates/pdb files

ncp-OCS.prmtop.zip: topology file

ncp-OCS_hmr.prmtop.zip: topology file with HMR

ncp-OCS.pdb.zip: pdb file

ncp-OCS.fix.zip: pdb file with labels in the B-factor column for restraints during the equilibration

## In Pathways.tgz ##
Raw data about computed communications pathways, including the list of hubs in each pathway.
