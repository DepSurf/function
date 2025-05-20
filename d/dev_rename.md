# Function: <code>dev_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_rename(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816a9950)
Location: drivers/md/dm-ioctl.c:891
Inline: False
```
**Symbols:**

```
ffffffff816a9950-ffffffff816a9d49: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_rename(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81709db0)
Location: drivers/md/dm-ioctl.c:891
Inline: False
```
**Symbols:**

```
ffffffff81709db0-ffffffff8170a1ad: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_rename(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173bc80)
Location: drivers/md/dm-ioctl.c:891
Inline: False
```
**Symbols:**

```
ffffffff8173bc80-ffffffff8173c07d: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81755540)
Location: drivers/md/dm-ioctl.c:896
Inline: False
```
**Symbols:**

```
ffffffff81755540-ffffffff81755937: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c77e0)
Location: drivers/md/dm-ioctl.c:903
Inline: False
```
**Symbols:**

```
ffffffff817c77e0-ffffffff817c7bd7: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:903
Inline: False
```
**Symbols:**

```
ffffffff81810920-ffffffff81810c62: dev_rename (STB_LOCAL)
ffffffff818119d7-ffffffff81811abb: dev_rename.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:903
Inline: False
```
**Symbols:**

```
ffffffff8183c920-ffffffff8183cc62: dev_rename (STB_LOCAL)
ffffffff8183d97f-ffffffff8183da63: dev_rename.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:903
Inline: False
```
**Symbols:**

```
ffffffff8187f000-ffffffff8187f349: dev_rename (STB_LOCAL)
ffffffff8188050a-ffffffff818805f1: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffffffff818b0e80-ffffffff818b11c9: dev_rename (STB_LOCAL)
ffffffff818b23ca-ffffffff818b24b1: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffffffff81981d50-ffffffff81981e0c: dev_rename (STB_LOCAL)
ffffffff81982bd7-ffffffff81982c03: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffffffff81986370-ffffffff8198642c: dev_rename (STB_LOCAL)
ffffffff81c28515-ffffffff81c28541: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1005
Inline: False
```
**Symbols:**

```
ffffffff81969f20-ffffffff81969fe6: dev_rename (STB_LOCAL)
ffffffff81c1a619-ffffffff81c1a645: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1012
Inline: False
```
**Symbols:**

```
ffffffff81a123c0-ffffffff81a12486: dev_rename (STB_LOCAL)
ffffffff81d2a480-ffffffff81d2a4ac: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1019
Inline: False
```
**Symbols:**

```
ffffffff81b7abb0-ffffffff81b7ac83: dev_rename (STB_LOCAL)
ffffffff81ef66d7-ffffffff81ef66fb: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d19ec0)
Location: drivers/md/dm-ioctl.c:1019
Inline: False
```
**Symbols:**

```
ffffffff81d19ec0-ffffffff81d19f9b: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d83020)
Location: drivers/md/dm-ioctl.c:1044
Inline: False
```
**Symbols:**

```
ffffffff81d83020-ffffffff81d830f1: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e3a6e0)
Location: drivers/md/dm-ioctl.c:1044
Inline: False
```
**Symbols:**

```
ffffffff81e3a6e0-ffffffff81e3a7b1: dev_rename (STB_LOCAL)
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
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b080d0)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffff800010b080d0-ffff800010b084b0: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be6e98)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
c0be6e98-c0be7240: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bf9540)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
c000000000bf9540-c000000000bf9a40: dev_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f688e)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffffffe0006f688e-ffffffe0006f6c24: dev_rename (STB_LOCAL)
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
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffffffff81856d00-ffffffff81857049: dev_rename (STB_LOCAL)
ffffffff8185824a-ffffffff81858331: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffffffff8181e310-ffffffff8181e659: dev_rename (STB_LOCAL)
ffffffff8181f85a-ffffffff8181f941: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffffffff818a6330-ffffffff818a6679: dev_rename (STB_LOCAL)
ffffffff818a787a-ffffffff818a7961: dev_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dev_rename(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:928
Inline: False
```
**Symbols:**

```
ffffffff818c2570-ffffffff818c28b9: dev_rename (STB_LOCAL)
ffffffff818c3aba-ffffffff818c3ba1: dev_rename.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *filp</code>
</li>
<li>
<b>Param reordered. </b>
<code>param, param_size</code> ➡️ <code>filp, param, param_size</code>
</li>
</ul>
</details>
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
