# Function: <code>proc_fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81279c90)
Location: fs/proc/inode.c:458
Inline: False
Direct callers:
  - fs/proc/root.c:proc_mount
```
**Symbols:**

```
ffffffff81279c90-ffffffff81279d31: proc_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff812a6a00)
Location: fs/proc/inode.c:460
Inline: False
```
**Symbols:**

```
ffffffff812a6a00-ffffffff812a6b25: proc_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff812bc2e0)
Location: fs/proc/inode.c:473
Inline: False
```
**Symbols:**

```
ffffffff812bc2e0-ffffffff812bc405: proc_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff812c96a0)
Location: fs/proc/inode.c:474
Inline: False
```
**Symbols:**

```
ffffffff812c96a0-ffffffff812c977d: proc_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff812edf20)
Location: fs/proc/inode.c:475
Inline: False
```
**Symbols:**

```
ffffffff812edf20-ffffffff812ee003: proc_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/inode.c (0)
Location: fs/proc/inode.c:492
Inline: False
```
**Symbols:**

```
ffffffff8131b05b-ffffffff8131b087: proc_fill_super.cold.8 (STB_LOCAL)
ffffffff8131af90-ffffffff8131b05b: proc_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/inode.c (0)
Location: fs/proc/inode.c:492
Inline: False
```
**Symbols:**

```
ffffffff813320e5-ffffffff81332111: proc_fill_super.cold.9 (STB_LOCAL)
ffffffff81332010-ffffffff813320e5: proc_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
ffffffff8135a1a0-ffffffff8135a2c1: proc_fill_super (STB_LOCAL)
ffffffff8135a3a4-ffffffff8135a3d0: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
ffffffff813723d0-ffffffff813724f1: proc_fill_super (STB_LOCAL)
ffffffff813725d4-ffffffff81372600: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:162
Inline: False
```
**Symbols:**

```
ffffffff813ba640-ffffffff813ba7e9: proc_fill_super (STB_LOCAL)
ffffffff813ba8c2-ffffffff813ba8ee: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:162
Inline: False
```
**Symbols:**

```
ffffffff813cc140-ffffffff813cc2ec: proc_fill_super (STB_LOCAL)
ffffffff81bebc91-ffffffff81bebcbd: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:162
Inline: False
```
**Symbols:**

```
ffffffff813d3100-ffffffff813d32a8: proc_fill_super (STB_LOCAL)
ffffffff81bddca0-ffffffff81bddccc: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:162
Inline: False
```
**Symbols:**

```
ffffffff81424650-ffffffff814247f8: proc_fill_super (STB_LOCAL)
ffffffff81cc80a2-ffffffff81cc80ce: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:162
Inline: False
```
**Symbols:**

```
ffffffff8149d270-ffffffff8149d410: proc_fill_super (STB_LOCAL)
ffffffff81e7ac52-ffffffff81e7ac76: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff81531d30)
Location: fs/proc/root.c:159
Inline: False
```
**Symbols:**

```
ffffffff81531d30-ffffffff81531ef1: proc_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff81569f00)
Location: fs/proc/root.c:159
Inline: False
```
**Symbols:**

```
ffffffff81569f00-ffffffff8156a0c1: proc_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff815a2520)
Location: fs/proc/root.c:159
Inline: False
```
**Symbols:**

```
ffffffff815a2520-ffffffff815a2716: proc_fill_super (STB_LOCAL)
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
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffff80001043c648)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
ffff80001043c648-ffff80001043c784: proc_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (c06026ac)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
c06026ac-c06027d8: proc_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (c0000000005503a0)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
c0000000005503a0-c000000000550504: proc_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffe0002d4982)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
ffffffe0002d4982-ffffffe0002d4a76: proc_fill_super (STB_LOCAL)
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
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
ffffffff8136a9b0-ffffffff8136aad1: proc_fill_super (STB_LOCAL)
ffffffff8136abb4-ffffffff8136abe0: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
ffffffff8135b440-ffffffff8135b561: proc_fill_super (STB_LOCAL)
ffffffff8135b644-ffffffff8135b670: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
ffffffff81368480-ffffffff813685a1: proc_fill_super (STB_LOCAL)
ffffffff81368684-ffffffff813686b0: proc_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int proc_fill_super(struct super_block *s, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/root.c (0)
Location: fs/proc/root.c:98
Inline: False
```
**Symbols:**

```
ffffffff8137bad0-ffffffff8137bbf1: proc_fill_super (STB_LOCAL)
ffffffff8137bcd4-ffffffff8137bd00: proc_fill_super.cold (STB_LOCAL)
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
<b>Param added. </b>
<code>int silent</code>
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
