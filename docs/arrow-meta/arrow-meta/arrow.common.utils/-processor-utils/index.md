//[arrow-meta](../../../index.md)/[arrow.common.utils](../index.md)/[ProcessorUtils](index.md)

# ProcessorUtils

[jvm]\
interface [ProcessorUtils](index.md) : KotlinMetadataUtils

## Functions

| Name | Summary |
|---|---|
| [asClassOrPackageDataWrapper](as-class-or-package-data-wrapper.md) | [jvm]<br>open fun KotlinMetadata.[asClassOrPackageDataWrapper](as-class-or-package-data-wrapper.md)(classElement: [TypeElement](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/TypeElement.html)): [ClassOrPackageDataWrapper](../-class-or-package-data-wrapper/index.md)? |
| [declaredTypeClassInterfaces](declared-type-class-interfaces.md) | [jvm]<br>open fun [ClassOrPackageDataWrapper.Class](../-class-or-package-data-wrapper/-class/index.md).[declaredTypeClassInterfaces](declared-type-class-interfaces.md)(typeTable: TypeTable): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ClassOrPackageDataWrapper](../-class-or-package-data-wrapper/index.md)&gt; |
| [getClassData](get-class-data.md) | [jvm]<br>open fun [Element](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/Element.html).[getClassData](get-class-data.md)(): [ClassOrPackageDataWrapper.Class](../-class-or-package-data-wrapper/-class/index.md) |
| [getClassOrPackageDataWrapper](get-class-or-package-data-wrapper.md) | [jvm]<br>open fun [getClassOrPackageDataWrapper](get-class-or-package-data-wrapper.md)(classElement: [TypeElement](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/TypeElement.html)): [ClassOrPackageDataWrapper](../-class-or-package-data-wrapper/index.md) |
| [getConstructorParamNames](get-constructor-param-names.md) | [jvm]<br>open fun [Element](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/Element.html).[getConstructorParamNames](get-constructor-param-names.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [getConstructorTypesNames](get-constructor-types-names.md) | [jvm]<br>open fun [Element](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/Element.html).[getConstructorTypesNames](get-constructor-types-names.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [getFunction](get-function.md) | [jvm]<br>open fun [ClassOrPackageDataWrapper](../-class-or-package-data-wrapper/index.md).[getFunction](get-function.md)(methodElement: [ExecutableElement](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/ExecutableElement.html)): ProtoBuf.Function? |
| [getFunctionOrNull](../../arrow.optics/-optics-processor/index.md#-1924364317%2FFunctions%2F-35121544) | [jvm]<br>open fun ClassData.[getFunctionOrNull](../../arrow.optics/-optics-processor/index.md#-1924364317%2FFunctions%2F-35121544)(methodElement: [ExecutableElement](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/ExecutableElement.html)): ProtoBuf.Function?<br>open fun PackageData.[getFunctionOrNull](../../arrow.optics/-optics-processor/index.md#-644467023%2FFunctions%2F-35121544)(methodElement: [ExecutableElement](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/ExecutableElement.html)): ProtoBuf.Function?<br>open fun [getFunctionOrNull](../../arrow.optics/-optics-processor/index.md#-2082541386%2FFunctions%2F-35121544)(methodElement: [ExecutableElement](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/ExecutableElement.html), nameResolver: NameResolver, functionList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;ProtoBuf.Function&gt;): ProtoBuf.Function? |
| [overrides](overrides.md) | [jvm]<br>open fun ProtoBuf.Function.[overrides](overrides.md)(o: ProtoBuf.Function): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [descriptor](../../arrow.optics/-optics-processor/index.md#-645837508%2FProperties%2F-35121544) | [jvm]<br>open val [ArrayType](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/type/ArrayType.html).[descriptor](../../arrow.optics/-optics-processor/index.md#-645837508%2FProperties%2F-35121544): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [descriptor](../../arrow.optics/-optics-processor/index.md#-2070878313%2FProperties%2F-35121544) | [jvm]<br>open val [ExecutableType](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/type/ExecutableType.html).[descriptor](../../arrow.optics/-optics-processor/index.md#-2070878313%2FProperties%2F-35121544): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [descriptor](../../arrow.optics/-optics-processor/index.md#1102730252%2FProperties%2F-35121544) | [jvm]<br>open val [TypeMirror](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/type/TypeMirror.html).[descriptor](../../arrow.optics/-optics-processor/index.md#1102730252%2FProperties%2F-35121544): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [descriptor](../../arrow.optics/-optics-processor/index.md#-240230391%2FProperties%2F-35121544) | [jvm]<br>open val [TypeVariable](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/type/TypeVariable.html).[descriptor](../../arrow.optics/-optics-processor/index.md#-240230391%2FProperties%2F-35121544): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [descriptor](../../arrow.optics/-optics-processor/index.md#2105374311%2FProperties%2F-35121544) | [jvm]<br>open val [WildcardType](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/type/WildcardType.html).[descriptor](../../arrow.optics/-optics-processor/index.md#2105374311%2FProperties%2F-35121544): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [elementUtils](../../arrow.optics/-optics-processor/index.md#353266973%2FProperties%2F-35121544) | [jvm]<br>open val [elementUtils](../../arrow.optics/-optics-processor/index.md#353266973%2FProperties%2F-35121544): [Elements](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/util/Elements.html) |
| [filer](../../arrow.optics/-optics-processor/index.md#-575129390%2FProperties%2F-35121544) | [jvm]<br>open val [filer](../../arrow.optics/-optics-processor/index.md#-575129390%2FProperties%2F-35121544): [Filer](https://docs.oracle.com/javase/8/docs/api/javax/annotation/processing/Filer.html) |
| [hasNoCompanion](has-no-companion.md) | [jvm]<br>open val [Element](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/Element.html).[hasNoCompanion](has-no-companion.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [jvmMethodSignature](../../arrow.optics/-optics-processor/index.md#2118350669%2FProperties%2F-35121544) | [jvm]<br>open val [ExecutableElement](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/element/ExecutableElement.html).[jvmMethodSignature](../../arrow.optics/-optics-processor/index.md#2118350669%2FProperties%2F-35121544): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [locale](../../arrow.optics/-optics-processor/index.md#256813368%2FProperties%2F-35121544) | [jvm]<br>open val [locale](../../arrow.optics/-optics-processor/index.md#256813368%2FProperties%2F-35121544): [Locale](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html) |
| [messager](../../arrow.optics/-optics-processor/index.md#-1623267801%2FProperties%2F-35121544) | [jvm]<br>open val [messager](../../arrow.optics/-optics-processor/index.md#-1623267801%2FProperties%2F-35121544): [Messager](https://docs.oracle.com/javase/8/docs/api/javax/annotation/processing/Messager.html) |
| [options](../../arrow.optics/-optics-processor/index.md#295592682%2FProperties%2F-35121544) | [jvm]<br>open val [options](../../arrow.optics/-optics-processor/index.md#295592682%2FProperties%2F-35121544): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [processingEnv](../../arrow.meta.encoder.jvm/-type-element-encoder/index.md#-2076210194%2FProperties%2F-35121544) | [jvm]<br>abstract val [processingEnv](../../arrow.meta.encoder.jvm/-type-element-encoder/index.md#-2076210194%2FProperties%2F-35121544): [ProcessingEnvironment](https://docs.oracle.com/javase/8/docs/api/javax/annotation/processing/ProcessingEnvironment.html) |
| [sourceVersion](../../arrow.optics/-optics-processor/index.md#178597355%2FProperties%2F-35121544) | [jvm]<br>open val [sourceVersion](../../arrow.optics/-optics-processor/index.md#178597355%2FProperties%2F-35121544): [SourceVersion](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/SourceVersion.html) |
| [typeUtils](../../arrow.optics/-optics-processor/index.md#-440752303%2FProperties%2F-35121544) | [jvm]<br>open val [typeUtils](../../arrow.optics/-optics-processor/index.md#-440752303%2FProperties%2F-35121544): [Types](https://docs.oracle.com/javase/8/docs/api/javax/lang/model/util/Types.html) |

## Inheritors

| Name |
|---|
| [AbstractProcessor](../-abstract-processor/index.md) |
| [JvmMetaApi](../../arrow.meta.encoder.jvm/-jvm-meta-api/index.md) |
| [TypeElementEncoder](../../arrow.meta.encoder.jvm/-type-element-encoder/index.md) |