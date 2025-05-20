# Function: <code>__hwspin_lock_timeout</code>

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
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811cc0)
Location: drivers/hwspinlock/hwspinlock_core.c:178
Inline: False
```
**Symbols:**

```
ffffffff81811cc0-ffffffff81811d3c: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185bab0)
Location: drivers/hwspinlock/hwspinlock_core.c:197
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff8185bab0-ffffffff8185bb2c: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187b1d0)
Location: drivers/hwspinlock/hwspinlock_core.c:197
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff8187b1d0-ffffffff8187b24c: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0790)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff818c0790-ffffffff818c083a: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f3290)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff818f3290-ffffffff818f333a: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8c80)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff819c8c80-ffffffff819c8d2a: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c89d0)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff819c89d0-ffffffff819c8a7a: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad920)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff819ad920-ffffffff819ad9ca: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5be80)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff81a5be80-ffffffff81a5bf2a: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb590)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff81bcb590-ffffffff81bcb64c: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d74e10)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff81d74e10-ffffffff81d74ecc: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de2d50)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff81de2d50-ffffffff81de2e0c: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e98e40)
Location: drivers/hwspinlock/hwspinlock_core.c:209
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff81e98e40-ffffffff81e98efc: __hwspin_lock_timeout (STB_GLOBAL)
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
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7f048)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffff800010b7f048-ffff800010b7f144: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c61c50)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
c0c61c50-c0c61d30: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c59ff0)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
c000000000c59ff0-c000000000c5a160: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072d3ca)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffe00072d3ca-ffffffe00072d498: __hwspin_lock_timeout (STB_GLOBAL)
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
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818945c0)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff818945c0-ffffffff8189466a: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c3b0)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff8184c3b0-ffffffff8184c45a: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e80c0)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff818e80c0-ffffffff818e816a: __hwspin_lock_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock *hwlock, unsigned int to, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904dd0)
Location: drivers/hwspinlock/hwspinlock_core.c:206
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_lock_hwlock
```
**Symbols:**

```
ffffffff81904dd0-ffffffff81904e7a: __hwspin_lock_timeout (STB_GLOBAL)
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
