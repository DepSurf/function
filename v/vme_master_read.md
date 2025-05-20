# Function: <code>vme_master_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816f1410)
Location: drivers/vme/vme.c:549
Inline: False
```
**Symbols:**

```
ffffffff816f1410-ffffffff816f14d8: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81756450)
Location: drivers/vme/vme.c:549
Inline: False
```
**Symbols:**

```
ffffffff81756450-ffffffff81756518: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81782a30)
Location: drivers/vme/vme.c:552
Inline: False
```
**Symbols:**

```
ffffffff81782a30-ffffffff81782af8: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817a17b0)
Location: drivers/vme/vme.c:672
Inline: False
```
**Symbols:**

```
ffffffff817a17b0-ffffffff817a1878: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff818188d0)
Location: drivers/vme/vme.c:668
Inline: False
```
**Symbols:**

```
ffffffff818188d0-ffffffff8181899d: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:668
Inline: False
```
**Symbols:**

```
ffffffff81862de5-ffffffff81862e2d: vme_master_read.cold.37 (STB_LOCAL)
ffffffff818621a0-ffffffff8186223a: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:668
Inline: False
```
**Symbols:**

```
ffffffff81882578-ffffffff818825c0: vme_master_read.cold.37 (STB_LOCAL)
ffffffff81881990-ffffffff81881a2a: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffffffff818ccbbd-ffffffff818ccc05: vme_master_read.cold (STB_LOCAL)
ffffffff818cbf80-ffffffff818cc020: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffffffff818fefad-ffffffff818feff5: vme_master_read.cold (STB_LOCAL)
ffffffff818fe370-ffffffff818fe410: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffffffff819d580f-ffffffff819d5857: vme_master_read.cold (STB_LOCAL)
ffffffff819d4030-ffffffff819d40c9: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:655
Inline: False
```
**Symbols:**

```
ffffffff81c2f7f9-ffffffff81c2f841: vme_master_read.cold (STB_LOCAL)
ffffffff819d3bb0-ffffffff819d3c49: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:655
Inline: False
```
**Symbols:**

```
ffffffff81c21abf-ffffffff81c21b07: vme_master_read.cold (STB_LOCAL)
ffffffff819b8e70-ffffffff819b8f09: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:655
Inline: False
```
**Symbols:**

```
ffffffff81d33822-ffffffff81d3386a: vme_master_read.cold (STB_LOCAL)
ffffffff81a67da0-ffffffff81a67e39: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:655
Inline: False
```
**Symbols:**

```
ffffffff81effc76-ffffffff81effcb4: vme_master_read.cold (STB_LOCAL)
ffffffff81bd9540-ffffffff81bd95df: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6ab80)
Location: drivers/staging/vme_user/vme.c:655
Inline: False
```
**Symbols:**

```
ffffffff81d6ab80-ffffffff81d6ac50: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd7e60)
Location: drivers/staging/vme_user/vme.c:655
Inline: False
```
**Symbols:**

```
ffffffff81dd7e60-ffffffff81dd7f30: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e92520)
Location: drivers/staging/vme_user/vme.c:618
Inline: False
```
**Symbols:**

```
ffffffff81e92520-ffffffff81e92625: vme_master_read (STB_GLOBAL)
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
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8e208)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffff800010b8e208-ffff800010b8e2dc: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c78584)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
c0c78584-c0c78668: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c6c510)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
c000000000c6c510-c000000000c6c630: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe000734022)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffffffe000734022-ffffffe0007340e0: vme_master_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffffffff818a02dd-ffffffff818a0325: vme_master_read.cold (STB_LOCAL)
ffffffff8189f6a0-ffffffff8189f740: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffffffff8185ba4d-ffffffff8185ba95: vme_master_read.cold (STB_LOCAL)
ffffffff8185ae10-ffffffff8185aeb0: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffffffff818ef9cd-ffffffff818efa15: vme_master_read.cold (STB_LOCAL)
ffffffff818eed90-ffffffff818eee30: vme_master_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t vme_master_read(struct vme_resource *resource, void *buf, size_t count, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:664
Inline: False
```
**Symbols:**

```
ffffffff81910aa5-ffffffff81910aed: vme_master_read.cold (STB_LOCAL)
ffffffff8190ff80-ffffffff81910020: vme_master_read (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
