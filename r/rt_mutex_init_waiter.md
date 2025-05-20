# Function: <code>rt_mutex_init_waiter</code>

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
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81909121)
Location: kernel/locking/rtmutex.c:1161
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810d5c80-ffffffff810d5c9e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993241)
Location: kernel/locking/rtmutex.c:1149
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ddc40-ffffffff810ddc5e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819ef851)
Location: kernel/locking/rtmutex.c:1149
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810e6290-ffffffff810e62ae: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2aba1)
Location: kernel/locking/rtmutex.c:1149
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810f1810-ffffffff810f182e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9b890)
Location: kernel/locking/rtmutex.c:1150
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810fa100-ffffffff810fa11e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad31e0)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81105ef0-ffffffff81105f0e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb297)
Location: kernel/locking/rtmutex.c:1146
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81110e60-ffffffff81110e7e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c44137)
Location: kernel/locking/rtmutex.c:1146
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8110e010-ffffffff8110e02e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c370e7)
Location: kernel/locking/rtmutex.c:1120
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81c37390-ffffffff81c373ae: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55a31)
Location: kernel/locking/rtmutex_common.h:190
Inline: True
```
```
In kernel/futex.c (ffffffff8117ffbb)
Location: kernel/locking/rtmutex_common.h:190
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f279aa)
Location: kernel/locking/rtmutex_common.h:190
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
```
In kernel/futex/pi.c (ffffffff811b538b)
Location: kernel/locking/rtmutex_common.h:190
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi
```
```
In kernel/futex/requeue.c (ffffffff811b6390)
Location: kernel/locking/rtmutex_common.h:190
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d349a)
Location: kernel/locking/rtmutex_common.h:190
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
```
In kernel/futex/pi.c (ffffffff811f649b)
Location: kernel/locking/rtmutex_common.h:190
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi
```
```
In kernel/futex/requeue.c (ffffffff811f74d0)
Location: kernel/locking/rtmutex_common.h:190
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8118eff9)
Location: kernel/locking/rtmutex_common.h:211
Inline: True
```
```
In kernel/futex/pi.c (ffffffff8120ac9b)
Location: kernel/locking/rtmutex_common.h:211
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi
```
```
In kernel/futex/requeue.c (ffffffff8120bc70)
Location: kernel/locking/rtmutex_common.h:211
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8119d9a9)
Location: kernel/locking/rtmutex_common.h:211
Inline: True
```
```
In kernel/futex/pi.c (ffffffff81222219)
Location: kernel/locking/rtmutex_common.h:211
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi
```
```
In kernel/futex/requeue.c (ffffffff81223208)
Location: kernel/locking/rtmutex_common.h:211
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
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
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5ba4)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffff80001016c0b8-ffff80001016c0ec: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9d9e0)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c03b79dc-c03b7a08: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee8254)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c0000000001c3c20-c0000000001c3c40: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c8284)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffe00010c2c6-ffffffe00010c2f2: rt_mutex_init_waiter (STB_GLOBAL)
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
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a72050)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ff200-ffffffff810ff21e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e420)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ef3f0-ffffffff810ef40e: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade460)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810fc3c0-ffffffff810fc3de: rt_mutex_init_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_init_waiter(struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aea910)
Location: kernel/locking/rtmutex.c:1148
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff811075e0-ffffffff811075fe: rt_mutex_init_waiter (STB_GLOBAL)
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
