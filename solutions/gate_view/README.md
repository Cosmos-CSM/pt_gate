# *Gate View*

A solution that provides user-friendly views to handle and interact with **Gate** product.

## *Get Started*

Here you will be guided through out process of installation, usage or develop on this solution.

### **Installation & Usage**

Guide to install or use this solution in a customer shaped implementation.

> **1**. Go to your Flutter **pubspec.yaml** file and paste:

```yaml
dependencies:
  gate_view:
    git:
      ref: <version>
      url: https://github.com/Cosmos-CSM/pt_gate.git
      path: solutions/gate_view
```

*Version*: can be found in the repository view at *releases* section, for version details please check *CHANGELOG.md*.

> **2**. Create an application implementation to use in your **runApp()** method.

```dart
final class BSNGateView extends GateViewBase {

    const BSNGateView({
        super.key
    }) : super(
        signature: 'BSNGV' // Just representative, to know more about signatures please consult CSM org docs.
    );

    // Here you can call an bootstrap engine building configurations.

    
} 
```

### **Development**

Guide to setup and configure a development environment to contribute this solution.

#### **Requirements**

Technical and configuration requirements to the development environment setup.

## **Related Documentation**

Related documents to consult and get deeper knowledge about the guidelines, structures or technical details about processes, development styles, etc.

## **Contacts**

Immediate contacts for questions or requirements.

- [TM] Juan Renato Urrea Ortiz (<usuaryrenato@hotmail.com>)
