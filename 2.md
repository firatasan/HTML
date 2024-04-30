Key Elements of the Bootstrap Script
src="https://ui5.sap.com/1.114.0/resources/sap-ui-core.js": This is where the SAPUI5 core is loaded from. The src attribute points to the URL where the SAPUI5 core JS file is hosted.

data-sap-ui-libs="sap.m": The libraries needed for your application are listed here. In this case, the sap.m library, which includes the master library of SAPUI5 controls, is loaded.

data-sap-ui-theme="sap_belize": This attribute sets the theme of your SAPUI5 application. There are different themes available that you can choose from.

data-sap-ui-resourceroots='{"sap.training.sample.app": "./"}': This attribute is where you specify the roots of your resource. This helps in mapping the namespace of the controls to their physical location.
