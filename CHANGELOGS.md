*Anything from 01/10/25 onwards will be documented here.*

v1.43.04
- Enumerations entirely recoded.
  - Renamed from Enumerations to SeraEnumerations as it previously featured 4 API functions: .new, .BelongsTo, .GetEnumItems, and .GetName.
  - It now features 5 API functions: .new, .isEnumItem, .isEnum, .fromRobloxEnum, and .extend.
    - Features production-ready type safety validation and export for ease of coding with IntelliSense.
      - Even better if you use this in VSCode.
    - Features serialization and deserialization via json (no, it's not overkill you absolute doofus'; in fact, it's necessary for all the great DataStore options brought to you).
    - API upon .new then enriches into: GetEnumItems, GetNames, GetValues, GetByName, GetByValue, GetByOrdinal (or known as Index), Contains, ContainsName, IsValidItem, ForEach, ToDataStore, FromDataStore, ToDataStoreName, ToDateStoreValue, FromDataStoreName, FromDataStoreValue, GetCount, GetRandom, Filter, Map, GetNext, and GetPrev.
    - Supports arrays, dictionaries, instances in the form of items, and more.
    - Clear distinction of faulty nil and intentional nil.
    - Comparative enums; equalizers, iterators, and callbacks.
    - Frozen and Cached tables for maximum performance and low usage of memory.
    - Exactly like Roblox's enumerations, but with a lot more control and flexibility.
    - Well-documented.
    - *I avoided adding GetRandomWithBias as I feel there's little use for it right now and there's definitely other ways to achieve the same effect. I will probably revisit it a later stage before publishing the Engine.*
- Entity Component System changed from Matter to JECS; a much more performant and flexibile ECS-library. 
- Introduced dynamic and more flexibile input detection library; will recode this entirely at a later date.


v1.43.10
- SeraEnumerations improvements:
  - Core API Naming Changes.
  - 4 New API functions.
  - Integrated DataStore functions with Enum type methods.
  - Querying & Access Improvements.
  - Better debugging modes and configuration options.
  - Safer DataStore methods.
  - Better type safety and validation.
  - Huge performance boost (in theory).
  - More minor integrations like ordinals to EnumItem properties, and others.
