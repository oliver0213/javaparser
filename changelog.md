Next Release (Version 3.23.1)
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/186?closed=1)

### Added
### Changed
### Deprecated
### Removed
### Fixed

* `record` may be used as variable name in Java 16 (PR [#3362](https://github.com/javaparser/javaparser/pull/3362) by [@koppor](github.com/koppor/))

### Security




Version 3.23.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/185?closed=1)

### Added

* Improving `toString` on CSM classes (PR [#3315](https://github.com/javaparser/javaparser/pull/3315) by [@jlerbsc](https://github.com/jlerbsc))
* Add test case for issue #2210 Resolution of Method References (PR [#3310](https://github.com/javaparser/javaparser/pull/3310) by [@jlerbsc](https://github.com/jlerbsc))
* Implemented method reference resolution on expressions (PR [#3307](https://github.com/javaparser/javaparser/pull/3307) by [@maartenc](https://github.com/maartenc))
* Define if a field is volatile through the ResolvedFieldDeclaration interface - from issue #3240 (PR [#3276](https://github.com/javaparser/javaparser/pull/3276) by [@jlerbsc](https://github.com/jlerbsc))
* Implemented logic for internalTypes in `JavaParserAnnotationDeclaration` and `JavassistAnnotationDeclaration` (PR [#3215](https://github.com/javaparser/javaparser/pull/3215) by [@4everTheOne](https://github.com/4everTheOne))

### Changed

* Check if ancestor also for super class (PR [#3324](https://github.com/javaparser/javaparser/pull/3324) by [@ReallyLiri](https://github.com/ReallyLiri))
* Remove useless  instanceof usage in Type (PR [#3311](https://github.com/javaparser/javaparser/pull/3311) by [@jlerbsc](https://github.com/jlerbsc))
* Fix Java 11+ AST postprocessing (PR [#3302](https://github.com/javaparser/javaparser/pull/3302) by [@matozoid](https://github.com/matozoid))
* Move duplicate code to JavaParserTypeAdapter (PR [#3267](https://github.com/javaparser/javaparser/pull/3267) by [@maartenc](https://github.com/maartenc))
* Improved performance when resolving types for big source files (PR [#3265](https://github.com/javaparser/javaparser/pull/3265) by [@maartenc](https://github.com/maartenc))
* Optimizations for Node class (CPU time and Memory usage) (PR [#3233](https://github.com/javaparser/javaparser/pull/3233) by [@4everTheOne](https://github.com/4everTheOne))
* Fix Javadoc comment * escaping problem. (PR [#3221](https://github.com/javaparser/javaparser/pull/3221) by [@matozoid](https://github.com/matozoid))
* Remove broken link (PR [#2912](https://github.com/javaparser/javaparser/pull/2912) by [@mernst](https://github.com/mernst))

### Fixed

* Preserving field order when getting the fields declared from a ReferenceType (PR [#3342](https://github.com/javaparser/javaparser/pull/3342) by [@jlerbsc](https://github.com/jlerbsc))
* Fix String Index out of range in TextBlockLiteralExpr (PR [#3337](https://github.com/javaparser/javaparser/pull/3337) by [@134ARG](https://github.com/134ARG))
* Fixed prettyprinting new switch-statements (and switch-expressions). (PR [#3335](https://github.com/javaparser/javaparser/pull/3335) by [@kozsik](https://github.com/kozsik))
* Fix pretty printing of generic records (PR [#3334](https://github.com/javaparser/javaparser/pull/3334) by [@twistedsquare](https://github.com/twistedsquare))
* Fix issue #3317 Comment in the middle of a multi-line single statement (PR [#3318](https://github.com/javaparser/javaparser/pull/3318) by [@jlerbsc](https://github.com/jlerbsc))
* Fix issue 3296 LexicalPreservation bug for array brackets (PR [#3316](https://github.com/javaparser/javaparser/pull/3316) by [@jlerbsc](https://github.com/jlerbsc))
* Fixes Issue #3308 -- stackoverflow when resolving the `FieldAccessExpr` of an `ArrayAccessExpr` (PR [#3312](https://github.com/javaparser/javaparser/pull/3312) by [@MysterAitch](https://github.com/MysterAitch))
* Fix StackOverflow when resolving ClassOrInterfaceType of nested ObjectCreationExpr (PR [#3279](https://github.com/javaparser/javaparser/pull/3279) by [@maartenc](https://github.com/maartenc))
* ResolvedMethods from javassist never had exceptions (PR [#3264](https://github.com/javaparser/javaparser/pull/3264) by [@maartenc](https://github.com/maartenc))
* Issue 3064 conditional nested lambda (PR [#3238](https://github.com/javaparser/javaparser/pull/3238) by [@si-e](https://github.com/si-e))
* Further optimization in resolving in StatementContext (PR [#3185](https://github.com/javaparser/javaparser/pull/3185) by [@Col-E](https://github.com/Col-E))
* Improve type resolution for duplicate names (PR [#3012](https://github.com/javaparser/javaparser/pull/3012) by [@thejk](https://github.com/thejk))

### Developer Changes

* chore(deps): update dependency org.mockito:mockito-core to v3.12.4 (PR [#3350](https://github.com/javaparser/javaparser/pull/3350) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.mockito:mockito-core to v3.12.3 (PR [#3349](https://github.com/javaparser/javaparser/pull/3349) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update codecov/codecov-action action to v2.0.3 (PR [#3348](https://github.com/javaparser/javaparser/pull/3348) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.mockito:mockito-core to v3.12.2 (PR [#3347](https://github.com/javaparser/javaparser/pull/3347) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.mockito:mockito-core to v3.12.1 (PR [#3345](https://github.com/javaparser/javaparser/pull/3345) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.mockito:mockito-core to v3.12.0 (PR [#3344](https://github.com/javaparser/javaparser/pull/3344) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.apache.maven.plugins:maven-scm-plugin to v1.11.3 (PR [#3339](https://github.com/javaparser/javaparser/pull/3339) by [@renovate[bot]](https://github.com/apps/renovate))
* Bump codecov/codecov-action from 1.5.2 to 2.0.2 (PR [#3326](https://github.com/javaparser/javaparser/pull/3326) by [@dependabot[bot]](https://github.com/apps/dependabot))
* chore(deps): update dependency org.mockito:mockito-core to v3.11.2 (PR [#3305](https://github.com/javaparser/javaparser/pull/3305) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.assertj:assertj-core to v3.20.2 (PR [#3297](https://github.com/javaparser/javaparser/pull/3297) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.assertj:assertj-core to v3.20.0 (PR [#3295](https://github.com/javaparser/javaparser/pull/3295) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.apache.maven.plugins:maven-dependency-plugin to v3.2.0 (PR [#3294](https://github.com/javaparser/javaparser/pull/3294) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.mockito:mockito-core to v3.11.1 (PR [#3293](https://github.com/javaparser/javaparser/pull/3293) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update codecov/codecov-action action to v1.5.2 (PR [#3287](https://github.com/javaparser/javaparser/pull/3287) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.mockito:mockito-core to v3.11.0 (PR [#3285](https://github.com/javaparser/javaparser/pull/3285) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update actions/cache action to v2.1.6 (PR [#3280](https://github.com/javaparser/javaparser/pull/3280) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.apache.maven.plugins:maven-javadoc-plugin to v3.3.0 (PR [#3270](https://github.com/javaparser/javaparser/pull/3270) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update junit5 monorepo to v5.7.2 (PR [#3262](https://github.com/javaparser/javaparser/pull/3262) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.apache.maven.plugins:maven-gpg-plugin to v3 (PR [#3250](https://github.com/javaparser/javaparser/pull/3250) by [@renovate[bot]](https://github.com/apps/renovate))

### :heart: Contributors

Thank You to all contributors who worked on this release!

* [@maartenc](https://github.com/maartenc)
* [@kozsik](https://github.com/kozsik)
* [@ReallyLiri](https://github.com/ReallyLiri)
* [@mernst](https://github.com/mernst)
* [@matozoid](https://github.com/matozoid)
* [@Col-E](https://github.com/Col-E)
* [@134ARG](https://github.com/134ARG)
* [@MysterAitch](https://github.com/MysterAitch)
* [@si-e](https://github.com/si-e)
* [@thejk](https://github.com/thejk)
* [@twistedsquare](https://github.com/twistedsquare)
* [@jlerbsc](https://github.com/jlerbsc)
* [@4everTheOne](https://github.com/4everTheOne)



Version 3.22.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/184?closed=1)

### Added

* Recover wrong statements no only to ';', but to '}' (not including) as well (PR [#3247](https://github.com/javaparser/javaparser/pull/3247) by [@32kda](https://github.com/32kda))

### Fixed

* update features.md -- fixed release version and date of records support, status of java 16 sealed classes to 2nd preview, and java 17 features (PR [#3263](https://github.com/javaparser/javaparser/pull/3263) by [@MysterAitch](https://github.com/MysterAitch))
* fixes #3255 -- bugfix grammar case when using `record` to as an identifier (PR [#3256](https://github.com/javaparser/javaparser/pull/3256) by [@MysterAitch](https://github.com/MysterAitch))
* Fixes issue #3113 -- Arrow missing in Switch Expression + jumbled up in LexicalPreservingPrinter (PR [#3235](https://github.com/javaparser/javaparser/pull/3235) by [@Zoom1111](https://github.com/Zoom1111))
* Handle possibility of tokens not being available (PR [#3231](https://github.com/javaparser/javaparser/pull/3231) by [@mernst](https://github.com/mernst))

### Developer Changes

* chore(deps): update dependency org.mockito:mockito-core to v3.10.0 (PR [#3259](https://github.com/javaparser/javaparser/pull/3259) by [@renovate[bot]](https://github.com/apps/renovate))
* Bump codecov/codecov-action from 1 to 1.5.0 (PR [#3258](https://github.com/javaparser/javaparser/pull/3258) by [@dependabot[bot]](https://github.com/apps/dependabot))
* Bump actions/create-release from 1 to 1.1.4 (PR [#3257](https://github.com/javaparser/javaparser/pull/3257) by [@dependabot[bot]](https://github.com/apps/dependabot))

### :heart: Contributors

Thank You to all contributors who worked on this release!

* [@32kda](https://github.com/32kda)
* [@MysterAitch](https://github.com/MysterAitch)
* [@Zoom1111](https://github.com/Zoom1111)
* [@mernst](https://github.com/mernst)



Version 3.22.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/183?closed=1)


### API or Behaviour Change

* Implemented isAssignableBy for VoidType - now return `false` instead of throwing `UnsupportedOperationException` (PR [#3197](https://github.com/javaparser/javaparser/pull/3197) by [@4everTheOne](https://github.com/4everTheOne))
* fixed ellipsis and doublecolon to be categorised as separators not operators (fixes #2897) (PR [#2924](https://github.com/javaparser/javaparser/pull/2924) by [@MysterAitch](https://github.com/MysterAitch))

### Added

* Update parser configuration and validators to include the release of java 16, and java 17 being in development (PR [#3222](https://github.com/javaparser/javaparser/pull/3222) by [@MysterAitch](https://github.com/MysterAitch))
* Adding convenient methods to find out if a method is a variable/fixed arity method (PR [#3196](https://github.com/javaparser/javaparser/pull/3196) by [@jlerbsc](https://github.com/jlerbsc))
* Fix issue #3173: Add isAnnotation() and asAnnotation() methods for ResolvedTypeDeclaration (PR [#3187](https://github.com/javaparser/javaparser/pull/3187) by [@deadlocklogic](https://github.com/deadlocklogic))
* Record support (compilation / parsing only, solving to follow separately) (PR [#3022](https://github.com/javaparser/javaparser/pull/3022) by [@MysterAitch](https://github.com/MysterAitch))

### Changed

* Implemented isAssignableBy for VoidType - now return `false` instead of throwing `UnsupportedOperationException` (PR [#3197](https://github.com/javaparser/javaparser/pull/3197) by [@4everTheOne](https://github.com/4everTheOne))
* Simplify how to find the package name from AstResolutionUtils (PR [#3193](https://github.com/javaparser/javaparser/pull/3193) by [@jlerbsc](https://github.com/jlerbsc))
* Type resolution improvment (PR [#3189](https://github.com/javaparser/javaparser/pull/3189) by [@jlerbsc](https://github.com/jlerbsc))
* Memory optimization for JarTypeSolver (Up to 42% less memory) (PR [#3188](https://github.com/javaparser/javaparser/pull/3188) by [@4everTheOne](https://github.com/4everTheOne))
* Fixes #3048 (`JavaParserSymbolDeclaration#localVar` returning old declaration) and adds tests for `JavaParserSymbolDeclaration` (PR [#3049](https://github.com/javaparser/javaparser/pull/3049) by [@4everTheOne](https://github.com/4everTheOne))

### Fixed

* Fix issue #3244 OrphanComment in BlockStmt not appearing (PR [#3245](https://github.com/javaparser/javaparser/pull/3245) by [@jlerbsc](https://github.com/jlerbsc))
* fix Log.error() throwing NullPointerException (PR [#3243](https://github.com/javaparser/javaparser/pull/3243) by [@CD4017BE](https://github.com/CD4017BE))
* fixed ellipsis and doublecolon to be categorised as separators not operators (fixes #2897) (PR [#2924](https://github.com/javaparser/javaparser/pull/2924) by [@MysterAitch](https://github.com/MysterAitch))

### Developer Changes

* Include and use a Maven wrapper (PR [#3254](https://github.com/javaparser/javaparser/pull/3254) by [@MysterAitch](https://github.com/MysterAitch))
* chore(deps): update dependency org.javassist:javassist to v3.28.0-ga (PR [#3249](https://github.com/javaparser/javaparser/pull/3249) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.jacoco:jacoco-maven-plugin to v0.8.7 (PR [#3246](https://github.com/javaparser/javaparser/pull/3246) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update actions/cache action to v2.1.5 (PR [#3226](https://github.com/javaparser/javaparser/pull/3226) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update dependency org.mockito:mockito-core to v3.9.0 (PR [#3224](https://github.com/javaparser/javaparser/pull/3224) by [@renovate[bot]](https://github.com/apps/renovate))
* chore(deps): update actions/setup-java action to v2 (PR [#3220](https://github.com/javaparser/javaparser/pull/3220) by [@renovate[bot]](https://github.com/apps/renovate))
* Update javaparser copyright headers (PR [#3212](https://github.com/javaparser/javaparser/pull/3212) by [@jlerbsc](https://github.com/jlerbsc))
* Update readme template so that #3096 becomes permanent (PR [#3210](https://github.com/javaparser/javaparser/pull/3210) by [@MysterAitch](https://github.com/MysterAitch))
* Improve tests on `getAllAncestors` method (PR [#3209](https://github.com/javaparser/javaparser/pull/3209) by [@jlerbsc](https://github.com/jlerbsc))
* Fix surefire configuration to allow jacoco to run correctly on JSS tests (PR [#3208](https://github.com/javaparser/javaparser/pull/3208) by [@MysterAitch](https://github.com/MysterAitch))

### :heart: Contributors

Thank You to all contributors who worked on this release!

* [@MysterAitch](https://github.com/MysterAitch)
* [@CD4017BE](https://github.com/CD4017BE)
* [@jlerbsc](https://github.com/jlerbsc)
* [@deadlocklogic](https://github.com/deadlocklogic)
* [@4everTheOne](https://github.com/4everTheOne)

Version 3.21.2
------------------
**v3.21.1 released as 3.21.2 without change**

Version 3.21.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/182?closed=1)

### Added

* Implemented logic for isAssignableBy in JavassistInterfaceDeclaration (PR [#3170](https://github.com/javaparser/javaparser/pull/3170) by [@4everTheOne](https://github.com/4everTheOne))
* Added additional tests to cover isAssignableBy method in JavassistClassDeclaration (PR [#3169](https://github.com/javaparser/javaparser/pull/3169) by [@4everTheOne](https://github.com/4everTheOne))

### Changed

* Update changelog (PR [#3178](https://github.com/javaparser/javaparser/pull/3178) by [@MysterAitch](https://github.com/MysterAitch))
* Minor performance improvement on getCanonicalName method call (PR [#3166](https://github.com/javaparser/javaparser/pull/3166) by [@jlerbsc](https://github.com/jlerbsc))

### Fixed

* Fix Issue #1950 Unambigous ambiguity call with <Void> generics and lambda's (PR [#3168](https://github.com/javaparser/javaparser/pull/3168) by [@jlerbsc](https://github.com/jlerbsc))
* Refactor the javassist implementation to delegate to the typesolver instead of using its own classpool (PR [#3167](https://github.com/javaparser/javaparser/pull/3167) by [@maartenc](https://github.com/maartenc))
* Fixed name resolution in casted lambda expressions (PR [#3165](https://github.com/javaparser/javaparser/pull/3165) by [@maartenc](https://github.com/maartenc))
* Fix issue #3159 JavaParserSymbolDeclaration is used to represent variables, but #isVariable() always returns false (PR [#3160](https://github.com/javaparser/javaparser/pull/3160) by [@jlerbsc](https://github.com/jlerbsc))
* Fix wrong author attribution in changelog for #3072 (PR [#3155](https://github.com/javaparser/javaparser/pull/3155) by [@Col-E](https://github.com/Col-E))
* Fixed #3136 - ThisExpr isn't resolved correctly when it is in the scope of an ObjectCreationExpr (PR [#3137](https://github.com/javaparser/javaparser/pull/3137) by [@deadlocklogic](https://github.com/deadlocklogic))
* Fix race condition in JavaParserTypeSolver (PR [#3091](https://github.com/javaparser/javaparser/pull/3091) by [@4everTheOne](https://github.com/4everTheOne))

### Developer Changes

* Publish to OSSRH rather than Bintray (PR [#3180](https://github.com/javaparser/javaparser/pull/3180) by [@MysterAitch](https://github.com/MysterAitch))
* Remove unused JUnit Pioneer dependency (PR [#3179](https://github.com/javaparser/javaparser/pull/3179) by [@MysterAitch](https://github.com/MysterAitch))
* Verify builds test correctly under JDK16 (PR [#3175](https://github.com/javaparser/javaparser/pull/3175) by [@MysterAitch](https://github.com/MysterAitch))
* update renovate to include "dependencies" label on PRs (PR [#3174](https://github.com/javaparser/javaparser/pull/3174) by [@MysterAitch](https://github.com/MysterAitch))
* chore(deps): update dependency com.google.guava:guava to v30.1.1-jre (PR [#3172](https://github.com/javaparser/javaparser/pull/3172) by [@renovate[bot]](https://github.com/apps/renovate))

### :heart: Contributors

Thank You to all contributors who worked on this release!

* [@maartenc](https://github.com/maartenc)
* [@MysterAitch](https://github.com/MysterAitch)
* [@jlerbsc](https://github.com/jlerbsc)
* [@deadlocklogic](https://github.com/deadlocklogic)
* [@4everTheOne](https://github.com/4everTheOne)
* [@Col-E](https://github.com/Col-E)



Version 3.20.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/181?closed=1)

### Added
* Issue #2991 - Added support for Iterables in CombinedTypeSolver
  (PR [#3033](https://github.com/javaparser/javaparser/pull/3033), by [@4everTheOne](https://github.com/4everTheOne))
* Implemented logic for getAllFields in Annotations
  (PR [#3097](https://github.com/javaparser/javaparser/pull/3097), by [@4everTheOne](https://github.com/4everTheOne))
### Changed
* Issue #2717 - Removed "empty" label from break statement and added additional test for BreakStmt
  (PR [#3109](https://github.com/javaparser/javaparser/pull/3109), by [@4everTheOne](https://github.com/4everTheOne))
* Issue #2708 - Improvement to the generated code (removal of redundant casts, and additions of `@Override`)
  (PR [#3124](https://github.com/javaparser/javaparser/pull/3124), by [@4everTheOne](https://github.com/4everTheOne))
* Performance improvement on ResolvedReferenceTypeDeclaration.isJavaLangObject()
  (PR [#3125](https://github.com/javaparser/javaparser/pull/3125), by [@jlerbsc](https://github.com/jlerbsc))
* Optimization to avoid systematically creating a class from javassist when the class has already been created
  (PR [#3126](https://github.com/javaparser/javaparser/pull/3126), by [@jlerbsc](https://github.com/jlerbsc))
* Bump jbehave-core from 4.8.1 to 4.8.2
  (PR [#3043](https://github.com/javaparser/javaparser/pull/3043), by [@dependabot](https://github.com/dependabot))
* Bump assertj-core from 3.18.1 to 3.19.0
  (PR [#3047](https://github.com/javaparser/javaparser/pull/3047), by [@dependabot](https://github.com/dependabot))
* Bump okhttp from 4.9.0 to 4.9.1
  (PR [#3054](https://github.com/javaparser/javaparser/pull/3054), by [@dependabot](https://github.com/dependabot))
* Bump actions/cache from v2 to v2.1.4
  (PR [#3070](https://github.com/javaparser/javaparser/pull/3070), by [@dependabot](https://github.com/dependabot))
* Bump mockito-core from 3.6.28 to 3.8.0
  (PR [#3110](https://github.com/javaparser/javaparser/pull/3110), by [@dependabot](https://github.com/dependabot))
* Bump junit from 4.13.1 to 4.13.2
  (PR [#3129](https://github.com/javaparser/javaparser/pull/3129), by [@dependabot](https://github.com/dependabot))
### Fixed
* Issue #3038 and Issue #3071 - Hanging when certain names are resolved
  (PR [#3072](https://github.com/javaparser/javaparser/pull/3072), by [@col-e](https://github.com/Col-E))
* Javadoc fixes
  (PR [#3082](https://github.com/javaparser/javaparser/pull/3082), by [@mernst](https://github.com/mernst))
* Update readme with correct Java support versions
  (PR [#3096](https://github.com/javaparser/javaparser/pull/3096), by [@MaartenGDev](https://github.com/MaartenGDev))
* Issue #3106 - Wrong descriptor for primitive type long
  (PR [#3107](https://github.com/javaparser/javaparser/pull/3107), by [@jlerbsc](https://github.com/jlerbsc))


Version 3.19.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/180?closed=1)

### Added
* Adding test case on PrettyPrinter indentation
  (PR [#2950](https://github.com/javaparser/javaparser/pull/2950), by [@jlerbsc](https://github.com/jlerbsc))
* Adding interface Printable for printer
  (PR [#2971](https://github.com/javaparser/javaparser/pull/2971), by [@jlerbsc](https://github.com/jlerbsc))
* Major update for pretty print, adding interfaces for printer configuration, printer, ... and deprecated old PrettyPrinter API 
  (PR [#2974](https://github.com/javaparser/javaparser/pull/2974), by [@jlerbsc](https://github.com/jlerbsc))
* Adding method descriptor resolution closes #2059
  (PR [#2976](https://github.com/javaparser/javaparser/pull/2976), by [@jlerbsc](https://github.com/jlerbsc))
* Adding management of the poly and standalone expression
  (PR [#2994](https://github.com/javaparser/javaparser/pull/2994), by [@jlerbsc](https://github.com/jlerbsc))
* Add test case for issue #1770 UnaryExpr failing to resolve BITWISE_COMPLEMENT operator   
  (PR [#3005](https://github.com/javaparser/javaparser/pull/3005), by [@jlerbsc](https://github.com/jlerbsc))
* Created additional validators to differentiate between enabling standard and preview features   
  (PR [#3015](https://github.com/javaparser/javaparser/pull/3015), by [@MysterAitch](https://github.com/MysterAitch))
* Added additional tests to TypeSolvers   
  (PR [#3046](https://github.com/javaparser/javaparser/pull/3046), by [@4everTheOne](https://github.com/4everTheOne))
* Improved JavaParserTypeVariableDeclaration tests   
  (PR [#3059](https://github.com/javaparser/javaparser/pull/3059), by [@4everTheOne](https://github.com/4everTheOne))
* Improved coverage for resolved declarations and fixed inconsistencies between them   
  (PR [#3062](https://github.com/javaparser/javaparser/pull/3062), by [@4everTheOne](https://github.com/4everTheOne))
* Additional GenericVisitorWithDefaults and VoidVisitorWithDefaults tests   
  (PR [#3067](https://github.com/javaparser/javaparser/pull/3067), by [@4everTheOne](https://github.com/4everTheOne))
* Additional tests for hash code visitors   
  (PR [#3068](https://github.com/javaparser/javaparser/pull/3068), by [@4everTheOne](https://github.com/4everTheOne))
* Add unit tests to issue #3074 Unable to delete .jar files after parsing and using symbol solver (re: #3074)   
  (PR [#3076](https://github.com/javaparser/javaparser/pull/3076), by [@jlerbsc](https://github.com/jlerbsc))
### Changed
* Minor refactoring regarding indentation management
  (PR [#2969](https://github.com/javaparser/javaparser/pull/2969), by [@jlerbsc](https://github.com/jlerbsc))
* Minor refactoring regarding indentation management (part2)
  (PR [#2970](https://github.com/javaparser/javaparser/pull/2970), by [@jlerbsc](https://github.com/jlerbsc))
* Minor refactoring moving Indentation class to configuration package - preparation for other refactoring on Printer
  (PR [#2972](https://github.com/javaparser/javaparser/pull/2972), by [@jlerbsc](https://github.com/jlerbsc))
* Bump guava from 30.0-jre to 30.1-jre
  (PR [#2977](https://github.com/javaparser/javaparser/pull/2977), by [@dependabot](https://github.com/dependabot))
* Refactoring: relocation of boxing/unboxing methods
  (PR [#2983](https://github.com/javaparser/javaparser/pull/2983), by [@jlerbsc](https://github.com/jlerbsc))
* Improve boxing/unboxing unit tests and remove useless code in isUnbox...
  (PR [#2984](https://github.com/javaparser/javaparser/pull/2984), by [@jlerbsc](https://github.com/jlerbsc))
* Bump jbehave-core from 4.7 to 4.8.1
  (PR [#2989](https://github.com/javaparser/javaparser/pull/2989), by [@dependabot](https://github.com/dependabot))
* Add JVM memory settings for surefire (seems that forked mode is the default running mode)
  (PR [#2999](https://github.com/javaparser/javaparser/pull/2999), by [@jlerbsc](https://github.com/jlerbsc))
* Move unit test Issue2592Test because it's not related to symbol solver
  (PR [#3000](https://github.com/javaparser/javaparser/pull/3000), by [@jlerbsc](https://github.com/jlerbsc))
* Manage memory on test suite (clear internal cache to release memory)
  (PR [#3001](https://github.com/javaparser/javaparser/pull/3001), by [@jlerbsc](https://github.com/jlerbsc))
* Remove the PhantomNodeLogic that generates memory issues when LexicalPreservingPrinter is used. Phantom node is now an attribut of each node. This is an optimization of the JP memory usage.
  (PR [#3002](https://github.com/javaparser/javaparser/pull/3002), by [@jlerbsc](https://github.com/jlerbsc))
* Make the visit order of ModifierVisitor more consistent.
  (PR [#3011](https://github.com/javaparser/javaparser/pull/3011), by [@mernst](https://github.com/mernst))
* Link to the specification, not to a random blog.
  (PR [#3013](https://github.com/javaparser/javaparser/pull/3013), by [@mernst](https://github.com/mernst))
* Minor refactoring change call to getScope().isPresent() to hasScope()
  (PR [#3026](https://github.com/javaparser/javaparser/pull/3026), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #3050 - Minor improvement to thread safety
  (PR [#3052](https://github.com/javaparser/javaparser/pull/3052), by [@jlerbsc](https://github.com/jlerbsc))
### Deprecated
* `PhantomNodeLogic` is now deprecated, with the logic now being handled by the node itself.
  (PR [#3002](https://github.com/javaparser/javaparser/pull/3002), by [@jlerbsc](https://github.com/jlerbsc))
### Fixed
* Fix issue on pretty configuration change
  (PR [#2979](https://github.com/javaparser/javaparser/pull/2979), by [@jlerbsc](https://github.com/jlerbsc))
* Fix trivial poly expression lambda, method reference, and parenthesized expressions
  (PR [#2981](https://github.com/javaparser/javaparser/pull/2981), by [@jlerbsc](https://github.com/jlerbsc))
* Partially fix the issue #1743 ConditionalExpr resolves to wrong type
  (PR [#2982](https://github.com/javaparser/javaparser/pull/2982), by [@jlerbsc](https://github.com/jlerbsc))
* Partially fix issue #1743 ConditionalExpr resolves to wrong type - trying to manage reference condition expression but lub (least upper bound) function is not yet implemented
  (PR [#3004](https://github.com/javaparser/javaparser/pull/3004), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #2987 StackOverflow error 
  (PR [#3006](https://github.com/javaparser/javaparser/pull/3006), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #1774 Ensure the correct type is calculated for all binary expressions and add unary primitive promotion   
  (PR [#3007](https://github.com/javaparser/javaparser/pull/3007), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #2995 Cannot resolve ClassOrInterfaceType of nested ObjectCreationExpr  
  (PR [#3019](https://github.com/javaparser/javaparser/pull/3019), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #1634 Missing EOL when add imports if the class not exist imports before 
  (PR [#3020](https://github.com/javaparser/javaparser/pull/3020), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #3024 methodCallExpr.resolve() StackOverflowError 
  (PR [#3025](https://github.com/javaparser/javaparser/pull/3025), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #3027 Unable to parse class with generic parameter using JavaParserTypeSolver 
  (PR [#3029](https://github.com/javaparser/javaparser/pull/3029), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #3030 NoSuchElementException when solving type 
  (PR [#3031](https://github.com/javaparser/javaparser/pull/3031), by [@4everTheOne](https://github.com/4everTheOne))
* Issue 3028  -- Changed MethodResolutionLogic to deal with multiple candidates with varargs when varargs have not been specified in the call.
  (PR [#3032](https://github.com/javaparser/javaparser/pull/3032), by [@greggers123](https://github.com/greggers123))
* Issue #1834 Improving annotation support: Implement ResolvedAnnotationDeclaration#getDefaultValue()
  (PR [#3055](https://github.com/javaparser/javaparser/pull/3055), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #3057 Removed redundant definition of method to inherit from super
  (PR [#3058](https://github.com/javaparser/javaparser/pull/3058), by [@4everTheOne](https://github.com/4everTheOne))
* Issue #3074 Unable to delete .jar files after parsing
  (PR [#3075](https://github.com/javaparser/javaparser/pull/3075), by [@jlerbsc](https://github.com/jlerbsc))
* Issue #3083 Fix choosing the most specific method in case of java.lang.Object argument type
  (PR [#3084](https://github.com/javaparser/javaparser/pull/3084), by [@jlerbsc](https://github.com/jlerbsc))


Version 3.18.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/179?closed=1)

### Added
* Add a convenient method (hasRange) to the interface NodeWithRange  
    (PR [#2929](https://github.com/javaparser/javaparser/pull/2929), by [@jlerbsc](https://github.com/jlerbsc))
* Add test case to issue 1017 LambdaExpr left side too permissive
    (PR [#2946](https://github.com/javaparser/javaparser/pull/2946), by [@jlerbsc](https://github.com/jlerbsc))
* Added Pattern Matching for instanceof (Java 14 preview, Java 15 second preview, Java 16 targeted release)
    (PR [#2654](https://github.com/javaparser/javaparser/pull/2654), by [@MysterAitch](https://github.com/MysterAitch))
* Added java 15 (latest released) and java 16 (bleeding edge) language level options, incl. some validators / post processors / configuration options
    (PR [#2959](https://github.com/javaparser/javaparser/pull/2959), by [@MysterAitch](https://github.com/MysterAitch))
### Changed
* Minor change in PrettyPrinterConfiguration : adding default char in enum IndentType
    (PR [#2948](https://github.com/javaparser/javaparser/pull/2948), by [@jlerbsc](https://github.com/jlerbsc))
* Minor refactoring rename interface Printable to Stringable. Something that has a printable form. I.e., it can be converted to a user-facing String
    (PR [#2949](https://github.com/javaparser/javaparser/pull/2949), by [@jlerbsc](https://github.com/jlerbsc))
* Adding interface Printable for printer
    (PR [#2950](https://github.com/javaparser/javaparser/pull/2950), by [@jlerbsc](https://github.com/jlerbsc))
* Minor refactoring in ResolvedReferenceType and add corresponding tests 
    (PR [#2955](https://github.com/javaparser/javaparser/pull/2955), by [@jlerbsc](https://github.com/jlerbsc))
* Tweak the property generator to add imports when generating and improve the typecastinggenerator's error message
    (PR [#2957](https://github.com/javaparser/javaparser/pull/2957), by [@MysterAitch](https://github.com/MysterAitch))
* Bump mockito-core from 3.6.0 to 3.6.28
    (PR [#2942](https://github.com/javaparser/javaparser/pull/2942), by dependabot
### Removed
* Removed .travis.yml -- per #2919 
    (PR [#2958](https://github.com/javaparser/javaparser/pull/2958), by [@MysterAitch](https://github.com/MysterAitch))
### Fixed
* Issue 2909 Improving search for the most relevant declaration of the specified class  
    (PR [#2927](https://github.com/javaparser/javaparser/pull/2927), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2926 NoSuchElementException in PhantomNodeLogic after adding node  
    (PR [#2930](https://github.com/javaparser/javaparser/pull/2930), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2909 try different bottom / up and try with type solver strategies 
    (PR [#2931](https://github.com/javaparser/javaparser/pull/2931), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2936 Triggering observer notifications for the NodeList iterator
    (PR [#2938](https://github.com/javaparser/javaparser/pull/2938), by [@MysterAitch](https://github.com/MysterAitch))
* Issue 2065 Problem resolving type of lambda with Math method invocation inside 
    (PR [#2945](https://github.com/javaparser/javaparser/pull/2945), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2740 Issue related to a method call in an anonymous class on a field with a private visibility
    (PR [#2947](https://github.com/javaparser/javaparser/pull/2947), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2951 Cannot solve function with List<byte[]> argument defined in jar 
    (PR [#2952](https://github.com/javaparser/javaparser/pull/2952), by [@qzchenwl](https://github.com/qzchenwl))
* Issue 2781 Resolve Stack overflow occurs when the name of the interface implemented by the class is the same as the name of the internal class 
    (PR [#2956](https://github.com/javaparser/javaparser/pull/2956), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2953 UnsolvedSymbolException throw when resolving method in enum class implement in interface by default.  
    (PR [#2954](https://github.com/javaparser/javaparser/pull/2954), by [@qzchenwl](https://github.com/qzchenwl))
* Fixed MethodCallExprContext generic parameter issue. (NullType must not fail matchTypeParameters)
    (PR [#2939](https://github.com/javaparser/javaparser/pull/2939), by [@zcbbpo](https://github.com/zcbbpo))
* Issue 2943 UnsolvedSymbolException thrown on `Stream.<func>(<some lambda>)` 
    (PR [#2961](https://github.com/javaparser/javaparser/pull/2961), by [@qzchenwl](https://github.com/qzchenwl))
* Issue 1945 JavaParser choking on multiple generic method calls on the same line 
    (PR [#2966](https://github.com/javaparser/javaparser/pull/2966), by [@jlerbsc](https://github.com/jlerbsc))


Version 3.17.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/178?closed=1)
### Fixed
* BEHAVIOUR CHANGE: Fix ArrayType brackets precedence
    (PR [#2758](https://github.com/javaparser/javaparser/pull/2758), by [@iTakeshi](https://github.com/iTakeshi))
* BEHAVIOUR CHANGE: Issue 2535 Comments within method missing indentation  
    (PR [#2918](https://github.com/javaparser/javaparser/pull/2918), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2290 Removing the second instance of a cloned statement within a block fails
    (PR [#2892](https://github.com/javaparser/javaparser/pull/2892), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2393 Apply difference in node text after if condition replacement
    (PR [#2895](https://github.com/javaparser/javaparser/pull/2895), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2406 Symbol solver fails to solve generic array type 
    (PR [#2896](https://github.com/javaparser/javaparser/pull/2896), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2489 SymbolSolver choosing wrong method after resolving 
    (PR [#2898](https://github.com/javaparser/javaparser/pull/2898), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2062 Type inference issue for method arguments 
    (PR [#2900](https://github.com/javaparser/javaparser/pull/2900), by [@jlerbsc](https://github.com/jlerbsc))
* Fix LOOKAHEAD for ReferenceType 
    (PR [#2904](https://github.com/javaparser/javaparser/pull/2904), by [@mernst](https://github.com/mernst))
* Issue 2578 Orphaned Comments exist but not printed on unrelated change to AST 
    (PR [#2916](https://github.com/javaparser/javaparser/pull/2916), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2909 Unexpected result when solving an outer class reference 
    (PR [#2914](https://github.com/javaparser/javaparser/pull/2914), by [@jlerbsc](https://github.com/jlerbsc))
* Issue 2909 Improving how to resolve inner classes  
    (PR [#2920](https://github.com/javaparser/javaparser/pull/2920), by [@jlerbsc](https://github.com/jlerbsc))
    (PR [#2921](https://github.com/javaparser/javaparser/pull/2921), by [@jlerbsc](https://github.com/jlerbsc))
* Ensure spaces between annotations and types for lexical-preserving printing
    (PR [#2795](https://github.com/javaparser/javaparser/pull/2918), by [@jwaataja](https://github.com/jwaataja))

### Changed
* Updated dependencies, and dependabot config
    (PR [#2893](https://github.com/javaparser/javaparser/pull/2893), by [@mysteraitch](https://github.com/mysteraitch))
    (PR [#2902](https://github.com/javaparser/javaparser/pull/2902), by Dependabot)
* Issue 2613 Auto update the version in the readme 
    (PR [#2903](https://github.com/javaparser/javaparser/pull/2903), by [@mysteraitch](https://github.com/mysteraitch))
* Fix jacoco and enable codecov.io action
    (PR [#2906](https://github.com/javaparser/javaparser/pull/2906), by [@mysteraitch](https://github.com/mysteraitch))
* Minor refactoring of binary numeric promotion 
    (PR [#2915](https://github.com/javaparser/javaparser/pull/2915), by [@jlerbsc](https://github.com/jlerbsc))
* Testcases for logical and/or 
    (PR [#2907](https://github.com/javaparser/javaparser/pull/2907), by [@mysteraitch](https://github.com/mysteraitch))
* Format and document the grammar 
    (PR [#2901](https://github.com/javaparser/javaparser/pull/2901), by [@mysteraitch](https://github.com/mysteraitch))
    (PR [#2913](https://github.com/javaparser/javaparser/pull/2913), by [@mernst](https://github.com/mernst))


Version 3.16.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/177?closed=1)
* ADDED: Created MANY test cases for older issues resolved but not directly linked/closed.
    (PRs
    [#2838](https://github.com/javaparser/javaparser/pull/2838), 
    [#2842](https://github.com/javaparser/javaparser/pull/2842), 
    [#2843](https://github.com/javaparser/javaparser/pull/2843), 
    [#2852](https://github.com/javaparser/javaparser/pull/2852), 
    [#2853](https://github.com/javaparser/javaparser/pull/2853), 
    [#2854](https://github.com/javaparser/javaparser/pull/2854), 
    [#2855](https://github.com/javaparser/javaparser/pull/2855), 
    [#2867](https://github.com/javaparser/javaparser/pull/2867), 
    [#2868](https://github.com/javaparser/javaparser/pull/2868), 
    [#2862](https://github.com/javaparser/javaparser/pull/2862), 
    [#2873](https://github.com/javaparser/javaparser/pull/2873), 
    by [@jlerbsc](https://github.com/jlerbsc)
    )
* ADDED: Added helper method to `ResolvedPrimitiveType.java` which checks if it is a boolean
    (PR [#2856](https://github.com/javaparser/javaparser/pull/2856), by [@jlerbsc](https://github.com/jlerbsc))
* ADDED: Added helper method to `ResolvedPrimitiveType.java` which returns all numeric types
    (PR [#2858](https://github.com/javaparser/javaparser/pull/2858), by [@jlerbsc](https://github.com/jlerbsc))
* ADDED/CHANGED: Minor refactoring - formatting code and adding convenient methods to `TypeHelper` and `ResolvedPrimitveType`
    (PR [#2860](https://github.com/javaparser/javaparser/pull/2860), by [@jlerbsc](https://github.com/jlerbsc))
* ADDED: Allow the symbol resolver for a `SymbolSolverCollectionStrategy` to be set via the given parser configuration
    (PR [#2864](https://github.com/javaparser/javaparser/pull/2864), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: `MethodResolutionLogic.findMostApplicable` not return correct symbol reference when resolving overloaded method
    (PR [#2866](https://github.com/javaparser/javaparser/pull/2866), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: Updated `AbstractSymbolResolutionTest.java` with better `@BeforeEach`/`@AfterEach`  
    (PR [#2871](https://github.com/javaparser/javaparser/pull/2871), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: `TypeResolver` fails on method with args to static imported fields
    (PR [#2872](https://github.com/javaparser/javaparser/pull/2872), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: Fix issue Resolution error for non-generic constructor if generic constructor declared
    (PR [#2874](https://github.com/javaparser/javaparser/pull/2874), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: Fix issue Fails to calculate the type of a generic return type constructed from a Primitive type
    (PR [#2875](https://github.com/javaparser/javaparser/pull/2875), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: Fix issue Can't get qualified signature of a resolved method inside a Constant Enum declaration 
    (PR [#2876](https://github.com/javaparser/javaparser/pull/2876), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: Fix issue Constructor resolution error for overloaded variadic constructor
    (PR [#2877](https://github.com/javaparser/javaparser/pull/2877), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: Fix issue Unable to find the constructor declaration when the argument list contains multiple `Optional.empty()` for different `Optional<T>`
    (PR [#2880](https://github.com/javaparser/javaparser/pull/2880), by [@jlerbsc](https://github.com/jlerbsc))
* FIXED: Fix issue Solving symbol as value in the case where the scope is a constraint
    (PR [#2883](https://github.com/javaparser/javaparser/pull/2883), by [@jlerbsc](https://github.com/jlerbsc))


Version 3.16.2
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/176?closed=1)
* FIXED: Enhanced the handling of line separator, introducing an enum `LineSeparator` that can be used.
    (PR [#2685](https://github.com/javaparser/javaparser/pull/2685), by [@MysterAitch](https://github.com/MysterAitch))
* FIXED: The generated metamodel classes now have the `@Generated` annotation 
    (PR [#2706](https://github.com/javaparser/javaparser/pull/2706), by [@MysterAitch](https://github.com/MysterAitch))
* various other bugfixes and enhancements


Version 3.16.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/175?closed=1)
* FIXED: Fixed typo
    (PR [#2697](https://github.com/javaparser/javaparser/pull/2697), by [@hfreeb](https://github.com/hfreeb))


Version 3.16.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/174?closed=1)

There are two breaking changes within this release. 
If you would like assistance with upgrading, get in touch.

* FIXED: Edits to the value of a string value are now correctly handled for use with Lexical Preservation 
    (PR [#2646](https://github.com/javaparser/javaparser/pull/2646), by [@lemoncurry](https://github.com/lemoncurry))
* FIXED: Edits to the value of other literal values also now handled 
    (PR [#2679](https://github.com/javaparser/javaparser/pull/2679), by [@MysterAitch](https://github.com/MysterAitch))
* BREAKING CHANGE: Tokens relating to literal values now have the category of `JavaToken.Category.LITERAL` (previously `JavaToken.Category.KEYWORD`) 
    (PR [#2679](https://github.com/javaparser/javaparser/pull/2679), by [@MysterAitch](https://github.com/MysterAitch))
* FIXED: Add symbol solver support for variadic parameters given zero or more than one argument, and when an array is given
    (PR [#2675](https://github.com/javaparser/javaparser/pull/2675), by [@hfreeb](https://github.com/hfreeb))
* CHANGED: Added the keyword `synchronized` to `JavaParserFacade#get`. This is specifically in response to #2668 - JavaParser is not otherwise threadsafe.  
    (PR [#2694](https://github.com/javaparser/javaparser/pull/2694), by [@MysterAitch](https://github.com/MysterAitch))
* BREAKING CHANGE: The following methods now return `Optional<>` _(as do all classes which implement/extend them)_:
    `ResolvedClassDeclaration#getSuperClass()`, 
    `ResolvedReferenceType#getTypeDeclaration()`.  
    _Note that Converting to use optional should be as simple as adding `.get()`, given that any cases where returning `Optional.empty()` causes problems would  have also previously triggered a `NullPointerException`. 
    You might also use `.orElseThrow()`._  
    (PR [#2693](https://github.com/javaparser/javaparser/pull/2693), by [@MysterAitch](https://github.com/MysterAitch))
* CHANGED: Added some temporary logic to allow tests to use slightly different expected results based on the version of java used _(e.g. `java.lang.Object.registerNatives()` removed in JDK14)_  
    (PR [#2637](https://github.com/javaparser/javaparser/pull/2637), by [@EFregnan](https://github.com/EFregnan))
* FIXED: Fix resolving overloaded methods of external types  
    (PR [#2687](https://github.com/javaparser/javaparser/pull/2687), by [@maartenc](https://github.com/maartenc))
* FIXED: Fix resolving method references on expressions other than ReferenceType::methodname  
    (PR [#2674](https://github.com/javaparser/javaparser/pull/2674), by [@maartenc](https://github.com/maartenc))



Version 3.15.22
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/173?closed=1)
* REVERT: Rollback of upgrade to `ph-javacc-maven-plugin` from v4.1.3 to v4.1.2 
    _(this undoes the transitive dependency update `parser-generator-cc` from v1.1.2 to v1.1.1, which appears to have isuse with handling tokens longer than the buffer length)_  
    ([#2646](https://github.com/javaparser/javaparser/pull/2646))
* ADDED: Support resolving an enum's `valueOf` method
    ([#2652](https://github.com/javaparser/javaparser/pull/2652))
* FIXED: Fixed build warning -- bnd-maven-plugin flagging missing id 
    ([#2605](https://github.com/javaparser/javaparser/pull/2605))
* FIXED: Fixed cases where nodes added after a trailing comment would incorrectly be added to the same line (thus be part of the comment)
    ([#2646](https://github.com/javaparser/javaparser/pull/2646))
* FIXED: Fixed resolving overloaded static method references (e.g. `String::valueOf` in a stream map/filter)
    ([#2662](https://github.com/javaparser/javaparser/pull/2662))


Version 3.15.21
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/172?closed=1)

* DEPRECATED: Deprecated and documented `JarTypeSolver#getJarTypeSolver(String)`, with a view to later removal.
    ([#2598](https://github.com/javaparser/javaparser/pull/2598))
    ([#2622](https://github.com/javaparser/javaparser/pull/2622))
* FIXED: Fix issue #2552 : UnsupportedOperationException caused by resolving inner annotation
    ([#2553](https://github.com/javaparser/javaparser/pull/2553))
* FIXED: Parents of `NodeList`s now correctly retain their parent when a child is replaced 
    ([#2594](https://github.com/javaparser/javaparser/pull/2594))
* FIXED: Fix JavaParserClassDeclaration canBeAssignedTo() to not cause a recursion when a node is its own parent (e.g. `java.lang.Object`)
    ([#2608](https://github.com/javaparser/javaparser/pull/2608))
* FIXED: Fix replacing an expression preceded by a comment (`LexicalPreservation` would previously throw an `UnsupportedOperation`)
    ([#2611](https://github.com/javaparser/javaparser/pull/2611))
* FIXED: The collection strategies now correctly take into account the parser configuration that is passed in via the constructor.
    ([#2619](https://github.com/javaparser/javaparser/pull/2619))


Version 3.15.20
------------------
_skipped_

Version 3.15.19
------------------
_skipped_

Version 3.15.18
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/170?closed=1)

* CHANGED: Dependencies should now all be up-to-date. 
  ([#2572](https://github.com/javaparser/javaparser/pull/2572) / [#2581](https://github.com/javaparser/javaparser/pull/2581))
  - Note that the JavaCC update introduced a breaking change that now requires a StreamProvider to be passed a charset if using an InputStream source.
* FIXED (possible CHANGED/BREAKING): 
  Improvements have been made to method `PositionUtils#nodeContains()` for clarity and precision in behaviour.
  ([#2502](https://github.com/javaparser/javaparser/pull/2502))
  - It is believed that there are no changes to behaviour, but if you do see anything please do reach out.
  - See some additional commentary/thoughts in #2502
* FIXED: Resolving super methodcalls in anonymous inner classes (fixes #1962)
    ([#2585](https://github.com/javaparser/javaparser/pull/2585))
* ADDED: `NodeList#getFirst(): Optional<Node>`
    ([#2502](https://github.com/javaparser/javaparser/pull/2502))
* ADDED: `NodeList#getLast(): Optional<Node>`
    ([#2502](https://github.com/javaparser/javaparser/pull/2502))

Version 3.15.17
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/169?closed=1)

* CHANGED: Merged symbol solver modules, for java 9 module compatibility
    ([#2564](https://github.com/javaparser/javaparser/pull/2564))
* CHANGED: Renamed the pretty printer configuration option `isSpacesBetweenOperators` to `isSpaceAroundOperators` 
    ([#2555](https://github.com/javaparser/javaparser/pull/2555))

Version 3.15.16
------------------
_Version skipped_

Version 3.15.15
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/168?closed=1)

* Often requested, finally implemented by [ReallyLiri](https://github.com/ReallyLiri):
configurable cache sizes for the symbol solver.

Version 3.15.14 (buggy)
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/167?closed=1)

* a suggestion for a new Javadoc parsing API was merged too quickly,
causing issues parsing Javadoc while parsing Java normally. 

Version 3.15.13
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/166?closed=1)

Version 3.15.12
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/165?closed=1)

Version 3.15.11
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/164?closed=1)

Version 3.15.10
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/163?closed=1)

Version 3.15.9
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/161?closed=1)

Version 3.15.8
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/160?closed=1)

Version 3.15.7
------------------
* BREAKING: Range.overlapsWith works slightly different now.

[issues resolved](https://github.com/javaparser/javaparser/milestone/162?closed=1)

Version 3.15.6
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/159?closed=1)

Version 3.15.5
------------------
* BREAKING: bugs have been fixed in how SourceRoot configures parsing,
so behaviour may change (which can be fixed by setting configuration on SourceRoot correctly.)

[issues resolved](https://github.com/javaparser/javaparser/milestone/158?closed=1)

Version 3.15.4
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/157?closed=1)

Version 3.15.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/156?closed=1)

Version 3.15.2
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/155?closed=1)

Version 3.15.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/154?closed=1)

Version 3.15.0
------------------
- The funny "PI" version number messed up the release order in the maven site,
    so here is a new minor release.
[issues resolved](https://github.com/javaparser/javaparser/milestone/153?closed=1)

Version 3.14.16
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/152?closed=1)

Version 3.14.159265359
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/151?closed=1)

Version 3.14.14 
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/150?closed=1)

Version 3.14.13
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/149?closed=1)

Version 3.14.12
------------------
- BREAKING: `NodeWithConstructors` has been merged into `NodeWithMembers`,
so if you don't have a very specific need to only find nodes that support constructors,
you can use `NodeWithMembers` instead.

[issues resolved](https://github.com/javaparser/javaparser/milestone/148?closed=1)

Version 3.14.11
------------------
- BREAKING: the pseudo-language levels have been turned into constants with the same name in the same place.
With a little luck everything will keep compiling.

[issues resolved](https://github.com/javaparser/javaparser/milestone/147?closed=1)

Version 3.14.10 (buggy!)
------------------
- BREAKING: Java 13: `break` no longer has an expression, this was part of a language preview in Java 12
and has been removed in Java 13.
- BREAKING: Java 13: `YieldStatement` and the keyword `yield` have been added.
This means the token numbers have changed, and this affects serialization.
If you rely on serialized tokens, be sure to deserialize with your current version and serialize with this version.
- Java 13: `TextBlockLiteralExpr` has been added.
- This release is broken because no identifier called `yield` can be used.

[issues resolved](https://github.com/javaparser/javaparser/milestone/146?closed=1)

Version 3.14.9
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/145?closed=1)

Version 3.14.8
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/144?closed=1)

Version 3.14.7
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/143?closed=1)

Version 3.14.6 (oops, failed)
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/142?closed=1)

Version 3.14.5
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/141?closed=1)

Version 3.14.4
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/140?closed=1)

Version 3.14.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/139?closed=1)

Version 3.14.2
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/138?closed=1)

Version 3.14.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/137?closed=1)

Version 3.14.0
------------------
* BREAKING: `SuperExpr` and `ThisExpr` used to have an `Expression classExpr`.
this has been tightened to `Name typeName` which is more specific and easier to use.
Checking if the expression is a `FieldAccessExpr` or `NameExpr` is no longer needed. 

[issues resolved](https://github.com/javaparser/javaparser/milestone/136?closed=1)

Version 3.13.10
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/135?closed=1)

Version 3.13.9
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/134?closed=1)

Version 3.13.8 (failed)
------------------
(release failed)

Version 3.13.7
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/133?closed=1)

Version 3.13.6
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/132?closed=1)

Version 3.13.5
------------------
* "BREAKING": `ReferenceType.getDirectAncestors()` no longer returns `java.lang.Object` when called on a `ReferenceType` of `java.lang.Object`.
This remedies infinite recursions in certain edge cases. If you relied on the old behavior, you have to add a `ReferenceType` instance of `java.lang.Object`
to the List returned by `ReferenceType.getDirectAncestors()` yourself.

[issues resolved](https://github.com/javaparser/javaparser/milestone/131?closed=1)

Version 3.13.4
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/130?closed=1)

Version 3.13.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/129?closed=1)

Version 3.13.2
------------------
* Version 3.13.0 and 3.13.1 contain rather bad bugs that have been fixed here.

[issues resolved](https://github.com/javaparser/javaparser/milestone/128?closed=1)

Version 3.13.1 (buggy!)
------------------
* Slightly breaking: most parameters to Log methods now take consumers to avoid evaluating them when not necessary. 

[issues resolved](https://github.com/javaparser/javaparser/milestone/127?closed=1)

Version 3.13.0 (buggy!)
------------------
* "BREAKING": The static `JavaParser.parse...` methods have moved to `StaticJavaParser.parse...`!

[issues resolved](https://github.com/javaparser/javaparser/milestone/126?closed=1)

Version 3.12.0
------------------
* "BREAKING": all deprecated code was removed.
If you don't know what to do, try version 3.11.0 and read the Javadoc for the deprecated methods.
It tells you what to use instead.

[issues resolved](https://github.com/javaparser/javaparser/milestone/124?closed=1)

Version 3.11.0
------------------
* BREAKING: `SwitchEntryStmt` is now `SwitchEntry`, because it was never a statement.
* BREAKING: a case in a switch can now have multiple labels,
so `SwitchEntry` no longer has an `Expression label`,
but a `NodeList<Expression> label`.
* This completes *parsing* support for Java 12.
Symbol resolution is still to be done.

[issues resolved](https://github.com/javaparser/javaparser/milestone/123?closed=1)

Version 3.10.2
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/122?closed=1)

Version 3.10.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/121?closed=1)

Version 3.10.0
------------------
* slightly breaking: besides `break;` and `break [label];` there is now `break [expression];` like
`break 1+2;` or `break "bye!";` . That means that `BreakStmt` no longer has a `label`,
it has a `value` which is of type `Expression`.
This is to prepare for Java 12 switch expressions.
You can find the details in the Javadoc.

[issues resolved](https://github.com/javaparser/javaparser/milestone/120?closed=1)

Version 3.9.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/119?closed=1)

Version 3.9.0
------------------
* MAJOR BREAKAGE: modifiers (like public, static, transient) used to be a special case:
they were enums stored in an EnumSet.
This meant they were not true `Node`s, had to be treated in a special way, and missed some information.
This has now been corrected in [PR 1975](https://github.com/javaparser/javaparser/pull/1975). 

[issues resolved](https://github.com/javaparser/javaparser/milestone/118?closed=1)

Version 3.8.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/117?closed=1)

Version 3.8.2
------------------
* slightly breaking: `ObjectCreationExpr` no longer gets a diamond when constructed with the default constructor.

[issues resolved](https://github.com/javaparser/javaparser/milestone/116?closed=1)

Version 3.8.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/114?closed=1)

Version 3.8.0
------------------
* A Unicode preprocessing filter is now available again.

[issues resolved](https://github.com/javaparser/javaparser/milestone/113?closed=1)

Version 3.7.1
------------------
* slightly breaking: the enum constants in JsonToken are now capitalized.
* slightly breaking: [some obscure methods in the symbol solver changed](https://github.com/javaparser/javaparser/pull/1922) 

[issues resolved](https://github.com/javaparser/javaparser/milestone/115?closed=1)

Version 3.7.0
------------------
* BREAKING: `ForeachStmt` is now correctly capitalized: `ForEachStmt`
* BREAKING: when using modules, everything that was called `...Statement` is now correctly called `...Directive`

[issues resolved](https://github.com/javaparser/javaparser/milestone/112?closed=1)

Version 3.6.27
------------------
* The Json serialization now serializes more fields,
which *should* not impact existing code.

[issues resolved](https://github.com/javaparser/javaparser/milestone/111?closed=1)

Version 3.6.26
------------------
* BREAKING: Node.getData now throws an exception if the data was not set before.
This can be rewritten by checking with Node.containsData before doing getData.

[issues resolved](https://github.com/javaparser/javaparser/milestone/110?closed=1)

Version 3.6.25
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/109?closed=1)

Version 3.6.24
------------------
* `findAncestor(type, predicate)` is now available

[issues resolved](https://github.com/javaparser/javaparser/milestone/108?closed=1)

Version 3.6.23
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/107?closed=1)

Version 3.6.22
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/106?closed=1)

Version 3.6.21
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/105?closed=1)

Version 3.6.20
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/104?closed=1)

Version 3.6.19
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/103?closed=1)

Version 3.6.18
------------------
* Parsing Java 11 is now supported.
* Running on Java 11 is now supported.
* Building on JDK 11 is NOT yet supported.

[issues resolved](https://github.com/javaparser/javaparser/milestone/101?closed=1)

Version 3.6.17
------------------
* A new artifact was added: javaparser-core-serialization.
It contains a JSON serializer, and might get more serializers in the future.

[issues resolved](https://github.com/javaparser/javaparser/milestone/100?closed=1)

Version 3.6.16
------------------
* BREAKING: some parts of the module syntax used `Type` where they should have used `Name`.
This is now fixed, but your code may need to be adapted if you are parsing modules.

[issues resolved](https://github.com/javaparser/javaparser/milestone/99?closed=1)

Version 3.6.15
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/98?closed=1)

Version 3.6.14
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/97?closed=1)

Version 3.6.13
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/96?closed=1)
* JavaParserFacade.getType now can also handle NameExpr referring to types 
while before they were not supported.
See [issue #1491](https://github.com/javaparser/javaparser/issues/1491#issuecomment-403277963)

Version 3.6.12
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/95?closed=1)

Version 3.6.10 & Version 3.6.11
------------------
* A mixup during the release put all the issues in the same milestone:

[issues resolved](https://github.com/javaparser/javaparser/milestone/94?closed=1)

Version 3.6.9
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/93?closed=1)

Version 3.6.8
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/92?closed=1)
* Intellij Idea project files were deleted from the repository,
so if you have a clone of the JP source, your local files will be deleted as well.
Save anything you want to keep.

Version 3.6.7
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/91?closed=1)

Version 3.6.6
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/90?closed=1)
* You can now configure the parser inside JavaParserTypeSolver.

Version 3.6.5
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/89?closed=1)
* Be aware of annotations or indents looking slightly different when output!

Version 3.6.4
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/88?closed=1)

Version 3.6.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/87?closed=1)

Version 3.6.2
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/86?closed=1)

Version 3.6.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/85?closed=1)
* BREAKING: `SymbolSolverQuickSetup` has been removed in favor of `ProjectRoot` and `SymbolSolverCollectionStrategy`.

Version 3.6.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/84?closed=1)
* @daanschipper added `ProjectRoot` which is used for analysing and storing project structure.
* Upgraded version from 3.5.20 to 3.6.0 because people got tired of seeing 3.5.

Version 3.5.20
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/83?closed=1)
* Thanks to @daanschipper for the PR :-)

Version 3.5.19
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/82?closed=1)

Version 3.5.18
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/81?closed=1)

Version 3.5.17
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/80?closed=1)

Version 3.5.16
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/79?closed=1)

Version 3.5.15
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/78?closed=1)
* Java 10 support is complete.
* BREAKING: Java language level support has changed to make Java 10 support possible.
[Here's a little article about it](https://matozoid.github.io/2017/04/11/enable-java-9-support.html)

Version 3.5.14
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/77?closed=1)
* Java 10's `var` can now be parsed and will be turned into a `VarType` node.
It can not be resolved yet.
* `NodeList` now has a pretty complete set of `...First` and `...Last` methods.
Thanks stephenramthun !

Version 3.5.13
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/76?closed=1)
* The Javadoc parser has received a lot of attention.

Version 3.5.12
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/75?closed=1)
* Thanks to un0btanium for fixing the readme file!

Version 3.5.11
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/74?closed=1)
* BREAKING: `AssignExpr.Operator.AND` is now `AssignExpr.Operator.BINARY_AND`.
* BREAKING: `AssignExpr.Operator.OR` is now `AssignExpr.Operator.BINARY_OR`.
* `getPrimaryTypeName` and `getPrimaryType` give access to the type that has the same name as the file it came from.
* Enums will now get their constants aligned vertically if there are more than five.
* You can now convert between `AssignExpr.Operator` and `AssignExpr.Operator` if you like.

Version 3.5.10
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/73?closed=1)
* JavaSymbolSolver is now in the same project as JavaParser, meaning they get released together from now on.
* LexicalPreservingPrinter has had a big speed optimization.

Version 3.5.9
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/72?closed=1)
* BREAKING: the very confusing constructor `NodeList(Node)` (which sets the parent) was removed.
* To avoid using the int type for token kinds, use the new `JavaToken.Kind` enum.
It can convert to and from the int kind. 

Version 3.5.8
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/71?closed=1)
* the module name is now set to com.github.javaparser.core

Version 3.5.7
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/70?closed=1)

Version 3.5.6
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/69?closed=1)
* `toSomeType()` methods have been added for many types that give more functional access to a subtype.
* BETA: the below work on Java Symbol Solver is still ongoing.

Version 3.5.5
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/68?closed=1)
* SourceRoot is now silent by default - look at the Log class if you want to change that. 
* BETA: the below work on Java Symbol Solver is still ongoing.

Version 3.5.4
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/67?closed=1)
* BETA: the below work on Java Symbol Solver is still ongoing.

Version 3.5.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/66?closed=1)
* Unicode escapes (`\u1234`) are now retained in the AST,
    but they are now only allowed in comments, string and character literals, and identifiers. 
* BETA: the below work on Java Symbol Solver is still ongoing.

Version 3.5.2
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/65?closed=1)
* The pretty printer now cleans up Javadoc comments.
* BETA: the below work on Java Symbol Solver is still ongoing.

Version 3.5.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/64?closed=1)
* BETA: the below work on Java Symbol Solver is still ongoing.

Version 3.5.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/63?closed=1)
* A functional visitor API has been added. See [PR 1195](https://github.com/javaparser/javaparser/pull/1195) for now.
* Build is working again on Windows thanks to Leonardo Herrera.
* The pretty printer now has an option to order imports, also thanks to Leonardo Herrera.
* Receiver parameters are now well-supported instead of being a hack. See [issue 1194](https://github.com/javaparser/javaparser/pull/1194) for a description.
* BETA: the below work on Java Symbol Solver is still ongoing.

Version 3.4.4
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/62?closed=1)
* BETA: the below work on Java Symbol Solver is still ongoing.

Version 3.4.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/61?closed=1)
* BETA: we're still doing work to integrate parts of [Java Symbol Solver](https://github.com/javaparser/javasymbolsolver) to simplify its API.
* `VisitorMap` is joined by `VisitorSet` and `VisitorList`, 
for when you want to store `Node`s in collection but don't want its default equals/hascode behaviour

Version 3.4.2
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/60?closed=1)
* BETA: we're doing work to integrate parts of [Java Symbol Solver](https://github.com/javaparser/javasymbolsolver) to simplify its API.
* JDK 9 will compile JavaParser now.
* [An official sample Maven setup](https://github.com/javaparser/javaparser-maven-sample) was added.

Version 3.4.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/59?closed=1)
* Two visitors were added: `NoCommentEqualsVisitor` and `NoCommentHashCodeVisitor` - 
as the name implies you can use these to compare nodes without considering comments.
Thanks Ryan Beckett!
* `isSomeType()` methods have been added for many types that help avoid `instanceof`.
* `asSomeType()` methods have been added for many types that help avoid casting to that type.
* `ifSomeType()` methods have been added for many types, giving a nice functional way of doing if-is-type-then-cast-to-type-then-use.
* The `LexicalPreservingPrinter` had its API changed a little: setup and printing are now separate things,
so you don't have to drag an instance of `LexicalPreservingPrinter` through your code anymore.  
* `traverseScope` was added to all nodes with a scope, so you can travel through the scope without tripping over (non-)optionality.


Version 3.4.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/58?closed=1)
* BREAKING: We missed a Java 9 feature which is now on board: try with resources can now refer to a resource declared outside of the statement.
This means that the node type you get for those resources is now `Expression` instead of `VariableDeclarationExpr`.
For Java 8 and below you can simply cast it to `VariableDeclarationExpr` again.
See also the Javadoc for `TryStmt`.
* You can now inspect the AST by exporting it to XML, JSON, YAML, or a Graphviz's dot diagram, thanks to Ryan Beckett!
* `GenericVisitorWithDefaults` and `VoidVisitorWithDefaults` were added which function like empty visitors, 
but all the visit methods call a default method by default.
* Annotation support was cleaned up, adding some obscure locations where you can have annotations.
* `EnumDeclaration` regained its constructor builder methods. They were accidentally lost around 3.2.2.
* `ArrayType` now has an `origin` field which indicates in which position the array brackets were found.

Version 3.3.5
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/57?closed=1)

Version 3.3.4
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/56?closed=1)
* `SourceZip` has been added.
Use it to read source code from jars or zip files.
Thank you @ryan-beckett !
* JavaCC was upgraded to 7.0.2
* A new option for the pretty printer was added.
You can now wrap-and-column-align parameters of method calls.
Thank you @tarilabs !

Version 3.3.3
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/55?closed=1)
* Parsing a partial java file (like an expression or statement) no longer ignores trailing code.
* New memory saving option: turn off token list.

Version 3.3.2
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/54?closed=1)
* `VisitorMap` lets you override hashcode/equals for nodes when used as a key for a map.

Version 3.3.1
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/53?closed=1)
* The token list is now mutable - see methods on `JavaToken`.
This caused mild breakage - some fields have become `Optional`.

Version 3.3.0
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/52?closed=1)
* Breaking: `TryStmt::tryBlock` and `EnclosedExpr::inner` were optional for no good reason. Now they are required.
* You can now ask a `JavaToken` for its category, which is useful for examining the token list or doing syntax highlighting or so.
* `enum` and `strictfp` can now be used as identifiers on lower Java versions.

Version 3.2.12
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/51?closed=1)

Version 3.2.11
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/50?closed=1)
* We're up to date with the latest Java 9 module system again.

Version 3.2.10
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/49?closed=1)
* `Node.replace(old, new)` was added, including property-specific `X.replaceY(newY)` methods

Version 3.2.9
------------------
Scrapped due to release problem.

Version 3.2.8
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/48?closed=1)
* Added `isInnerClass()` that checks if a `ClassOrInterfaceDeclaration` is an inner class (note: this is different from a nested class!)
* @ryan-beckett contributed a huge [Eclipse setup guide](https://github.com/javaparser/javaparser/wiki/Eclipse-Project-Setup-Guide)

Version 3.2.7
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/47?closed=1)
* We now recover from some parse errors! [Here is an article](https://matozoid.github.io/2017/06/11/parse-error-recovery.html)

Version 3.2.6
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/46?closed=1)
* `EmptyMemberDeclaration` is gone! 
It was deprecated for a while because it it was in the AST, but doesn't have any meaning in a Java program. 
`EmptyStmt` was also deprecated, but that has been reverted. 
This node *does* have meaning.

Version 3.2.5
------------------
[issues resolved](https://github.com/javaparser/javaparser/milestone/45?closed=1)
* `NodeWithCondition` was added on all nodes containing a condition.
* Lots of work on improving lexical preservation.
* If a file was parsed from a file system, you can now get path information etc. from `CompilationUnit`
* API BREAKING: every node now points to its start and end token.
Some of the API has started returning `TokenRange` instead of `Range` - you can call `toRange` to get the old object type.
We may still change the naming of some of this code in the following month.

Version 3.2.4
------------------
New style changelog, no more issue numbers, but a link: 
[issues resolved](https://github.com/javaparser/javaparser/milestone/44?closed=1)
and any notable changes:
* the new method `Node.removeForced()` by removing it, or removing the first parent that is optional.
This is different from `Node.remove()`, `remove()` only tries to remove the node from the parent and fails if it can't.
* `FieldAccessExpr.scope` is now a required property.
You might find some `get()`s in your code that are no longer necessary.
* `ReferenceType` no longer has a type parameter, so every `ReferenceType<?>` can be replaced by `ReferenceType` now.

Version 3.2.3
------------------
* 907 906 905 903 911 910 909 908 smaller improvements and fixes

Version 3.2.2
------------------
Beta: `TreeStructureVisitor`.

* 770 902 904 901 smaller improvements and fixes

Version 3.2.1
------------------
Beta: `TreeStructureVisitor`.

* Maven dependencies were updated to their latest versions 
* 890 the concept of "method signature" now exists in JavaParser
* 896 891 889 887 882 789 smaller improvements and fixes

Version 3.2.0
------------------
The lexical preservation code is stable!

Beta: `TreeStructureVisitor`.

* 885 884 879 878 smaller improvements and fixes

Version 3.1.4
------------------
This is the first version to parse Java 9.

Beta: `TreeStructureVisitor`, and `LexicalPreservingPrinter`.

* 872 873 874 787 Remaining Java 9 work.

Version 3.1.3
------------------
Beta: `TreeStructureVisitor`, and `LexicalPreservingPrinter`.

A start has been made on source level support. The default level is Java 8.
It can be set to Java 9 like this for a parser *instance*:
```java
private final JavaParser parser = new JavaParser(new ParserConfiguration().setValidator(new Java9Validator()));
```
and like this for the static parse methods:
```java
QuickJavaParser.getConfiguration().setValidator(new Java9Validator());
```

* 862 552 "_" is an illegal identifier on source level 9.
* 869 867 109 855 857 smaller improvements and fixes

Version 3.1.2
------------------
Beta: `TreeStructureVisitor`, `ConcreteSyntaxModel`, and `LexicalPreservingPrinter`.

* 594 849 831 a validation framework was introduced to inform about problems in the AST without needing to change the grammar,
and without requiring parsing code.
It is open for extension by users.
* 852 853 826 832 846 839 smaller improvements and fixes

Version 3.1.1
------------------
Beta: `TreeStructureVisitor`, `ConcreteSyntaxModel`, and `LexicalPreservingPrinter`.

* 654 124 lexical preservation (printing source code with the same formatting it had when parsing) has been added.
    Thank you @ftomassetti for a lot of work! 
* 554 800 first (big) step towards Java 9 support: JavaParser can read project Jigsaw module definitions.
* 795 786 751 extend the TreeVisitor with more traversal options. Thanks @ryan-beckett!
* 791 `GenericListVisitorAdapter` has been added which collects its results in a list. Thanks @Gottox!
* 815 798 797 813 clean up Problem text
* 819 818 817 816 441 809 808 807 fix various absurd annotation related issues. 
* 777 805 802 796 790 792 793 781 784 785 783 782 779 357 799 763 smaller improvements and fixes

Version 3.1.0
------------------
Beta: `TreeStructureVisitor` and `ConcreteSyntaxModel`.

* 705 755 Add the concrete syntax model, which will give you information about the exact syntax a certain nodes matches.

* 777 smaller improvements and fixes

Version 3.1.0-beta.2
------------------
This version is a beta because `TreeStructureVisitor` is not in its definite state yet.

* 762 761 772 merge `javaparser-metamodel` and `javaparser-generator-utils` into `javaparser-core`.
* 766 the `ModifierVisitor` is now created by a code generator. Its behaviour has been made logical, and may give different results than before.
* 755 `ConstructorDeclaration` and `MethodDeclaration` now share a parent: `CallableDeclaration`
* 687 759 773 769 768 767 765 759 smaller improvements and fixes

Version 3.1.0-beta.1
------------------
This version is a beta because there are a lot of new features that may still change.

This version needs a minor version increase because of a backwards compatability issue: 
* 719 `getJavadoc`, `getJavadocComment` and `getComment` could return null. Our promise was to return `Optional`, so that is what they do now.

New:
* 658 718 736 737 we have created a metamodel.
It gives information about the structure of the various AST nodes, as if you are introspecting them.
You can find it in `javaparser-metamodel`, the main class is `JavaParserMetaModel`
* 353 365 visitors are no longer hand made, they are now generated from the metamodel. This should make them 100% reliable.
Affected visitors are: `GenericVisitorAdapter`, `EqualsVisitor`, `VoidVisitorAdapter`, `VoidVisitor`, `GenericVisitor`, `HashCodeVisitor`, `CloneVisitor`.

If you want to generate your own visitors, you can use the `VisitorGenerator` class from `javaparser-core-generators`

If you want to reuse the code generation utilities, look at module `javaparser-generator-utils` - there is a very useful `SourceRoot` class in there that takes away a lot of file management troubles.
* 538 735 `TreeStructureVisitor` has been added, which should be considered beta.
* 220 733 717 749 745 750 743 748 666 732 746 734 733 smaller improvements and fixes

Version 3.0.1
------------------
* 699 433 325 Javadoc can now be parsed
* 703 696 added NodeWithOptionalScope
* 702 FieldAccessExpr now implements NodeWithSimpleName, *which means that "field" has been renamed to "name"*
* 707 706 improve range of array types and levels
* 709 smaller improvements and fixes

Version 3.0.0
------------------
* 695 697 689 680 693 691 682 690 677 679 688 684 683 smaller improvements and fixes

Version 3.0.0-RC.4
------------------
* 668 669 TypeDeclarationStmt became LocalClassDeclarationStmt
* 347 665 every node now has some documentation
* 660 670 673 four types of import declaration have been merged back into the old ImportDeclaration
* 659 The pretty printer can now take customized visitors 
* 650 671 672 674 524 smaller improvements and fixes

Version 3.0.0-RC.3
------------------
* 639 622 632 657 656 652 653 647 648 645 194 643 630 624 628 627 626 625 623 cleanups, small fixes, and general housekeeping

Version 3.0.0-RC.2
------------------
* 593 EmptyImportDeclaration and NonEmptyImportDeclaration have been removed
* 612 VariableDeclaratorId has been removed. It has been substituted by "SimpleName name"
* 614 617 the list of tokens has been linearized and simplified
* 615 support for arrays has once more been changed. See [the issue](https://github.com/javaparser/javaparser/issues/592) 
* 580 453 380 618 580 611 610 424 608 smaller improvements and fixes

Version 3.0.0-RC.1
------------------
* 499 601 renames many fields to be more consistent
* 596 605 602 604 smaller improvements and fixes

Version 3.0.0-alpha.11
------------------
* 547 595 Node.range is now using Optional instead of Range.UNKNOWN
* 584 588 548 585 bug fixes and improvements

Version 3.0.0-alpha.10
------------------
* 578 579 577 575 290 570 568 567 562 564 551 bug fixes and improvements

Version 3.0.0-alpha.9
------------------
* 403 358 549 Make all names nodes: either SimpleName or Name. This makes every name in the AST visitable. NameExpr is now a wrapper to use SimpleName in an expression.
* 516 536 use Optional<> for return values.
* 556 557 558 550 small improvements and fixes.
* 560 559 make nodes observable.

Version 3.0.0-alpha.8
------------------
* 344 529 turn DumpVisitor into an official PrettyPrinter
* 532 508 427 530 531 513 528 cleanups

Version 3.0.0-alpha.7
------------------
* 515 roll back attempt at using Optional
* 522 504 make NodeList not a Node (restores parent/children behaviour to before alpha.4)
* 527 526 rename getChildrenNodes to getChildNodes
* 525 495 520 bug fix

Version 3.0.0-alpha.6
------------------
* 503 modified ImportDeclaration hierarchy to have getters for static and "asterisk" again
* 506 bug fix

Version 3.0.0-alpha.5
------------------
* 451 null is no longer allowed in the AST. [See last post in issue](https://github.com/javaparser/javaparser/issues/451)
* 501 421 420 316 use a special type of list for nodes: NodeList. [See last post in issue](https://github.com/javaparser/javaparser/issues/421)

Version 3.0.0-alpha.4
------------------
* 463 471 nodes can now be removed easily
* 491 import handling changed. Instead of "ImportDeclaration", we now have the four types of import as described in the JLS. [See issue](https://github.com/javaparser/javaparser/pull/491)
* 452 355 474 494 various improvements
* 493 492 485 Simplify the JavaParser interface

Version 3.0.0-alpha.3
------------------
* 112 237 466 465 461 460 458 457 fundamentally changes how we deal with arrays. [It is explained in the last post here](https://github.com/javaparser/javaparser/issues/237)
* 472 456 makes the "data" field on every node more structured.
* 477 468 refactor TypeArguments. You will find that TypeArguments is no longer a type, it is just a list in some nodes.
* 482 adds the "nodeTypes" packages to the osgi export.
* 479 476 makes all setters on nodes return this so they become chainable.
* 473 437 clean up CloneVisitor.

Version 3.0.0-alpha.2
------------------
* 157 a new parser frontend, check https://github.com/javaparser/javaparser/pull/447 for explanations
* 435 more builder methods like 400 and 405
* 111 440 443 444 445 446 bugs & cleanups

Version 3.0.0-alpha.1
------------------
* 400 405 introduce many "builder" style methods for constructing code. Thanks DeepSnowNeeL!
* 409 remove ASTHelper (methods are now on specific Node subclasses)
* 414 JavaParser can now be instantiated and reused. InstanceJavaParser removed
* 418 417 411 408 bugs
* 367 420 407 402 various cleanups

Version 2.5.1
-------------
* 394 OSGi manifest added
* 391 fix ModifierVisitor NullPointerException bug
* 385 a few new parse methods
* 386 fix dumping an empty import (a single ; after the package declaration)

Version 2.5.0
-------------
API breaking changes:

* 191: moved TreeVisitor to visitor package
* 368, 162, 303, 302, 360: use correct type in some places.
* 371: code is now compiled with Java 8
* 342, 331: ModifierVisitorAdapter detects and removes broken nodes
* 328, 270: upgrade JavaCC (use TokenMgrException now)
Other changes:

* 297: enable access to tokens.
* 341, 361: node positions are now OO
* 211, 373: escaping of \n \r for string literals
* 336, 276, 141: JavaDoc support now works
* 337, 281: reorganize the stream reading code
* 343, 309, 332, 57: take advantage of common interfaces
* 329, 326, 327: deal with platform issues
* 163, 236, 252, 296, 269, 339, 321, 322, 252, 253, 293, 295: various fixes
* 310, 311, 313, 301, 294: some code clean-ups 

Version 2.4.0
-------------
* several fixes in DumpVisitor for bugs due to lazy initialization
* make TypeDeclaration implements DocumentableNode directly
* TypedNode interface introduced
* introduce MultiBoundType
* refactored IntersectionType and UnionType
* refactored CatchClause
* parsing annotations in throws declarations
* parse orphan semicolons in import statements
* added PackageDeclaration.getPackageName
* solved issue with newlines in string literals
* fixed handling of UnknownType in EqualsVisitor
* improvements to CommentsParser
* removing old grammar

Version 2.3.0
-------------
* ClassOrInterfaceType implements NamedNode
* DumpVisitor can now be extended
* Improved documentation
* AST: lists are now lazy initialized

Version 2.1.0
-------------
* Features
  * [#75 performance improvement for `PositionUtils.sortByBeginPosition`](https://github.com/javaparser/javaparser/issues/75)
  * [#64 In getDeclarationAsString parameter names should be optional](https://github.com/javaparser/javaparser/issues/64)
* Bugfixes
  * [#79 Fix NPE in `ConstructorDeclaration.getDeclarationAsString`](https://github.com/javaparser/javaparser/pull/79)
  * [#86 Add missing functions to ModifierVisitorAdapter](https://github.com/javaparser/javaparser/pull/86)
  * [#82 set LambdaExpr as parent of its child nodes](https://github.com/javaparser/javaparser/issues/82)
  * [#87 implement `setJavadoc` and `getJavadoc` at various classes](https://github.com/javaparser/javaparser/issues/87)
  * [#96 Fixed encoding issue in `Javaparser.parse`](https://github.com/javaparser/javaparser/pull/96)
  * [#85 Casting a lambda expression causes a parsing failure](https://github.com/javaparser/javaparser/issues/85)
  * [#88 `MethodReferenceExpr` and `TypeExpr` don't set themselves as parents](https://github.com/javaparser/javaparser/issues/88)
* Internal
  * [#89 CommentsParser.State contains unused fields](https://github.com/javaparser/javaparser/issues/89)
  * Switched from drone.io to [Travis](https://travis-ci.org/javaparser/javaparser)
  * [#105 Enforce compiling the library for a certain Java version](https://github.com/javaparser/javaparser/pull/105)

[Code changes](https://github.com/javaparser/javaparser/compare/javaparser-parent-2.0.0...master)

Version 2.0.0
-------------
* support Java 8

Version 1.0.8 (2010-01-17)
-------------
* Fixed issues:
	* Issue 17: A refactor suggestion for AnnotationExpr and its subclasses
	* Issue 21: Java 5 JavaParser compiled JARs
	* Issue 22: Please use java.lang.reflect.Modifier constants in japa.parser.ast.body.ModifierSet
	* Issue 27: Implement the "equal" method
	* Issue 30: equals and hashCode methods

Version 1.0.7 (2009-04-12)
-------------
* Issue 19 fixed: 
* Tests changed to run with junit 4 

Version 1.0.6 (2009-01-11)
-------------
* Issue 11 fixed: changed method get/setPakage to get/setPackage in the class CompilationUnit
* Created new visitor adapter to help AST modification: ModifierVisitorAdapter
* Changed visitor adapters to abstract  

Version 1.0.5 (2008-10-26)
-------------
* Created simplified constructors in the nodes of the AST (without positional arguments) 
* Created ASTHelper class with some helpful methods (more methods are still needed)

Version 1.0.4 (2008-10-07)
-------------
* Moved to javacc 4.1.
* The java_1_5.jj can be build alone without compilation errors

Version 1.0.3 (2008-09-06)
-------------
* Removed SuperMemberAccessExpr class, it was no longer used
* Removed the methods get/setTypeArgs() from ArrayCreationExpr, this node shouldn't have these methods.
* Fixed the bug with start/end position of the nodes IntegerLiteralMinValueExpr and LongLiteralMinValueExpr  
* The methods get/setAnnotations() from all BodyDeclaration subclasses were pushed down to BodyDeclaration class 

Version 1.0.2 (2008-07-20)
-------------
* Issue fixed: Issue 1: Add support for editing AST nodes or create new ones

Version 1.0.1 (2008-07-01)
-------------
* Issue fixed: Issue 5: end line and end column equal to begin line and begin column

Version 1.0.0 (2008-06-25)
-------------
* Changed version numbering, starting version 1.0.0
* Javadoc done for packages:
    * japa.parser
    * japa.parser.ast
* Corrected bug when parsing in multithread: 
    * JavaParser.setCacheParser(false) must be called before to use the parser concurrent 

2008-06-19
-------------
* No code changes, added binary distribution to download page 

2008-06-11
-------------
* Bug corrected: NPE in VoidVisitorAdapter 
	* http://code.google.com/p/javaparser/issues/detail?id=2

2008-06-09
-------------
* Added Adapters for de visitors

2008-05-28
-------------
* This project now is published at Google Code:
	* http://code.google.com/p/javaparser/

2008-05-25
-------------
* Added support for comments and javadoc to the tree. 
	* Javadocs are stored directly to members (BodyDeclaration and all deriveds (classes, methods, fields, etc.)), accessible by the method getJavadoc().
	* All comments are stored in the CompilationUnit, accessible by the method getComments().

2008-04-01
-------------
* Changed all nodes public attributes to be private and created getters to access them
* Changed the methods of the Node getLine e getColumn to getBeginLine and getBeginColumn
* Added the methods getEndLine and getEndColumn to the Node class (works only in the BlockNode)

2007-12-22
-------------
* Corrected ConditionalExpression bug

2007-10-21
-------------
* Added LGPL License

2007-10-21
-------------
* Bugs corrected:  
  * Created PackageDeclaration member of CompilationUnit to add suport for annotations in the package declaration
  * Parameterized anonymous constructor invocation
  * Explicit constructor invotation Type Arguments
  * ctrl+z ("\u001A") ar end of compilation unit

2007-10-09
-------------
* EnumConstantDeclaration annotation support corrected
* Parssing Java Unicode escape characters suport added

2007-10-03
-------------
* Bug corrected: "MotifComboPopup.this.super()" statement was generating parser error
	                    
2007-10-01
-------------
* Bug corrected: Casting signed primitive values
```
	double d = (double) -1;
	                    ^
```
2007-08-06
-------------
* Bug with the single line comments in the final of the unit corrected

2007-07-31
-------------
* Fixed the bug with the following expression:  `Class c = (int.class);`

2007-06-26
-------------
* Bug fixes from Leon Poyyayil work
	* suport for hex floating point
	* unicode digits in indentifier 
	* MemberValueArrayInitializer

2007-03-09
-------------
* Long and Integer literal MIN_VALUE bug	

2007-02-24
-------------
* '\0' bug fixed	

2007-02-01
-------------
* Many bug fixes
* Added line/column to nodes
