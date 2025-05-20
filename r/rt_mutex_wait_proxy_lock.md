# Function: <code>rt_mutex_wait_proxy_lock</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5e00)
Location: kernel/locking/rtmutex.c:1803
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810d5e00-ffffffff810d5e87: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810dddc0)
Location: kernel/locking/rtmutex.c:1802
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810dddc0-ffffffff810dde47: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e6410)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810e6410-ffffffff810e6497: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f1990)
Location: kernel/locking/rtmutex.c:1849
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810f1990-ffffffff810f1a17: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fa290)
Location: kernel/locking/rtmutex.c:1850
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810fa290-ffffffff810fa31a: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81106080)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81106080-ffffffff8110610a: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81111010)
Location: kernel/locking/rtmutex.c:1846
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81111010-ffffffff811110a6: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110e1c0)
Location: kernel/locking/rtmutex.c:1845
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8110e1c0-ffffffff8110e256: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c376a0)
Location: kernel/locking/rtmutex.c:1702
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81c376a0-ffffffff81c37734: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex_base *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55e90)
Location: kernel/locking/rtmutex_api.c:349
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81d55e90-ffffffff81d55f0c: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex_base *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27e30)
Location: kernel/locking/rtmutex_api.c:371
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
**Symbols:**

```
ffffffff81f27e30-ffffffff81f27eaa: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex_base *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d39c0)
Location: kernel/locking/rtmutex_api.c:371
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
**Symbols:**

```
ffffffff820d39c0-ffffffff820d3a3a: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex_base *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82157c40)
Location: kernel/locking/rtmutex_api.c:371
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
**Symbols:**

```
ffffffff82157c40-ffffffff82157cba: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex_base *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223aab0)
Location: kernel/locking/rtmutex_api.c:371
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
**Symbols:**

```
ffffffff8223aab0-ffffffff8223ab2a: rt_mutex_wait_proxy_lock (STB_GLOBAL)
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
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016c340)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffff80001016c340-ffff80001016c430: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b7ba8)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c03b7ba8-c03b7c6c: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3ed0)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c0000000001c3ed0-c0000000001c3fd8: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010c4c8)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffe00010c4c8-ffffffe00010c56e: rt_mutex_wait_proxy_lock (STB_GLOBAL)
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
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ff390)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ff390-ffffffff810ff41a: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ef580)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ef580-ffffffff810ef604: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fc550)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810fc550-ffffffff810fc5da: rt_mutex_wait_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt_mutex_wait_proxy_lock(struct rt_mutex *lock, struct hrtimer_sleeper *to, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81107780)
Location: kernel/locking/rtmutex.c:1848
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81107780-ffffffff81107801: rt_mutex_wait_proxy_lock (STB_GLOBAL)
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
