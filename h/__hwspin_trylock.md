# Function: <code>__hwspin_trylock</code>

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
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811b70)
Location: drivers/hwspinlock/hwspinlock_core.c:89
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff81811b70-ffffffff81811cb6: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b920)
Location: drivers/hwspinlock/hwspinlock_core.c:87
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff8185b920-ffffffff8185baa6: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187b040)
Location: drivers/hwspinlock/hwspinlock_core.c:87
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff8187b040-ffffffff8187b1c6: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0600)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff818c0600-ffffffff818c0788: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f3100)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff818f3100-ffffffff818f3288: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8af0)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff819c8af0-ffffffff819c8c7c: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8840)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff819c8840-ffffffff819c89cc: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad790)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff819ad790-ffffffff819ad917: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5bcf0)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff81a5bcf0-ffffffff81a5be77: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb2f0)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff81bcb2f0-ffffffff81bcb44e: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d74b20)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff81d74b20-ffffffff81d74c88: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de2a60)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff81de2a60-ffffffff81de2bbd: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e98b50)
Location: drivers/hwspinlock/hwspinlock_core.c:92
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff81e98b50-ffffffff81e98cad: __hwspin_trylock (STB_GLOBAL)
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
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7edf8)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffff800010b7edf8-ffff800010b7f044: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c619f4)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
c0c619f4-c0c61b90: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c59cf0)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
c000000000c59cf0-c000000000c59f64: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072d236)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffe00072d236-ffffffe00072d3ca: __hwspin_trylock (STB_GLOBAL)
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
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81894430)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff81894430-ffffffff818945b8: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c240)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff8184c240-ffffffff8184c3a2: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e7f30)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff818e7f30-ffffffff818e80b8: __hwspin_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __hwspin_trylock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904c50)
Location: drivers/hwspinlock/hwspinlock_core.c:91
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
**Symbols:**

```
ffffffff81904c50-ffffffff81904dcd: __hwspin_trylock (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
