# Function: <code>rt_mutex_futex_trylock</code>

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
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81909390)
Location: kernel/locking/rtmutex.c:1515
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81909390-ffffffff81909401: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819934b0)
Location: kernel/locking/rtmutex.c:1510
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff819934b0-ffffffff8199351f: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819efa80)
Location: kernel/locking/rtmutex.c:1530
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff819efa80-ffffffff819efaee: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2add0)
Location: kernel/locking/rtmutex.c:1530
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81a2add0-ffffffff81a2ae3e: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9bad0)
Location: kernel/locking/rtmutex.c:1531
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81a9bad0-ffffffff81a9bb42: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad3420)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81ad3420-ffffffff81ad3492: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb520)
Location: kernel/locking/rtmutex.c:1527
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81bcb520-ffffffff81bcb59e: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c443c0)
Location: kernel/locking/rtmutex.c:1527
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81c443c0-ffffffff81c4443e: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c373c0)
Location: kernel/locking/rtmutex.c:1490
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81c373c0-ffffffff81c3743c: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55bd0)
Location: kernel/locking/rtmutex_api.c:126
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81d55bd0-ffffffff81d55c4c: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27aa0)
Location: kernel/locking/rtmutex_api.c:148
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81f27aa0-ffffffff81f27b28: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d35b0)
Location: kernel/locking/rtmutex_api.c:148
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
```
**Symbols:**

```
ffffffff820d35b0-ffffffff820d3638: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82157830)
Location: kernel/locking/rtmutex_api.c:148
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
```
**Symbols:**

```
ffffffff82157830-ffffffff821578b8: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223a6a0)
Location: kernel/locking/rtmutex_api.c:148
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8223a6a0-ffffffff8223a728: rt_mutex_futex_trylock (STB_GLOBAL)
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
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5e70)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffff800010da5e70-ffff800010da5f50: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9dc7c)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c0e9dc7c-c0e9dcfc: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee8550)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c000000000ee8550-c000000000ee8608: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c8446)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffe0008c8446-ffffffe0008c84be: rt_mutex_futex_trylock (STB_GLOBAL)
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
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a72290)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81a72290-ffffffff81a72302: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e660)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81a2e660-ffffffff81a2e6d2: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade6a0)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81ade6a0-ffffffff81ade712: rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aeab20)
Location: kernel/locking/rtmutex.c:1529
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81aeab20-ffffffff81aeab92: rt_mutex_futex_trylock (STB_GLOBAL)
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
