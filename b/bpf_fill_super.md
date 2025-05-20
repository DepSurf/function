# Function: <code>bpf_fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81176fb0)
Location: kernel/bpf/inode.c:337
Inline: True
```
**Symbols:**

```
ffffffff81176fb0-ffffffff81176ffd: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81185a50)
Location: kernel/bpf/inode.c:337
Inline: True
```
**Symbols:**

```
ffffffff81185a50-ffffffff81185a9d: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81192bf0)
Location: kernel/bpf/inode.c:415
Inline: False
```
**Symbols:**

```
ffffffff81192bf0-ffffffff81192cec: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81199aa0)
Location: kernel/bpf/inode.c:442
Inline: False
```
**Symbols:**

```
ffffffff81199aa0-ffffffff81199b9d: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811a8e30)
Location: kernel/bpf/inode.c:486
Inline: False
```
**Symbols:**

```
ffffffff811a8e30-ffffffff811a8f2d: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811c04c0)
Location: kernel/bpf/inode.c:631
Inline: False
```
**Symbols:**

```
ffffffff811c04c0-ffffffff811c05b1: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811d1920)
Location: kernel/bpf/inode.c:632
Inline: False
```
**Symbols:**

```
ffffffff811d1920-ffffffff811d1a11: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e5c60)
Location: kernel/bpf/inode.c:627
Inline: False
```
**Symbols:**

```
ffffffff811e5c60-ffffffff811e5d4a: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f2200)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
ffffffff811f2200-ffffffff811f225b: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81213e40)
Location: kernel/bpf/inode.c:643
Inline: False
```
**Symbols:**

```
ffffffff81213e40-ffffffff81213ea0: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81215e70)
Location: kernel/bpf/inode.c:751
Inline: False
```
**Symbols:**

```
ffffffff81215e70-ffffffff81215ee4: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81218a60)
Location: kernel/bpf/inode.c:752
Inline: False
```
**Symbols:**

```
ffffffff81218a60-ffffffff81218ad4: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8124f0b0)
Location: kernel/bpf/inode.c:762
Inline: False
```
**Symbols:**

```
ffffffff8124f0b0-ffffffff8124f124: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81296160)
Location: kernel/bpf/inode.c:743
Inline: False
```
**Symbols:**

```
ffffffff81296160-ffffffff812961de: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812f1030)
Location: kernel/bpf/inode.c:743
Inline: False
```
**Symbols:**

```
ffffffff812f1030-ffffffff812f10ae: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8131dcc0)
Location: kernel/bpf/inode.c:742
Inline: False
```
**Symbols:**

```
ffffffff8131dcc0-ffffffff8131dd3e: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff813400d0)
Location: kernel/bpf/inode.c:784
Inline: False
```
**Symbols:**

```
ffffffff813400d0-ffffffff8134015e: bpf_fill_super (STB_LOCAL)
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
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffff8000102756a8)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
ffff8000102756a8-ffff800010275730: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (c04a7e44)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
c04a7e44-c04a7ebc: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (c00000000031d730)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
c00000000031d730-c00000000031d7d0: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffe0001addba)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
ffffffe0001addba-ffffffe0001ade32: bpf_fill_super (STB_LOCAL)
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
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811ea820)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
ffffffff811ea820-ffffffff811ea87b: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811dd5e0)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
ffffffff811dd5e0-ffffffff811dd63b: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e85f0)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
ffffffff811e85f0-ffffffff811e864b: bpf_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f69a0)
Location: kernel/bpf/inode.c:625
Inline: False
```
**Symbols:**

```
ffffffff811f69a0-ffffffff811f69fb: bpf_fill_super (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fs_context *fc</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>int silent</code>
</li>
</ul>
</details>
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
