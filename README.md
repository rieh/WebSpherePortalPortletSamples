WebSpherePortalPortletSamples
=============================

OPENNTF

    This project is an OpenNTF project, and is available under the Apache License V2.0.  
    All other aspects of the project, including contributions, defect reports, discussions, 
    feature requests and reviews are subject to the OpenNTF Terms of Use - available at 
    http://openntf.org/Internal/home.nsf/dx/Terms_of_Use.

BUILD

	mvn clean package
    
INSTALL
	
	./ConfigEngine.sh install-paa -DPAALocation=WebSpherePortalPortletSamplesSetup-paa.zip
	./ConfigEngine.sh deploy-paa -DappName=com.ibm.portal.samples-WebSpherePortalPortletSamplesSetup
	
UNINSTALL

	./ConfigEngine.sh remove-paa -DappName=com.ibm.portal.samples-WebSpherePortalPortletSamplesSetup
	./ConfigEngine.sh uninstall-paa -DappName=com.ibm.portal.samples-WebSpherePortalPortletSamplesSetup
	./ConfigEngine.sh delete-paa -DappName=com.ibm.portal.samples-WebSpherePortalPortletSamplesSetup