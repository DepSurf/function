# Function: <code>__rt_mutex_futex_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81909477)
Location: kernel/locking/rtmutex.c:1593
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81909410-ffffffff81909440: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819935c7)
Location: kernel/locking/rtmutex.c:1593
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81993560-ffffffff81993590: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819efba0)
Location: kernel/locking/rtmutex.c:1613
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff819efb30-ffffffff819efb60: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2aef0)
Location: kernel/locking/rtmutex.c:1613
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81a2ae80-ffffffff81a2aeb0: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9bbfd)
Location: kernel/locking/rtmutex.c:1614
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81a9bb90-ffffffff81a9bbc0: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad354d)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81ad34e0-ffffffff81ad3510: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb65d)
Location: kernel/locking/rtmutex.c:1610
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:wake_futex_pi
```
**Symbols:**

```
ffffffff81bcb5f0-ffffffff81bcb620: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c444fd)
Location: kernel/locking/rtmutex.c:1610
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:wake_futex_pi
```
**Symbols:**

```
ffffffff81c44490-ffffffff81c444c0: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c374ed)
Location: kernel/locking/rtmutex.c:1507
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81c37480-ffffffff81c374b0: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex_base *lock, struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55d06)
Location: kernel/locking/rtmutex_api.c:143
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81d55c90-ffffffff81d55cc0: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex_base *lock, struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27c15)
Location: kernel/locking/rtmutex_api.c:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81f27b80-ffffffff81f27bc6: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex_base *lock, struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d3755)
Location: kernel/locking/rtmutex_api.c:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff820d36b0-ffffffff820d36f6: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex_base *lock, struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff821579d5)
Location: kernel/locking/rtmutex_api.c:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff82157930-ffffffff82157976: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex_base *lock, struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223a845)
Location: kernel/locking/rtmutex_api.c:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff8223a7a0-ffffffff8223a7e6: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da605c)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffff800010da5fa0-ffff800010da5ff0: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9dde0)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
c0e9dd4c-c0e9dd90: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee8738)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
c000000000ee8680-c000000000ee86dc: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c857e)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffe0008c8502-ffffffe0008c854c: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a723bd)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81a72350-ffffffff81a72380: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e78d)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81a2e720-ffffffff81a2e750: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade7cd)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81ade760-ffffffff81ade790: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aeac4d)
Location: kernel/locking/rtmutex.c:1612
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81aeabe0-ffffffff81aeac10: __rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rt_wake_q_head *wqh</code>
</li>
<li>
<b>Param removed. </b>
<code>struct wake_q_head *wake_q</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex *lock</code> ➡️ <code>struct rt_mutex_base *lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
