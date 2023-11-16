# [Coding-Assistant](https://assetstore.unity.com/packages/slug/267341?aid=1011lrgAB)
🔥 One-click generation of scripts, component fields, and event listener functions, with automatic handling of event listening, removal, component field binding, and referencing.      
🤞Allows developers to focus more on implementing business logic without spending excessive time writing repetitive, standardized code. Eliminates the need for manual component field binding and referencing, saving valuable time⌚ and effort, resulting in improved development efficiency💨.

😖Whether this plugin is useful to me?😖

😩Have you encountered any of the following troubles?😩     
1️⃣. Creating countless scripts and repeatedly writing code with a structure similar to the following:     
~~~
[SerializeField] private Button button;        
[SerializeField] private Slider slider;        
[SerializeField] private InputField inputField;        
[SerializeField] private Toggle toggle;        
[SerializeField] private Dropdown dropdown;        
... ...     
button.onClick.AddListener(OnButtonClicked);       
slider.onValueChanged.AddListener(OnSliderValueChanged);
inputField.onValueChanged.AddListener(OnInputFieldValueChanged);
toggle.onValueChanged.AddListener(OnToggleValueChanged);
dropdown.onValueChanged.AddListener(OnDropdownValueChanged);
... ...
button.onClick.RemoveListener(OnButtonClicked);
slider.onValueChanged.RemoveListener(OnSliderValueChanged);
inputField.onValueChanged.RemoveListener(OnInputFieldValueChanged);
toggle.onValueChanged.RemoveListener(OnToggleValueChanged);
dropdown.onValueChanged.RemoveListener(OnDropdownValueChanged);
... ...
private void OnButtonClicked() { }
private void OnSliderValueChanged(float val) { }
private void OnInputFieldValueChanged(string val) { }
private void OnToggleValueChanged(bool val) { }
private void OnDropdownValueChanged(int val) { }
~~~
2️⃣. In the Hierarchy, dragging and assigning components one by one to the corresponding fields in the script.     

🎉 🎉Congratulations!       
😀 😀This plugin perfectly solves your trouble!     

⭐Features:     
* One-click generation of scripts, component fields, and event listener functions.        
* Automatic addition and removal of event listener functions for fields like Button's OnClick event.      
* Edit and configure scripts, including namespace, generation location, etc.      
* It can automatically generate script fields by recognizing them through @(FieldMaker). Additionally, it offers the option to selectively generate fields by choosing from a list of all components available in the built-in interface.     
* Clean and user-friendly interface for field editing and selection.      
* Automatically bind all code fields with one-click.      
* Lists all scripts and their fields that can be bound.       
* Support for ignore list (namespaces).       
* Fuzzy fault tolerance and other configurations are supported.       
