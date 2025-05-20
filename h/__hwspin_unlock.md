# Function: <code>__hwspin_unlock</code>

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
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811d40)
Location: drivers/hwspinlock/hwspinlock_core.c:230
Inline: False
```
**Symbols:**

```
ffffffff81811d40-ffffffff81811dc0: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185bb30)
Location: drivers/hwspinlock/hwspinlock_core.c:249
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff8185bb30-ffffffff8185bbba: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187b250)
Location: drivers/hwspinlock/hwspinlock_core.c:249
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff8187b250-ffffffff8187b2da: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0840)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff818c0840-ffffffff818c08e2: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f3340)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff818f3340-ffffffff818f33e2: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8a40)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff819c8a40-ffffffff819c8ae3: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8790)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff819c8790-ffffffff819c8833: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad6e0)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff819ad6e0-ffffffff819ad783: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5bc40)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff81a5bc40-ffffffff81a5bce3: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb450)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff81bcb450-ffffffff81bcb510: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d74ca0)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff81d74ca0-ffffffff81d74d60: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de2bd0)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff81de2bd0-ffffffff81de2c91: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e98cc0)
Location: drivers/hwspinlock/hwspinlock_core.c:268
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff81e98cc0-ffffffff81e98d81: __hwspin_unlock (STB_GLOBAL)
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
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7ed08)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffff800010b7ed08-ffff800010b7edf8: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c61b90)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
c0c61b90-c0c61c50: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5b190)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
c000000000c5b190-c000000000c5b340: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072d112)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffe00072d112-ffffffe00072d236: __hwspin_unlock (STB_GLOBAL)
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
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81894670)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff81894670-ffffffff81894712: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184cb50)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff8184cb50-ffffffff8184cbec: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e8170)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff818e8170-ffffffff818e8212: __hwspin_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __hwspin_unlock(struct hwspinlock *hwlock, int mode, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819044c0)
Location: drivers/hwspinlock/hwspinlock_core.c:265
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq
  - drivers/base/regmap/regmap.c:regmap_unlock_hwlock
```
**Symbols:**

```
ffffffff819044c0-ffffffff81904556: __hwspin_unlock (STB_GLOBAL)
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
