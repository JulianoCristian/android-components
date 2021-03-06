[android-components](../../index.md) / [mozilla.components.browser.domains](../index.md) / [CustomDomains](./index.md)

# CustomDomains

`object CustomDomains` [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/browser/domains/src/main/java/mozilla/components/browser/domains/CustomDomains.kt#L13)

Contains functionality to manage custom domains for auto-completion.

### Functions

| Name | Summary |
|---|---|
| [add](add.md) | `fun add(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds the provided domain to preferences. |
| [load](load.md) | `fun load(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>Loads the previously added/saved custom domains from preferences. |
| [remove](remove.md) | `fun remove(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, domains: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Removes the provided domain from preferences. |
| [save](save.md) | `fun save(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, domains: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Saves the provided domains to preferences. |
