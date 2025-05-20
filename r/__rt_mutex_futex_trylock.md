# Function: <code>__rt_mutex_futex_trylock</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993520)
Location: kernel/locking/rtmutex.c:1515
Inline: False
```
**Symbols:**

```
ffffffff81993520-ffffffff8199355f: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819efaf0)
Location: kernel/locking/rtmutex.c:1535
Inline: False
```
**Symbols:**

```
ffffffff819efaf0-ffffffff819efb2b: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2ae40)
Location: kernel/locking/rtmutex.c:1535
Inline: False
```
**Symbols:**

```
ffffffff81a2ae40-ffffffff81a2ae7b: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9bb50)
Location: kernel/locking/rtmutex.c:1536
Inline: False
```
**Symbols:**

```
ffffffff81a9bb50-ffffffff81a9bb8e: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad34a0)
Location: kernel/locking/rtmutex.c:1534
Inline: False
```
**Symbols:**

```
ffffffff81ad34a0-ffffffff81ad34de: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb5a0)
Location: kernel/locking/rtmutex.c:1532
Inline: False
Direct callers:
  - kernel/futex.c:fixup_pi_state_owner
```
**Symbols:**

```
ffffffff81bcb5a0-ffffffff81bcb5e3: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c44440)
Location: kernel/locking/rtmutex.c:1532
Inline: False
Direct callers:
  - kernel/futex.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff81c44440-ffffffff81c44483: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c37440)
Location: kernel/locking/rtmutex.c:1495
Inline: False
Direct callers:
  - kernel/futex.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff81c37440-ffffffff81c3747d: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55c50)
Location: kernel/locking/rtmutex_api.c:131
Inline: False
Direct callers:
  - kernel/futex.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff81d55c50-ffffffff81d55c8d: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27b30)
Location: kernel/locking/rtmutex_api.c:153
Inline: False
Direct callers:
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff81f27b30-ffffffff81f27b77: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d3650)
Location: kernel/locking/rtmutex_api.c:153
Inline: False
Direct callers:
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff820d3650-ffffffff820d3697: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff821578d0)
Location: kernel/locking/rtmutex_api.c:153
Inline: False
Direct callers:
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff821578d0-ffffffff82157917: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex_base *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223a740)
Location: kernel/locking/rtmutex_api.c:153
Inline: False
Direct callers:
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff8223a740-ffffffff8223a787: __rt_mutex_futex_trylock (STB_GLOBAL)
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
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5f50)
Location: kernel/locking/rtmutex.c:1534
Inline: False
```
**Symbols:**

```
ffff800010da5f50-ffff800010da5f9c: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9dcfc)
Location: kernel/locking/rtmutex.c:1534
Inline: False
Direct callers:
  - kernel/futex.c:fixup_pi_state_owner
```
**Symbols:**

```
c0e9dcfc-c0e9dd4c: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee8610)
Location: kernel/locking/rtmutex.c:1534
Inline: False
```
**Symbols:**

```
c000000000ee8610-c000000000ee8678: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c84be)
Location: kernel/locking/rtmutex.c:1534
Inline: False
```
**Symbols:**

```
ffffffe0008c84be-ffffffe0008c8502: __rt_mutex_futex_trylock (STB_GLOBAL)
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
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a72310)
Location: kernel/locking/rtmutex.c:1534
Inline: False
```
**Symbols:**

```
ffffffff81a72310-ffffffff81a7234e: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e6e0)
Location: kernel/locking/rtmutex.c:1534
Inline: False
```
**Symbols:**

```
ffffffff81a2e6e0-ffffffff81a2e71e: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade720)
Location: kernel/locking/rtmutex.c:1534
Inline: False
```
**Symbols:**

```
ffffffff81ade720-ffffffff81ade75e: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aeaba0)
Location: kernel/locking/rtmutex.c:1534
Inline: False
```
**Symbols:**

```
ffffffff81aeaba0-ffffffff81aeabde: __rt_mutex_futex_trylock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
