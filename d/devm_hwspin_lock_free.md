# Function: <code>devm_hwspin_lock_free</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187b010)
Location: drivers/hwspinlock/hwspinlock_core.c:848
Inline: True
```
**Symbols:**

```
ffffffff8187b010-ffffffff8187b039: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0a2c)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff818c0a2c-ffffffff818c0a3f: devm_hwspin_lock_free.cold (STB_LOCAL)
ffffffff818c02f0-ffffffff818c0323: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f2e00)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff818f2e00-ffffffff818f2e29: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8a10)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff819c8a10-ffffffff819c8a39: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8760)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff819c8760-ffffffff819c8789: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad6b0)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff819ad6b0-ffffffff819ad6d9: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5b700)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: False
```
**Symbols:**

```
ffffffff81a5b700-ffffffff81a5b729: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb890)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: False
```
**Symbols:**

```
ffffffff81bcb890-ffffffff81bcb8d1: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d751c0)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: False
```
**Symbols:**

```
ffffffff81d751c0-ffffffff81d75201: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de3100)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: False
```
**Symbols:**

```
ffffffff81de3100-ffffffff81de3141: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e991f0)
Location: drivers/hwspinlock/hwspinlock_core.c:875
Inline: False
```
**Symbols:**

```
ffffffff81e991f0-ffffffff81e99231: devm_hwspin_lock_free (STB_GLOBAL)
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
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e880)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffff800010b7e880-ffff800010b7e8d8: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c62524)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
c0c62524-c0c62580: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a3b0)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: False
```
**Symbols:**

```
c000000000c5a3b0-c000000000c5a408: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072d0c0)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffe00072d0c0-ffffffe00072d112: devm_hwspin_lock_free (STB_GLOBAL)
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
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81894130)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff81894130-ffffffff81894159: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c850)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff8184c850-ffffffff8184c879: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e7c30)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff818e7c30-ffffffff818e7c59: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_free(struct device *dev, struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904950)
Location: drivers/hwspinlock/hwspinlock_core.c:870
Inline: True
```
**Symbols:**

```
ffffffff81904950-ffffffff81904979: devm_hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
