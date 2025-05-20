# Function: <code>hwspin_lock_unregister</code>

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
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818115e0)
Location: drivers/hwspinlock/hwspinlock_core.c:456
Inline: False
```
**Symbols:**

```
ffffffff818115e0-ffffffff8181164c: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b430)
Location: drivers/hwspinlock/hwspinlock_core.c:483
Inline: False
```
**Symbols:**

```
ffffffff8185b430-ffffffff8185b49c: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187a910)
Location: drivers/hwspinlock/hwspinlock_core.c:512
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff8187a910-ffffffff8187a97c: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff818c0992-ffffffff818c09a5: hwspin_lock_unregister.cold (STB_LOCAL)
ffffffff818c0050-ffffffff818c00b4: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f2b70)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff818f2b70-ffffffff818f2bdc: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c84b0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff819c84b0-ffffffff819c851c: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8200)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff819c8200-ffffffff819c826c: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad150)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff819ad150-ffffffff819ad1bc: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5bbf0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81a5b660-ffffffff81a5b6cc: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcbdf0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81bcb7c0-ffffffff81bcb83f: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d758c0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81d750d0-ffffffff81d7514f: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de37fe)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81de3010-ffffffff81de308b: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e998ee)
Location: drivers/hwspinlock/hwspinlock_core.c:538
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81e99100-ffffffff81e9917b: hwspin_lock_unregister (STB_GLOBAL)
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
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e4c0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffff800010b7e4c0-ffff800010b7e568: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c621d0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
c0c621d0-c0c62268: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a250)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
c000000000c5a250-c000000000c5a328: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c8c8)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffe00072c8c8-ffffffe00072c94a: hwspin_lock_unregister (STB_GLOBAL)
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
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81893ea0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81893ea0-ffffffff81893f0c: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c5c0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff8184c5c0-ffffffff8184c62c: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e79a0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff818e79a0-ffffffff818e7a0c: hwspin_lock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hwspin_lock_unregister(struct hwspinlock_device *bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819046c0)
Location: drivers/hwspinlock/hwspinlock_core.c:534
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff819046c0-ffffffff8190472c: hwspin_lock_unregister (STB_GLOBAL)
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
