# Function: <code>rt_mutex_postunlock</code>

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
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8190949f)
Location: kernel/locking/rtmutex.c:1452
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810d5ca0-ffffffff810d5cb0: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819935ef)
Location: kernel/locking/rtmutex.c:1447
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810ddc60-ffffffff810ddc70: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819efbe8)
Location: kernel/locking/rtmutex.c:1446
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810e62b0-ffffffff810e62c0: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2af38)
Location: kernel/locking/rtmutex.c:1446
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810f1830-ffffffff810f1840: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9bc4c)
Location: kernel/locking/rtmutex.c:1447
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff810fa120-ffffffff810fa130: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad359c)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81105f10-ffffffff81105f20: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb67d)
Location: kernel/locking/rtmutex.c:1443
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:wake_futex_pi
```
**Symbols:**

```
ffffffff81110e80-ffffffff81110e90: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c4451d)
Location: kernel/locking/rtmutex.c:1443
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:wake_futex_pi
```
**Symbols:**

```
ffffffff8110e030-ffffffff8110e040: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c3750d)
Location: kernel/locking/rtmutex.c:1299
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81c373b0-ffffffff81c373c0: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55d26)
Location: kernel/locking/rtmutex_api.c:457
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81d56070-ffffffff81d56087: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27c34)
Location: kernel/locking/rtmutex_api.c:479
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81f28030-ffffffff81f28064: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d3774)
Location: kernel/locking/rtmutex_api.c:479
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff820d3bf0-ffffffff820d3c24: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff821579f4)
Location: kernel/locking/rtmutex_api.c:479
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff82157e70-ffffffff82157ea4: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct rt_wake_q_head *wqh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223a864)
Location: kernel/locking/rtmutex_api.c:479
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff8223ace0-ffffffff8223ad14: rt_mutex_postunlock (STB_GLOBAL)
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
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da60e8)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffff80001016c0f0-ffff80001016c11c: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9de2c)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
c03b7a08-c03b7a24: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee87ac)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
c0000000001c3c40-c0000000001c3c74: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c85ba)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffe00010c2f2-ffffffe00010c31c: rt_mutex_postunlock (STB_GLOBAL)
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
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a7240c)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff810ff220-ffffffff810ff230: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e7dc)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff810ef410-ffffffff810ef420: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade81c)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff810fc3e0-ffffffff810fc3f0: rt_mutex_postunlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rt_mutex_postunlock(struct wake_q_head *wake_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aeac9c)
Location: kernel/locking/rtmutex.c:1445
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81107600-ffffffff81107620: rt_mutex_postunlock (STB_GLOBAL)
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
