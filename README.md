## Guid Based Reference
A component for giving Game Objects a GUID and a class to create references to objects in any Scene by GUID.

### Summary
This GUID can then be used to reference an object even if it is another Scene, not loaded yet, or otherwise not easy to directly reference.

### How to Use:
* Clone repository to the folder on local machine
* Go to Pacakage Manager -> Add Package From Disk -> select the folder
* Add a GuidComponent to any object you want to be able to reference.
* In any code that needs to be able to reference objects by GUID, add a GuidReference field.
* GuidReference.gameObject will then return the GameObject if it is loaded, otherwise null.

License - Please see LICENSE.md in this repository
