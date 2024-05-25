# The-Frogman-Plus-Plus-Language
This project is a part of the Project Frogman. The Frogman++ language is a C++ variant and a game scripting tool designed to be specifically used with Frogman Engine.


``` cpp
// .fxx
import <FE.core.log>
import <FE.core.string>


int32 main()
{
  /*
    All pointers are smart pointers in the Frogman++ game scripting language.
    pointers and references never dangle and they are always either null or valid.
  */
    string* p = new string;
    FE_LOG("${%s@0}", p->c_str());
    return 0;
}
```

# NOTE: The scripting tool is not available
