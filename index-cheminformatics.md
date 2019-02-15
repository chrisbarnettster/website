---
layout: subsite-galaxy
---


<br/>
<img src="/assets/media/cheminformatics.png" height="200px" alt="Cheminformatics"/>

Welcome to our **Computational Chemistry** flavour of UseGalaxy.eu -- a webserver to process, analyse and visualize chemical data.


1. TOC
{:toc}


# Get started

Are you new to Galaxy, or returning after a long time, and looking for help to get started? Take [a guided tour](https://cheminformatics.usegalaxy.eu/tours/core.galaxy_ui){:target="_blank"} through Galaxy's user interface.

Want to learn about computational chemistry? Check our [tutorials](#tutorials).

Check also the standard but customizable [workflows](#workflows) available there.

# Tools

Several tools are integrated in this custom Galaxy instance. They were chosen for their use in exploitation of chemical data:


## chemical structure conversion and manipulation tools

Tool | Description | Reference
--- | --- | ---
[remSmallMol](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_remsmall/openbabel_remSmall/){:target="_top"} | Remove small molecules | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
[AddH](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_addh/openbabel_addh/){:target="_top"} | Add hydrogen atoms at a certain pH value | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
[RemDupMol](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_remduplicates/openbabel_remDuplicates/){:target="_top"} | Remove duplicated molecules  | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
[remProtState](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_remove_protonation_state/openbabel_remove_protonation_state){:target="_top"} | Remove protonation state of every atom | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
[comConvert](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_compound_convert/openbabel_compound_convert/){:target="_top"} | Compound Convert Converts various chemistry and molecular modeling data files | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
[remConterIons](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_remions/openbabel_remIons/){:target="_top"} | Remove counterions and fragments | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
[changTitle](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_change_title/openbabel_change_title){:target="_top"} | Change Title to meta-data value | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
[remCountIo](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_change_title/openbabel_change_title){:target="_top"} | Change Title to meta-data value | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
{:.table.table-striped}


## compute chemical properties

Tool | Description | Reference
--- | --- | ---
[genProp](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/openbabel_genprop/openbabel_genProp/){:target="_top"} | Compute physico-chemical properties for a set of molecules  | [N M O'Boyle,2011](https://doi.org/10.1186/1758-2946-3-33){:target="_blank"}
[NPL](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/natural_product_likeness/ctb_np-likeness-calculator){:target="_top"} | Natural Product likeness calculator  | [Jayaseelan, Kalai Vanii, 2012](http://dx.doi.org/10.1186/1471-2105-13-106){:target="_blank"}
[QED](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/bgruening/silicos_it/ctb_silicos_qed/0.1) | Drug-likeness quantitative estimation (QED) | [Bickerton et al., 2012](https://doi.org/10.1038/nchem.1243){:target="_blank"}
{:.table.table-striped}

## molecular dynamics tools

Tool | Description | Reference
--- | --- | ---
[gmxSetup](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/gmx_setup/gmx_setup/){:target="_top"} | Produce a topology using GROMACS for a given protein structure  | [Abraham et al., 2015](https://doi.org/10.1016/j.softx.2015.06.001){:target="_blank"}
[gmxSolvate](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/gmx_solvate/gmx_solvate/){:target="_top"} | Solvate a system using GROMACS | [Abraham et al., 2015](https://doi.org/10.1016/j.softx.2015.06.001){:target="_blank"}
[gmxEM](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/gmx_em/gmx_em/){:target="_top"} | Energy minimization using GROMACS  | [Abraham et al., 2015](https://doi.org/10.1016/j.softx.2015.06.001){:target="_blank"}
[gmxNVT](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/gmx_nvt/gmx_nvt/){:target="_top"} | NVT equilibration using GROMACS  | [Abraham et al., 2015](https://doi.org/10.1016/j.softx.2015.06.001){:target="_blank"}
[gmxNPT](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/gmx_npt/gmx_npt/){:target="_top"} |  NPT equilibration using GROMACS  | [Abraham et al., 2015](https://doi.org/10.1016/j.softx.2015.06.001){:target="_blank"}
[gmxMD](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/gmx_md/gmx_md/){:target="_top"} | Production simulation using GROMACS  | [Abraham et al., 2015](https://doi.org/10.1016/j.softx.2015.06.001){:target="_blank"}
[mdaDistance](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/mdanalysis_distance/mdanalysis_distance/){:target="_top"} | Distance analysis using MDAnalysis  | [Agrawal et al., 2011](https://doi.org/10.1002/jcc.21787){:target="_blank"}
[mdaDihedral](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/mdanalysis_dihedral/mdanalysis_dihedral/){:target="_top"} | Dihedral analysis using MDAnalysis  | [Agrawal et al., 2011](https://doi.org/10.1002/jcc.21787){:target="_blank"}
[mdaRDF](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/mdanalysis_rdf/mdanalysis_rdf/){:target="_top"} | Radial distribution function between two atoms  | [Agrawal et al., 2011](https://doi.org/10.1002/jcc.21787){:target="_blank"}
[mdaAngle](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/mdanalysis_angle/mdanalysis_angle/){:target="_top"} | Angle analysis using MDAnalysis | [Agrawal et al., 2011](https://doi.org/10.1002/jcc.21787){:target="_blank"}
[mdConverter](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/md_converter/md_converter/){:target="_top"} | Interconvert between MD file formats | [McGibbon et al., 2015](https://doi.org/10.1016/j.bpj.2015.08.015){:target="_blank"} [Abraham et al., 2015](https://doi.org/10.1016/j.softx.2015.06.001){:target="_blank"}
[packmol](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/packmol/packmol/){:target="_top"} | Create initial MD configurations | [Martinez et al., 2009](https://doi.org/10.1002/jcc.21224){:target="_blank"}
[bio3dPCA](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/bio3d_pca/bio3d_pca/){:target="_top"} | Apply PCA to an MD trajectory | [Grant et al., 2006](https://doi.org/10.1093/bioinformatics/btl461){:target="_blank"}
[bio3dRMSD](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/bio3d_rmsd/bio3d_rmsd/){:target="_top"} | Calculate RMSD for an MD trajectory | [Grant et al., 2006](https://doi.org/10.1093/bioinformatics/btl461){:target="_blank"}
[bio3dRMSF](https://cheminformatics.usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu/repos/chemteam/bio3d_rmsf/bio3d_rmsf/){:target="_top"} | Calculate RMSF for an MD trajectory | [Grant et al., 2006](https://doi.org/10.1093/bioinformatics/btl461){:target="_blank"}
{:.table.table-striped}

# Tutorials
- PDF's of the workshop run in 2019 are [available](https://drive.google.com/drive/folders/10oxT2Vl4rBdyNR8iHjer4Q77Ra56-jIp?usp=sharing)

🙋 Are additional tutorials needed? [Please make a request.](https://github.com/galaxycomputationalchemistry/galaxy-tools-compchem/issues)

# Workflows

To orchestrate tools and help users with their analyses, several workflows are available. They formally orchestrate tools in a defined order and with defined parameters, but they are customizable (tools, order, parameters).

The workflows are available in the [Shared Workflows](https://cheminformatics.usegalaxy.eu/workflows/list_published), with the label "***cheminformatics***".

Workflow | Description
--- | ---
[GROMACS](https://cheminformatics.usegalaxy.eu/u/simonbray/w/molecular-dynamics-1) | Molecular dynamics simulation with GROMACS
[Bio3D](https://cheminformatics.usegalaxy.eu/u/tsenapathi/w/md-analysis-using-bio3d) | Molecular dynamics analysis with Bio3D
{:.table.table-striped}

# Contributors

  * [Simon Bray](https://github.com/simonbray)
  * [Tharindu Senapathi](https://github.com/tsenapathi)
  * [Chris Barnett](https://github.com/chrisbarnettster)
  * [Björn Grüning](https://github.com/bgruening)

# References

{% bibliography --cited --prefix index-metagenomics --group_by none %}
