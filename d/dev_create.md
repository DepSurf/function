# Function: <code>dev_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_create(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816aa690)
Location: drivers/md/dm-ioctl.c:734
Inline: False
```
**Symbols:**

```
ffffffff816aa690-ffffffff816aa994: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_create(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8170ab10)
Location: drivers/md/dm-ioctl.c:734
Inline: False
```
**Symbols:**

```
ffffffff8170ab10-ffffffff8170ae2e: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_create(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173c9e0)
Location: drivers/md/dm-ioctl.c:734
Inline: False
```
**Symbols:**

```
ffffffff8173c9e0-ffffffff8173ccfe: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81756300)
Location: drivers/md/dm-ioctl.c:739
Inline: False
```
**Symbols:**

```
ffffffff81756300-ffffffff81756629: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c8510)
Location: drivers/md/dm-ioctl.c:746
Inline: False
```
**Symbols:**

```
ffffffff817c8510-ffffffff817c8839: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:746
Inline: False
```
**Symbols:**

```
ffffffff81810fb0-ffffffff818112db: dev_create (STB_LOCAL)
ffffffff81811abb-ffffffff81811ad2: dev_create.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:746
Inline: False
```
**Symbols:**

```
ffffffff8183cfb0-ffffffff8183d2db: dev_create (STB_LOCAL)
ffffffff8183da63-ffffffff8183da7a: dev_create.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8187fa80)
Location: drivers/md/dm-ioctl.c:746
Inline: False
```
**Symbols:**

```
ffffffff8187fa80-ffffffff8187fb58: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818b1940)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffffffff818b1940-ffffffff818b1a18: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffffffff81981c50-ffffffff81981d43: dev_create (STB_LOCAL)
ffffffff81982bc0-ffffffff81982bd7: dev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffffffff81986270-ffffffff81986363: dev_create (STB_LOCAL)
ffffffff81c284fe-ffffffff81c28515: dev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:848
Inline: False
```
**Symbols:**

```
ffffffff81969bb0-ffffffff81969ca3: dev_create (STB_LOCAL)
ffffffff81c1a562-ffffffff81c1a579: dev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:853
Inline: False
```
**Symbols:**

```
ffffffff81a12040-ffffffff81a12133: dev_create (STB_LOCAL)
ffffffff81d2a3b5-ffffffff81d2a3cc: dev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:854
Inline: False
```
**Symbols:**

```
ffffffff81b7a850-ffffffff81b7a94b: dev_create (STB_LOCAL)
ffffffff81ef65cf-ffffffff81ef65e6: dev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d19a30)
Location: drivers/md/dm-ioctl.c:854
Inline: False
```
**Symbols:**

```
ffffffff81d19a30-ffffffff81d19b55: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d82bd0)
Location: drivers/md/dm-ioctl.c:879
Inline: False
```
**Symbols:**

```
ffffffff81d82bd0-ffffffff81d82cc0: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e3a290)
Location: drivers/md/dm-ioctl.c:879
Inline: False
```
**Symbols:**

```
ffffffff81e3a290-ffffffff81e3a380: dev_create (STB_LOCAL)
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
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b08728)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffff800010b08728-ffff800010b08818: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be74b0)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
c0be74b0-c0be75a4: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bfa120)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
c000000000bfa120-c000000000bfa254: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f6eaa)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffffffe0006f6eaa-ffffffe0006f6f94: dev_create (STB_LOCAL)
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
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818577c0)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffffffff818577c0-ffffffff81857898: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8181edd0)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffffffff8181edd0-ffffffff8181eea8: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818a6df0)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffffffff818a6df0-ffffffff818a6ec8: dev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_create(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818c3030)
Location: drivers/md/dm-ioctl.c:771
Inline: False
```
**Symbols:**

```
ffffffff818c3030-ffffffff818c3108: dev_create (STB_LOCAL)
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
