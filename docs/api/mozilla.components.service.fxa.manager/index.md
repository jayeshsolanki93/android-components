[android-components](../index.md) / [mozilla.components.service.fxa.manager](./index.md)

## Package mozilla.components.service.fxa.manager

### Types

| Name | Summary |
|---|---|
| [AccountState](-account-state/index.md) | `enum class AccountState`<br>States of the [FxaAccountManager](-fxa-account-manager/index.md). |
| [FxaAccountManager](-fxa-account-manager/index.md) | `open class FxaAccountManager : `[`Closeable`](https://developer.android.com/reference/java/io/Closeable.html)`, `[`Observable`](../mozilla.components.support.base.observer/-observable/index.md)`<`[`AccountObserver`](../mozilla.components.concept.sync/-account-observer/index.md)`>`<br>An account manager which encapsulates various internal details of an account lifecycle and provides an observer interface along with a public API for interacting with an account. The internal state machine abstracts over state space as exposed by the fxaclient library, not the internal states experienced by lower-level representation of a Firefox Account; those are opaque to us. |
| [SyncEnginesStorage](-sync-engines-storage/index.md) | `class SyncEnginesStorage`<br>Storage layer for the enabled/disabled state of [SyncEngine](../mozilla.components.service.fxa/-sync-engine/index.md). |

### Properties

| Name | Summary |
|---|---|
| [SCOPE_PROFILE](-s-c-o-p-e_-p-r-o-f-i-l-e.md) | `const val SCOPE_PROFILE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [SCOPE_SESSION](-s-c-o-p-e_-s-e-s-s-i-o-n.md) | `const val SCOPE_SESSION: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [SCOPE_SYNC](-s-c-o-p-e_-s-y-n-c.md) | `const val SCOPE_SYNC: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
