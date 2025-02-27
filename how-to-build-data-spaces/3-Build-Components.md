# Step 3. Build Components

You can either build IDS components from scratch by using existing resources as a template, or you can reuse existing open source components available on the IDS Github repository. Already at this stage, you must ensure that the necessary requirements for a later, successful certification are met. Below you can check the existing projects that are available on IDS OS Landscape. If you are looking for external support for the implementation process, you can check the section about [Technology Implementation Partners](3-Build-Components.md#technology-implementation-partners), at the end of this page.

**Deployment Scenarios**, (_which is currently under development_) aims to consist the library of information, listing different deployment alternatives applied by IDS projects. When completed, this will be a source of inspiration and will provide technical guidance for others who would like to experiment with data spaces. This will be the place for all who is in search for best practices or exemplary deployment alternatives provided by domain experts, or those who are looking to share and improve their deployment scenarios.

### Connectors

* [Dataspace Connector](https://github.com/International-Data-Spaces-Association/DataspaceConnector) is an implementation of an IDS connector component following the IDS Reference Architecture Model.
* [Eclipse Dataspace Connector](https://projects.eclipse.org/projects/technology.dataspaceconnector) Existing open-source projects address the technical challenges of cataloguing and transferring data for a wide range of use cases. However, there is no open-source effort aimed at providing an interoperable, cross-organization framework for data sharing that is built on a common identity model and uniform policy enforcement. This project will integrate with existing data exchange technologies and provide these missing pieces to create a system for data sharing where each organization is able to exert control over how its shared data is used. You can also find more information via [EDC's YouTube Channel](https://www.youtube.com/channel/UCYmjEHtMSzycheBB4AeITHg/videos)
* [TRUE Connector](https://github.com/International-Data-Spaces-Association/true-connector) (TRUsted Engineering) Connector for the IDS (International Data Space) ecosystem.
* [Trusted Connector](https://github.com/International-Data-Spaces-Association/trusted-connector) is an Apache Karaf-based platform for the Industrial Internet of Things (IIoT).

### Metadata Broker

* [Metadata Broker Open Core](../metadata-broker-open-core/) is an implementation of an International Data Spaces (IDS) Metadata Broker, which is a registry for IDS Connector self-description documents. It is currently under development and intends to act as a reference for members of the International Data Spaces Association (IDSA) to help with the implementation of custom Broker solutions.

### Identity Management

* [DAPS ](https://github.com/International-Data-Spaces-Association/omejdn-daps)(Dynamic Attribute Provisioning Service) is the component to provide certain attributes to organizations and connectors.
* [ParIS Open Core](https://github.com/International-Data-Spaces-Association/ParIS-open-core) is an implementation of an International Data Spaces (IDS) Participant Information Service (ParIS), which is a registry for IDS Participant self-description documents. It is currently under development and intends to act as a reference for members of the International Data Spaces Association (IDSA) to help with the implementation of custom ParIS solutions.

### App Store

* [AppStore Open Core](https://github.com/International-Data-Spaces-Association/IDS-AppStore) is an implementation of the App Store by Fraunhofer FIT.

### Clearing House

* [Clearing House](https://github.com/International-Data-Spaces-Association/ids-clearing-house-core) is an implementation of the IDS Clearing House. It consists of two microservices that support the Clearing House Service, which is a prototype implementation of the Clearing House component of the Industrial Data Space.

### Frameworks & Other Resources

* [Certification Criteria Catalogue](https://github.com/International-Data-Spaces-Association/ids3c-co) International Data Spaces Certification Criteria Catalog for Components. **(Accessible only for IDS Members)**
* [DataspaceConnector UI ](https://github.com/International-Data-Spaces-Association/DataspaceConnectorUI)is a user interface for the Dataspace Connector, facilitating the operation and configuration of the connector.
* [IDS Enterprise Integration Connector](https://github.com/International-Data-Spaces-Association/IDS-Enterprise-Integration-Connector) is an implementation of an International Data Spaces (IDS) Connector that serves static content (files) using the standard message types defined in the IDS Information Model.
* [IDS Clearing House Service](https://github.com/International-Data-Spaces-Association/ids-clearing-house-service) is a prototype implementation of the Clearing House component of the Industrial Data Space. It consists of app and processors and its API is defined by the IDS-G and represents the top level service.
* [IDSCP2Rust](https://github.com/International-Data-Spaces-Association/idscp2-rust) is the Rust implementation of the IDSCP2 transport layer.
* [IDS Information Model ](https://github.com/International-Data-Spaces-Association/InformationModel)is an RDFS/OWL-ontology covering the fundamental concepts of the International Data Spaces (IDS), i.e. the types of digital contents that are exchanged by participants by means of the IDS infrastructure components.
* [IDS Messaging Services](https://github.com/International-Data-Spaces-Association/IDS-Messaging-Services) provides a lightweight implementation for IDS-Message-Handling. The IDS-Messaging-Services offer open-source functionality for sending IDS-Messages as well as interfaces for processing received IDS-Messages.
* [IDS Testbed](https://github.com/International-Data-Spaces-Association/IDS-testbed) can be used for component behaviour testing and to verify interoperability testing against IDS components (Connector, DAPS, CA, Metadata Broker). It also functions as a preparation tool for IDS certification as well as a starting point for creation of data spaces.

## Technology Implementation Partners

Are you looking for external support for technology implementation process? IDSA works together with many different organizations who serve as technology implementation partners (TIP), that will support you as you build the necessary components to succeed with certification. Your TIP will help you to bring your use case from the drawing board into the real world. You can find more information [on IDSA Website](https://internationaldataspaces.org/adopt/implementation-partners/).
