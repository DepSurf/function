# Function: <code>devm_hwspin_lock_unregister</code>

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
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187afe0)
Location: drivers/hwspinlock/hwspinlock_core.c:561
Inline: True
```
**Symbols:**

```
ffffffff8187afe0-ffffffff8187b009: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0a19)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff818c0a19-ffffffff818c0a2c: devm_hwspin_lock_unregister.cold (STB_LOCAL)
ffffffff818c02b0-ffffffff818c02e3: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f2dd0)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff818f2dd0-ffffffff818f2df9: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c89e0)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff819c89e0-ffffffff819c8a09: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8730)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff819c8730-ffffffff819c8759: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad680)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff819ad680-ffffffff819ad6a9: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5b6d0)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: False
```
**Symbols:**

```
ffffffff81a5b6d0-ffffffff81a5b6f9: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb840)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: False
```
**Symbols:**

```
ffffffff81bcb840-ffffffff81bcb881: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d75160)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: False
```
**Symbols:**

```
ffffffff81d75160-ffffffff81d751a1: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de30a0)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: False
```
**Symbols:**

```
ffffffff81de30a0-ffffffff81de30e1: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e99190)
Location: drivers/hwspinlock/hwspinlock_core.c:587
Inline: False
```
**Symbols:**

```
ffffffff81e99190-ffffffff81e991d1: devm_hwspin_lock_unregister (STB_GLOBAL)
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
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e828)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffff800010b7e828-ffff800010b7e880: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c624c8)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
c0c624c8-c0c62524: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a350)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: False
```
**Symbols:**

```
c000000000c5a350-c000000000c5a3a8: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072d06e)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffe00072d06e-ffffffe00072d0c0: devm_hwspin_lock_unregister (STB_GLOBAL)
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
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81894100)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff81894100-ffffffff81894129: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c820)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff8184c820-ffffffff8184c849: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e7c00)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff818e7c00-ffffffff818e7c29: devm_hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devm_hwspin_lock_unregister(struct device *dev, struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904920)
Location: drivers/hwspinlock/hwspinlock_core.c:583
Inline: True
```
**Symbols:**

```
ffffffff81904920-ffffffff81904949: devm_hwspin_lock_unregister (STB_GLOBAL)
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
