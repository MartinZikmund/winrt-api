---
-api-type: winrt method
---
 Register to be notified of unlocking via the [Unlocking](lockapplicationhost_unlocking.md) event.
 In the Unlocking event handler, call [GetDeferral](lockscreenunlockingeventargs_getdeferral.md).
 Kick off an animation.   + When that animation completes, call [Complete](lockscreenunlockingdeferral_complete.md) on the deferral to end the deferral.