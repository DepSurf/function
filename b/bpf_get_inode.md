# Function: <code>bpf_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81176c80)
Location: kernel/bpf/inode.c:81
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
Direct callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff81176c80-ffffffff81176cf4: bpf_get_inode.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81185720)
Location: kernel/bpf/inode.c:81
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff81185720-ffffffff811857b9: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81192980)
Location: kernel/bpf/inode.c:82
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff81192980-ffffffff81192a1a: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811997e0)
Location: kernel/bpf/inode.c:83
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811997e0-ffffffff8119988a: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811a8a80)
Location: kernel/bpf/inode.c:83
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811a8a80-ffffffff811a8b2a: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811bff10)
Location: kernel/bpf/inode.c:83
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811bff10-ffffffff811bffb2: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811d1360)
Location: kernel/bpf/inode.c:83
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811d1360-ffffffff811d1402: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e5690)
Location: kernel/bpf/inode.c:80
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811e5690-ffffffff811e5737: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f1df0)
Location: kernel/bpf/inode.c:81
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811f1df0-ffffffff811f1e97: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812139d0)
Location: kernel/bpf/inode.c:100
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff812139d0-ffffffff81213a77: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81215210)
Location: kernel/bpf/inode.c:101
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff81215210-ffffffff812152b7: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81217f20)
Location: kernel/bpf/inode.c:101
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff81217f20-ffffffff81217fce: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8124e580)
Location: kernel/bpf/inode.c:101
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff8124e580-ffffffff8124e62e: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812955c0)
Location: kernel/bpf/inode.c:101
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff812955c0-ffffffff81295692: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812f0330)
Location: kernel/bpf/inode.c:101
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff812f0330-ffffffff812f0402: bpf_get_inode (STB_LOCAL)
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
In kernel/bpf/inode.c (ffffffff8131d79d)
Location: kernel/bpf/inode.c:101
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff8131d3a0-ffffffff8131d422: bpf_get_inode.part.0 (STB_LOCAL)
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
In kernel/bpf/inode.c (ffffffff8133fb28)
Location: kernel/bpf/inode.c:101
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffff800010275bcc)
Location: kernel/bpf/inode.c:81
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffff800010275938-ffff8000102759d0: bpf_get_inode.part.0 (STB_LOCAL)
ffff8000102759d0-ffff800010275a44: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (c04a82c0)
Location: kernel/bpf/inode.c:81
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
c04a8084-c04a8138: bpf_get_inode.part.0 (STB_LOCAL)
c04a8138-c04a8180: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (c00000000031dd6c)
Location: kernel/bpf/inode.c:81
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
c00000000031da50-c00000000031db24: bpf_get_inode.part.0 (STB_LOCAL)
c00000000031db30-c00000000031db74: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffe0001ae20a)
Location: kernel/bpf/inode.c:81
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffe0001adfde-ffffffe0001ae05e: bpf_get_inode.part.0 (STB_LOCAL)
ffffffe0001ae05e-ffffffe0001ae0bc: bpf_get_inode (STB_LOCAL)
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
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811ea410)
Location: kernel/bpf/inode.c:81
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811ea410-ffffffff811ea4b7: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811dd1d0)
Location: kernel/bpf/inode.c:81
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811dd1d0-ffffffff811dd277: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e81e0)
Location: kernel/bpf/inode.c:81
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811e81e0-ffffffff811e8287: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *bpf_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f6590)
Location: kernel/bpf/inode.c:81
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811f6590-ffffffff811f6637: bpf_get_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
