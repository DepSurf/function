# Function: <code>configfs_fill_super</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int configfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff812e1850)
Location: fs/configfs/mount.c:69
Inline: True
```
**Symbols:**

```
ffffffff812e1850-ffffffff812e1957: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int configfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813061a0)
Location: fs/configfs/mount.c:69
Inline: True
```
**Symbols:**

```
ffffffff813061a0-ffffffff813062a7: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813341b0)
Location: fs/configfs/mount.c:69
Inline: False
```
**Symbols:**

```
ffffffff813341b0-ffffffff813342ac: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff8134b520)
Location: fs/configfs/mount.c:69
Inline: False
```
**Symbols:**

```
ffffffff8134b520-ffffffff8134b61c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81373f10)
Location: fs/configfs/mount.c:56
Inline: False
```
**Symbols:**

```
ffffffff81373f10-ffffffff8137400c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff8138c150)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
ffffffff8138c150-ffffffff8138c24c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813d7490)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
ffffffff813d7490-ffffffff813d758c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813e9130)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
ffffffff813e9130-ffffffff813e922c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813efca0)
Location: fs/configfs/mount.c:63
Inline: False
```
**Symbols:**

```
ffffffff813efca0-ffffffff813efd9c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81441b90)
Location: fs/configfs/mount.c:63
Inline: False
```
**Symbols:**

```
ffffffff81441b90-ffffffff81441c86: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff814bd780)
Location: fs/configfs/mount.c:63
Inline: False
```
**Symbols:**

```
ffffffff814bd780-ffffffff814bd876: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81555430)
Location: fs/configfs/mount.c:63
Inline: False
```
**Symbols:**

```
ffffffff81555430-ffffffff81555526: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff8158d1d0)
Location: fs/configfs/mount.c:63
Inline: False
```
**Symbols:**

```
ffffffff8158d1d0-ffffffff8158d2c6: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff815c5f10)
Location: fs/configfs/mount.c:63
Inline: False
```
**Symbols:**

```
ffffffff815c5f10-ffffffff815c6009: configfs_fill_super (STB_LOCAL)
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
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffff80001045db20)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
ffff80001045db20-ffff80001045dc4c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (c061e72c)
Location: fs/configfs/mount.c:65
Inline: True
```
**Symbols:**

```
c061e72c-c061e848: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (c0000000005796e0)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
c0000000005796e0-c000000000579838: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffe0002ed9c2)
Location: fs/configfs/mount.c:65
Inline: True
```
**Symbols:**

```
ffffffe0002ed9c2-ffffffe0002edae4: configfs_fill_super (STB_LOCAL)
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
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81384730)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
ffffffff81384730-ffffffff8138482c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813751c0)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
ffffffff813751c0-ffffffff813752bc: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81382200)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
ffffffff81382200-ffffffff813822fc: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81395d20)
Location: fs/configfs/mount.c:65
Inline: False
```
**Symbols:**

```
ffffffff81395d20-ffffffff81395e1c: configfs_fill_super (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
<b>Param removed. </b>
<code>int silent</code>
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
