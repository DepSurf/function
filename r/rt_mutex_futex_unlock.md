# Function: <code>rt_mutex_futex_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81822e10)
Location: kernel/locking/rtmutex.c:1497
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81822e10-ffffffff81822e3d: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8189d360)
Location: kernel/locking/rtmutex.c:1506
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8189d360-ffffffff8189d38d: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool rt_mutex_futex_unlock(struct rt_mutex *lock, struct wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff818d2260)
Location: kernel/locking/rtmutex.c:1570
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff818d2260-ffffffff818d228d: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81909440)
Location: kernel/locking/rtmutex.c:1616
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81909440-ffffffff819094d6: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993590)
Location: kernel/locking/rtmutex.c:1616
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81993590-ffffffff81993626: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819efb60)
Location: kernel/locking/rtmutex.c:1636
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff819efb60-ffffffff819efbf7: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2aeb0)
Location: kernel/locking/rtmutex.c:1636
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81a2aeb0-ffffffff81a2af47: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9bbc0)
Location: kernel/locking/rtmutex.c:1637
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81a9bbc0-ffffffff81a9bc5b: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad3510)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81ad3510-ffffffff81ad35ab: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb620)
Location: kernel/locking/rtmutex.c:1633
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81bcb620-ffffffff81bcb6bb: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c444c0)
Location: kernel/locking/rtmutex.c:1633
Inline: False
Direct callers:
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81c444c0-ffffffff81c4455b: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c374b0)
Location: kernel/locking/rtmutex.c:1530
Inline: False
Direct callers:
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81c374b0-ffffffff81c3754b: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55cc0)
Location: kernel/locking/rtmutex_api.c:166
Inline: False
Direct callers:
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81d55cc0-ffffffff81d55d6c: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27bd0)
Location: kernel/locking/rtmutex_api.c:188
Inline: False
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81f27bd0-ffffffff81f27c92: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d3710)
Location: kernel/locking/rtmutex_api.c:188
Inline: False
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff820d3710-ffffffff820d37d2: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82157990)
Location: kernel/locking/rtmutex_api.c:188
Inline: False
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff82157990-ffffffff82157a52: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223a800)
Location: kernel/locking/rtmutex_api.c:188
Inline: False
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff8223a800-ffffffff8223a8c2: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5ff0)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffff800010da5ff0-ffff800010da60f8: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9dd90)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c0e9dd90-c0e9de3c: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee86e0)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c000000000ee86e0-c000000000ee87c4: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c854c)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffe0008c854c-ffffffe0008c85d2: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a72380)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81a72380-ffffffff81a7241b: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e750)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81a2e750-ffffffff81a2e7eb: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade790)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81ade790-ffffffff81ade82b: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt_mutex_futex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aeac10)
Location: kernel/locking/rtmutex.c:1635
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81aeac10-ffffffff81aeacb9: rt_mutex_futex_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct wake_q_head *wqh</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
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
