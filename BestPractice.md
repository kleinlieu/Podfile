1. Use ARC to stop worrying about memory management.
2: No longer need to declare instance variables for your properties.
3. No longer need to @synthesize your properties. Auto-synthesize will automatically make the backing instance variable and prefix it with an underscore.
4. It’s better to place your instance variables in the @implementation section than in the public interface.
5. You no longer need forward declarations for your private methods and IBAction methods.
6. Rather than making a “(Private)” category, use a class extension.
7. Put your IBOutlet properties in the class extension.
8. You can list the protocols that your class conforms to in the class extension, rather than in the public interface.
9. The class extension can re-declare a readonly property to be a readwrite property inside the .m file.
10. You don’t need to #import UIKit and other system frameworks if you already import them in the Prefix.pch file.
11. Use categories to add new functionality to existing classes, even those from UIKit and Foundation.
12. Use blocks for enumerating through arrays and dictionaries, and to replace delegates where that makes sense.
13. You can now use the @ symbol for number literals, @[ ] for arrays and @{ } for dictionaries.
14. You can use [ ] notation to subscript arrays and dictionaries, and even implement this functionality in your own classes.