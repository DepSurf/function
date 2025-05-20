# Function: <code>kernfs_test_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kernfs_test_super(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812884e0)
Location: fs/kernfs/mount.c:169
Inline: True
```
**Symbols:**

```
ffffffff812884e0-ffffffff8128852e: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812b5960)
Location: fs/kernfs/mount.c:185
Inline: False
```
**Symbols:**

```
ffffffff812b5960-ffffffff812b5991: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812cb1f0)
Location: fs/kernfs/mount.c:186
Inline: False
```
**Symbols:**

```
ffffffff812cb1f0-ffffffff812cb221: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812d8670)
Location: fs/kernfs/mount.c:186
Inline: False
```
**Symbols:**

```
ffffffff812d8670-ffffffff812d869e: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812fcda0)
Location: fs/kernfs/mount.c:259
Inline: False
```
**Symbols:**

```
ffffffff812fcda0-ffffffff812fcdce: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8132a9b0)
Location: fs/kernfs/mount.c:259
Inline: False
```
**Symbols:**

```
ffffffff8132a9b0-ffffffff8132a9de: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81341d10)
Location: fs/kernfs/mount.c:266
Inline: False
```
**Symbols:**

```
ffffffff81341d10-ffffffff81341d3e: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136a130)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
ffffffff8136a130-ffffffff8136a162: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81382320)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
ffffffff81382320-ffffffff81382352: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813cca20)
Location: fs/kernfs/mount.c:277
Inline: False
```
**Symbols:**

```
ffffffff813cca20-ffffffff813cca55: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813de670)
Location: fs/kernfs/mount.c:277
Inline: False
```
**Symbols:**

```
ffffffff813de670-ffffffff813de6a5: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813e53c0)
Location: fs/kernfs/mount.c:277
Inline: False
```
**Symbols:**

```
ffffffff813e53c0-ffffffff813e53f5: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81436f90)
Location: fs/kernfs/mount.c:277
Inline: False
```
**Symbols:**

```
ffffffff81436f90-ffffffff81436fc5: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff814b1b10)
Location: fs/kernfs/mount.c:278
Inline: False
```
**Symbols:**

```
ffffffff814b1b10-ffffffff814b1b5d: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815485a0)
Location: fs/kernfs/mount.c:281
Inline: False
```
**Symbols:**

```
ffffffff815485a0-ffffffff815485ed: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81580160)
Location: fs/kernfs/mount.c:281
Inline: False
```
**Symbols:**

```
ffffffff81580160-ffffffff815801ad: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815b8b50)
Location: fs/kernfs/mount.c:288
Inline: False
```
**Symbols:**

```
ffffffff815b8b50-ffffffff815b8b9d: kernfs_test_super (STB_LOCAL)
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
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffff800010450638)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
ffff800010450638-ffff800010450698: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c06136c8)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
c06136c8-c061370c: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c0000000005687a0)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
c0000000005687a0-c0000000005687e8: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffe0002e3644)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
ffffffe0002e3644-ffffffe0002e3690: kernfs_test_super (STB_LOCAL)
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
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8137a900)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
ffffffff8137a900-ffffffff8137a932: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136b3d0)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
ffffffff8136b3d0-ffffffff8136b402: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813783d0)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
ffffffff813783d0-ffffffff81378402: kernfs_test_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_test_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8138be80)
Location: fs/kernfs/mount.c:254
Inline: False
```
**Symbols:**

```
ffffffff8138be80-ffffffff8138beb2: kernfs_test_super (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fs_context *fc</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
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
