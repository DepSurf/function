# Function: <code>fuse_force_forget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81311650)
Location: fs/fuse/dev.c:644
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81311650-ffffffff813116f4: fuse_force_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81345ac0)
Location: fs/fuse/dev.c:619
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81345ac0-ffffffff81345b64: fuse_force_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8135b7e0)
Location: fs/fuse/dev.c:623
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8135b7e0-ffffffff8135b884: fuse_force_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81370170)
Location: fs/fuse/dev.c:622
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81370170-ffffffff81370214: fuse_force_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81394e70)
Location: fs/fuse/dev.c:622
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81394e70-ffffffff81394f14: fuse_force_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c3f90)
Location: fs/fuse/dev.c:635
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813c3f90-ffffffff813c4035: fuse_force_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dd760)
Location: fs/fuse/dev.c:689
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813dd760-ffffffff813dd805: fuse_force_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81409290)
Location: fs/fuse/dev.c:713
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81409290-ffffffff81409338: fuse_force_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8142fc20)
Location: fs/fuse/readdir.c:252
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8142fc20-ffffffff8142fcaa: fuse_force_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8147fbe0)
Location: fs/fuse/readdir.c:252
Inline: True
Direct callers:
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffffffff8147fbe0-ffffffff8147fc62: fuse_force_forget.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8149b2c0)
Location: fs/fuse/readdir.c:252
Inline: True
Direct callers:
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffffffff8149b2c0-ffffffff8149b342: fuse_force_forget.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814a13b0)
Location: fs/fuse/readdir.c:255
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814f9460)
Location: fs/fuse/readdir.c:255
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81588f04)
Location: fs/fuse/readdir.c:255
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8162f401)
Location: fs/fuse/readdir.c:257
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8166766d)
Location: fs/fuse/readdir.c:257
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff816a19bd)
Location: fs/fuse/readdir.c:265
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffff800010514620)
Location: fs/fuse/readdir.c:252
Inline: False
Direct callers:
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff800010514620-ffff8000105146d4: fuse_force_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c06cf970)
Location: fs/fuse/readdir.c:252
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c00000000065ca40)
Location: fs/fuse/readdir.c:252
Inline: False
Direct callers:
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c00000000065ca40-c00000000065cb0c: fuse_force_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffe00037e196)
Location: fs/fuse/readdir.c:252
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe00037e196-ffffffe00037e22a: fuse_force_forget (STB_LOCAL)
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
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81428200)
Location: fs/fuse/readdir.c:252
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81428200-ffffffff8142828a: fuse_force_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81418c80)
Location: fs/fuse/readdir.c:252
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81418c80-ffffffff81418d0a: fuse_force_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814243a0)
Location: fs/fuse/readdir.c:252
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814243a0-ffffffff8142442a: fuse_force_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_force_forget(struct file *file, u64 nodeid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8143b1e0)
Location: fs/fuse/readdir.c:252
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8143b1e0-ffffffff8143b26a: fuse_force_forget (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
