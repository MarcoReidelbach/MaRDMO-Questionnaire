# MaRDMO-Questionnaire

This repository contains the questionnaire for the [MaRDMO-Export-Plugin](https://github.com/MarcoReidelbach/MaRDMO-Export-Plugin) developed within Task Area 4 "Interdisciplinary Mathematics" of the [Mathematical Research Data Initiative](https://www.mardi4nfdi.de/about/mission) (MaRDI). 

## Structure of the MaRDMO-Questionnaire directory

```bash
. 
├── catalog - Questionnaire Files 
│   ├── conditions.xml - individual conditions of Questionnaire 
│   ├── attributes.xml - individual domains of Questionnaire 
│   ├── optionsets.xml - individual options of Questionnaire 
│   └── catalogs.xml - individual questions for Questionnaire 
│ 
└── LICENSE.md 
```

## Usage of MaRDMO-Questionaire

Check out the [MaRDI-Export-Plugin](https://github.com/MarcoReidelbach/MaRDMO-Export-Plugin) for further information.  

## Sections, Pages and Questions of the MaRDMO-Questionnaire

The Questions listed here are not updated regularly, i.e. further questions might be introduced, others might be removed and the order is subject to change.

<b>MaRDMO Catalog</b><br>

<b>MaRDMO Operation Modus</b><br>

Operation Modus<br>
- Document or search a workflow?<br>
- Provide the name of the author of this workflow documentation.<br>
- Provide appropriate IDs for the identification of the author.<br>

<b>Workflow Search</b><br>

Workflow Search<br>
- Would you like to specify key words the research objective of the workflow should contain?<br>
- Specify the key words<br>
- Would you like to specify research disciplines the workflow should be connected with?<br>
- Select the research disciplines<br>
- Would you like to specify mathematical models, methods, software, input or output data sets the workflow should be connected with?<br>
- Select the mathematical models, methods, software, input or output data sets<br>

<b>Documentation</b><br>

Local or Public?<br>
- Local Documentation or MaRDI portal export?<br>
- Get a preview of the documentation?<br>

<b>General Description</b><br>

Problem, Objective and Procedure<br>
- Is the workflow published?<br>
- Which kind of workflow will you document?<br>
- State the Workflow Problem<br>
- State the research objective<br>
- Describe the workflow procedure<br>

Publication Information<br>
- MaRDI KG or Wikidata QID of Publication<br>
- Type of Publication<br>
- Title of Publication<br>
- Author(s) of Publication<br>
- Language of Publication<br>
- Journal of Publication<br>
- Volume of Journal<br>
- Issue of Journal<br>
- Page(s) of Journal<br>
- Date of Publication<br>

Involved Disciplines and Data Streams<br>
- Select mathematical areas, involved in your workflow, from Wikidata or MaRDI KG!<br>
- Select non-mathematical disciplines, involved in your workflow, from Wikidata or MaRDI KG!<br>
- Indicate the data streams of the workflow<br>

<b>Mathematical Model I</b><br>

Mathematical Model in MathModDB?<br>
- Select an appropriate mathematical model from MathModDB!<br>

  If not in MathModDB...<br>
  - Provide a name for the new Mathematical Model!<br>
  - Provide a description for the new Mathematical Model!<br>
  - Provide an ID for the new Mathematical Model!<br>
  - Assign appropriate properties to the new Mathematical Model.<br>
  - Select a research field related to the new Mathematical model!<br>
  - Select a Research Problem related to the new Mathematical Model!<br>
  - Should the new Mathematical Model be set in relation to others?<br>
  - Select Quantities related to the new Mathematical Model!<br>
  - Should further quantities be added?<br>
  - Select Quantity Kinds related to the new Mathematical Model!<br>
  - Should further quantity kinds be added?<br>

<b>Mathematical Model II</b><br>

Related Research Field<br>
- Provide a name for the new Research Field.<br>
- Provide a description for the new Research Field.<br>
- Provide an ID for the new Research Field.<br>

  Research Field Connections<br>
  - The new Research Field...<br>
  - ...another Research Field.<br>

Related Research Problem<br>
- Provide a name for the new Research Problem.<br>
- Provide a description for the new Research Problem.<br>
- Provide an ID for the new Research Problem.<br>
- To which Research Field belongs the new Research Problem?<br>
- Is the new Research Problem represented by the new Mathematical Model?<br>

  Research Problem Connections<br>
  - The new Research Problem...<br>
  - ...another Research Problem.<br>

Related Mathematical Model<br>
- Select a Mathematical Model related to the new Mathematical Model!<br>
- Provide a name for the next new Mathematical Model.<br>
- Provide a description for the next new Mathematical Model.<br>
- Provide an ID for the next new Mathematical Model<br>
- Assign appropriate properties to the next new Mathematical Model.<br>
- Select a Research Problem related to the next new Mathematical Model?<br>

  Mathematical Model Connections<br>
  - The existing / next new Mathematical Model...<br>
  - ...another Mathematical Model.<br>

Related Quantity<br>
- Provide a name for the new Quantity.<br>
- Provide a description for the new Quantity.<br>
- Provide an ID for the new Quantity.<br>
- Assign appropriate properties to the new Quantity.<br>

  Quantity Connections<br>
  - The new Quantity...<br>
  - ...another Quantity.<br>

Related Quantity Kind<br>
- Provide a name for the new Quantity Kind.<br>
- Provide a description for the new Quantity Kind!<br>
- Provide an ID for the new Quantity Kind.<br>
- Assign appropriate properties to the new Quantity Kind.<br>

  Quantity Kind Connections<br>
  - The new Quantity Kind...<br>
  - ...another Quantity Kind.<br>

  Quantity / Quantity Kind Connections<br>
  - The new Quantity Kind...<br>
  - ...a Quantity.<br>

Related Mathematical Formulation<br>
- Select a Mathematical Formulation related to the new Mathematical Model!<br>
- Provide a name for the new Mathematical Formulation.<br>
- Provide a description for the new Mathematical Model.<br>
- Provide an ID for the new Mathematical Formulation.<br>
- Assign appropriate properties to the new Mathematical Formulation.<br>
- Provide the formula of the new Mathematical Formulation<br>

  Terms of the Mathematical Formulation<br>
  - Symbol of the Term<br>
  - Encoded Quantity / Quantity Kind<br>

  Contains / Contained in Mathematical Formulation<br>
  - The new Mathematical Formulation...<br>
  - ...another Mathematical Formulation.<br>

  Contained in Mathematical Model<br>
  - The new Mathematical Formulation...<br>
  - ...a Mathematical Model.<br>

  Mathematical Formulation Connection<br>
  - The new Mathematical Formulation...<br>
  - ...another Mathematical Formulation.<br>

Related Task<br>
- Select a Task related to the new Mathematical Model!<br>
- Provide a name for the new Task.<br>
- Provide a description for the new Task.<br>
- Provide an ID for the new Task.<br>
- Select a Mathematical Model applied by the new Task.<br>
- To which Research Problem belongs the new Task?<br>
- Which category does this task fall into?<br>

  Contains Mathematical Formulation<br>
  - The new Task...<br>
  - ...a Mathematical Formulation.<br>

  Contains Quantity / Quantity Kind<br>
  - The new Task...<br>
  - ...a Quantity / Quantity Kind.<br>

  Task Connection<br>
  - The new Task...<br>
  - ...another Task.<br>

Related Publication<br>
- Provide the DOI the Publication<br>

  Publication Relation<br>
  - The publication...<br>
  - ...a previously defined entity.<br>

<b>Process Information</b><br>

Software<br>
- Select an appropriate software from Wikidata or MaRDI KG!<br>
- Provide a name for the software.<br>
- Provide a description for the software.<br>
- Provide the programming language(s) the software is based on.<br>
- Provide an appropriate reference.<br>
- Provide the version of the software used<br>
- Provide the dependencies of the software used<br>
- Is the software versioned?<br>
- Is the software published?<br>
- Is the software documented?<br>

Hardware (Computational Workflow)<br>
- Provide an identifier for the hardware<br>
- Provide a name for the hardware<br>
- Provide the processor name of the hardware<br>
- Provide the existing compiler of the hardware<br>
- State the number of nodes of the hardware<br>
- State the number of cores of the hardware<br>

Devices ((Measurement) Data Analysis Workflow)<br>
- Provide an identifier for the device<br>
- Provide a name for the device<br>
- Provide a description for the device<br>
- State the version of the device<br>
- State the part number of the device<br>
- State the serial number of the device<br>
- State the location of the device<br>
- State the available software of the device<br>

Data Sets<br>
- Select an appropriate input data set from Wikidata or MaRDI KG!<br>
- Provide a name for the input data set.<br>
- Provide a description for the input data set.<br> 
- Provide an appropriate reference.<br>
- Provide the size of the input data set.<br>
- Provide the data structure of the input data set.<br>
- Provide the representation format of the input data set.<br>
- Provide the exchange format of the input data set.<br>
- Is the input data set binary or text?<br>
- Is the format of the input data set proprietary?<br>
- Is a publication of the input data set necessary?<br>
- Is an archiving of the input data set necessary?<br>

Methods<br>
- Select an appropriate method from Wikidata or MaRDI KG!<br>
- Provide a name for the method.<br>
- Provide a description for the method.<br>
- Provide the main subject of the method.<br>
- Provide the defining formulas of the method.<br>
- Provide an appropriate reference.<br>
- Provide the relevant parameter(s) of the method<br>
- Provide the software(s) realizing or implementing the method<br>

Process steps<br>
- Provide a name for the process step<br>
- Provide a description for the process step<br>
- State the inputs of the process step<br>
- State the output of the process step<br>
- State the methods used in this process step<br>
- State the parameter relevant for this process step<br>
- State the environment of the process step<br>
- State the mathematical area of the process step<br>

<b>Reproducibility</b><br>

Reproducibility (Computational Workflow)<br>
- Is the workflow mathematically reproducible?<br>
- Is the runtime reproducibie?<br>
- Are the results reproducible?<br>
- Is a reproduction on the original hardware possible?<br>
- Is a reproduction on other hardware possible?<br>
- Transferability to<br>

Reproducibility ((Measurement) Data Analysis Workflow)<br>
- Experiments reproducible on the original devices/instruments/hardware?<br>
- Experiments reproducible on other devices/instruments/hardware?<br>
- Transferability of the experiments to<br>


