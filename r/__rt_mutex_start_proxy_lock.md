# Function: <code>__rt_mutex_start_proxy_lock</code>

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
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5d10)
Location: kernel/locking/rtmutex.c:1709
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810d5d10-ffffffff810d5d7e: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ddcd0)
Location: kernel/locking/rtmutex.c:1708
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ddcd0-ffffffff810ddd3e: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e6310)
Location: kernel/locking/rtmutex.c:1729
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810e6310-ffffffff810e6387: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f1890)
Location: kernel/locking/rtmutex.c:1748
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810f1890-ffffffff810f18f8: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fa190)
Location: kernel/locking/rtmutex.c:1749
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810fa190-ffffffff810fa1f8: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81105f80)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81105f80-ffffffff81105fe8: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81110f75)
Location: kernel/locking/rtmutex.c:1745
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81110ee0-ffffffff81110f48: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110e125)
Location: kernel/locking/rtmutex.c:1744
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8110e090-ffffffff8110e0f8: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c37635)
Location: kernel/locking/rtmutex.c:1623
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81c375a0-ffffffff81c37608: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55dc0)
Location: kernel/locking/rtmutex_api.c:270
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81d55dc0-ffffffff81d55e28: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27dc4)
Location: kernel/locking/rtmutex_api.c:292
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81f27d20-ffffffff81f27d9d: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d3944)
Location: kernel/locking/rtmutex_api.c:292
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
```
**Symbols:**

```
ffffffff820d3890-ffffffff820d390d: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82157bc4)
Location: kernel/locking/rtmutex_api.c:292
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
```
**Symbols:**

```
ffffffff82157b10-ffffffff82157b8f: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223aa34)
Location: kernel/locking/rtmutex_api.c:292
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8223a980-ffffffff8223a9ff: __rt_mutex_start_proxy_lock (STB_GLOBAL)
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
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016c190)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffff80001016c190-ffff80001016c210: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b7a84)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c03b7a84-c03b7aec: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3ce0)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c0000000001c3ce0-c0000000001c3d9c: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010c382)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffe00010c382-ffffffe00010c3ee: __rt_mutex_start_proxy_lock (STB_GLOBAL)
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
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ff290)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ff290-ffffffff810ff2f8: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ef480)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ef480-ffffffff810ef4e8: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fc450)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810fc450-ffffffff810fc4b8: __rt_mutex_start_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __rt_mutex_start_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81107680)
Location: kernel/locking/rtmutex.c:1747
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81107680-ffffffff811076e8: __rt_mutex_start_proxy_lock (STB_GLOBAL)
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
