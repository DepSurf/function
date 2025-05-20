# Function: <code>devm_memremap_pages_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void devm_memremap_pages_release(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8118b580)
Location: kernel/memremap.c:157
Inline: False
```
**Symbols:**

```
ffffffff8118b580-ffffffff8118b59e: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void devm_memremap_pages_release(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119e120)
Location: kernel/memremap.c:234
Inline: False
```
**Symbols:**

```
ffffffff8119e120-ffffffff8119e2d3: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void devm_memremap_pages_release(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811adb40)
Location: kernel/memremap.c:234
Inline: False
```
**Symbols:**

```
ffffffff811adb40-ffffffff811add02: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void devm_memremap_pages_release(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b5040)
Location: kernel/memremap.c:222
Inline: False
```
**Symbols:**

```
ffffffff811b5040-ffffffff811b523a: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void devm_memremap_pages_release(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c92f0)
Location: kernel/memremap.c:286
Inline: False
```
**Symbols:**

```
ffffffff811c92f0-ffffffff811c9522: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811e9410)
Location: kernel/memremap.c:116
Inline: False
```
**Symbols:**

```
ffffffff811e9410-ffffffff811e9648: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811fa0a0)
Location: kernel/memremap.c:87
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff811fa0a0-ffffffff811fa2d5: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812c2520)
Location: mm/memremap.c:102
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812c2520-ffffffff812c2728: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4c07)
Location: mm/memremap.c:139
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812d4640-ffffffff812d4650: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130a9d7)
Location: mm/memremap.c:165
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff8130a980-ffffffff8130a990: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81316847)
Location: mm/memremap.c:187
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff81316500-ffffffff81316510: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131ca97)
Location: mm/memremap.c:187
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff8131c750-ffffffff8131c760: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81369de7)
Location: mm/memremap.c:184
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff81369a90-ffffffff81369aa0: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813e7ae6)
Location: mm/memremap.c:154
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff813e7430-ffffffff813e7446: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8146f7e6)
Location: mm/memremap.c:157
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff8146f0a0-ffffffff8146f0b6: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814a3fcd)
Location: mm/memremap.c:157
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff814a3880-ffffffff814a3896: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814d4e7d)
Location: mm/memremap.c:158
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff814d4720-ffffffff814d4736: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046e57c)
Location: mm/memremap.c:139
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
c00000000046de50-c00000000046de64: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cd1e7)
Location: mm/memremap.c:139
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812ccc20-ffffffff812ccc30: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812be057)
Location: mm/memremap.c:139
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812bda90-ffffffff812bdaa0: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812caff7)
Location: mm/memremap.c:139
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812caa30-ffffffff812caa40: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_memremap_pages_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812dbd57)
Location: mm/memremap.c:139
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812db750-ffffffff812db760: devm_memremap_pages_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>void *res</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, data</code> ➡️ <code>data</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
