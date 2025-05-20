# Function: <code>rt_mutex_cleanup_proxy_lock</code>

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
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5e90)
Location: kernel/locking/rtmutex.c:1842
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810d5e90-ffffffff810d5f11: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810dde50)
Location: kernel/locking/rtmutex.c:1841
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810dde50-ffffffff810dded1: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e64a0)
Location: kernel/locking/rtmutex.c:1862
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810e64a0-ffffffff810e6521: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f1a20)
Location: kernel/locking/rtmutex.c:1889
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810f1a20-ffffffff810f1aa1: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fa320)
Location: kernel/locking/rtmutex.c:1890
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810fa320-ffffffff810fa3a3: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81106110)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81106110-ffffffff81106193: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff811110b0)
Location: kernel/locking/rtmutex.c:1886
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff811110b0-ffffffff8111113b: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110e260)
Location: kernel/locking/rtmutex.c:1885
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8110e260-ffffffff8110e2eb: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c37740)
Location: kernel/locking/rtmutex.c:1742
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81c37740-ffffffff81c377c9: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55f10)
Location: kernel/locking/rtmutex_api.c:389
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81d55f10-ffffffff81d55f99: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27eb0)
Location: kernel/locking/rtmutex_api.c:411
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
**Symbols:**

```
ffffffff81f27eb0-ffffffff81f27f3a: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d3a50)
Location: kernel/locking/rtmutex_api.c:411
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
**Symbols:**

```
ffffffff820d3a50-ffffffff820d3ada: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82157cd0)
Location: kernel/locking/rtmutex_api.c:411
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
**Symbols:**

```
ffffffff82157cd0-ffffffff82157d5a: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223ab40)
Location: kernel/locking/rtmutex_api.c:411
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
**Symbols:**

```
ffffffff8223ab40-ffffffff8223abca: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
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
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016c430)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffff80001016c430-ffff80001016c50c: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b7c6c)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c03b7c6c-c03b7d14: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3fe0)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c0000000001c3fe0-c0000000001c40d0: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010c56e)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffe00010c56e-ffffffe00010c61c: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
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
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ff420)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ff420-ffffffff810ff4a3: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ef610)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810ef610-ffffffff810ef68d: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fc5e0)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff810fc5e0-ffffffff810fc663: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rt_mutex_cleanup_proxy_lock(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81107810)
Location: kernel/locking/rtmutex.c:1888
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81107810-ffffffff8110788a: rt_mutex_cleanup_proxy_lock (STB_GLOBAL)
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
