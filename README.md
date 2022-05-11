# CDK_ECFP_generator

This ECFP generator can be used to extract "Extended Connectivity FingerPrint" with given molecular structure (SMILES string representation as input) based on the CDK package. https://cdk.github.io/

To use this class file, simply put it in the same directory as the downloaded cdk-2.5.jar, and use shell command:
```
java -cp .;cdk-2.5.jar CDKImpl [smiles] ECFP6 3
```
