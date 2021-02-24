# MagicalRecord-tvOS
A hacked version of MagicalRecord 3.0 for tvOS 

Simply drag this into your project and import the header like this: 

#import <MagicalRecord/MagicalRecord.h>

Feel free to take this code and use or re-use - its not my code anyway, it belongs to MagicalPanda, I offer this version with a few minor changes needed to run on tvOS. 

Note that I had to disable one feature which has no tvOS equivilent, cant remember which, but it doesn't matter since you can't use that feature anyway, whatever it is. 

Note that on tvOS there is no persistent core-data store. Data must be re-loaded into core-data on each app launch. Thus, I use this to set up the core data stack: 

[MagicalRecord setupCoreDataStackWithInMemoryStoreNamed:@"MyStoreName"];

If you have questions, email me and I may be able to help. But probably not, I post this as-is for other developers not as a commercial or professional exercise. 

Good luck,

