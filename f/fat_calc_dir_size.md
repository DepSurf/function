# Function: <code>fat_calc_dir_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fb850)
Location: fs/fat/inode.c:435
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff812fb850-ffffffff812fb8d7: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8132f400)
Location: fs/fat/inode.c:466
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff8132f400-ffffffff8132f487: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81345160)
Location: fs/fat/inode.c:466
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81345160-ffffffff813451e7: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81359bd0)
Location: fs/fat/inode.c:466
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81359bd0-ffffffff81359c57: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8137e8e0)
Location: fs/fat/inode.c:466
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff8137e8e0-ffffffff8137e967: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813ad190)
Location: fs/fat/inode.c:473
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff813ad190-ffffffff813ad217: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813c6540)
Location: fs/fat/inode.c:473
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff813c6540-ffffffff813c65c7: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813f1050)
Location: fs/fat/inode.c:474
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff813f1050-ffffffff813f10d7: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8140af30)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff8140af30-ffffffff8140afb7: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8145a28a)
Location: fs/fat/inode.c:479
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814765da)
Location: fs/fat/inode.c:479
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
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
In fs/fat/inode.c (ffffffff8147c04a)
Location: fs/fat/inode.c:479
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:480
Inline: True
Direct callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff814d3210-ffffffff814d32a2: fat_calc_dir_size.constprop.0 (STB_LOCAL)
ffffffff81cd00a6-ffffffff81cd00c6: fat_calc_dir_size.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:481
Inline: True
Direct callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81560220-ffffffff815602cc: fat_calc_dir_size.constprop.0 (STB_LOCAL)
ffffffff81e832d5-ffffffff81e832f5: fat_calc_dir_size.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:476
Inline: True
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff816026c0-ffffffff8160276c: fat_calc_dir_size.constprop.0 (STB_LOCAL)
ffffffff82072249-ffffffff82072269: fat_calc_dir_size.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:476
Inline: True
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff8163a5e0-ffffffff8163a68c: fat_calc_dir_size.constprop.0 (STB_LOCAL)
ffffffff820f1e6c-ffffffff820f1e8c: fat_calc_dir_size.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:476
Inline: True
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81673ad0-ffffffff81673b7c: fat_calc_dir_size.constprop.0 (STB_LOCAL)
ffffffff821cf14e-ffffffff821cf16e: fat_calc_dir_size.constprop.0.cold (STB_LOCAL)
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
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104eb930)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffff8000104eb930-ffff8000104eb9d0: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06a9924)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
c06a9924-c06a99d4: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c000000000629eb0)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
c000000000629eb0-c000000000629fa4: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035c202)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffe00035c202-ffffffe00035c270: fat_calc_dir_size (STB_LOCAL)
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
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81403510)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81403510-ffffffff81403597: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813f3f90)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff813f3f90-ffffffff813f4017: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81400890)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81400890-ffffffff81400917: fat_calc_dir_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fat_calc_dir_size(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81416690)
Location: fs/fat/inode.c:479
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81416690-ffffffff81416717: fat_calc_dir_size (STB_LOCAL)
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
