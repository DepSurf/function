# Function: <code>squashfs_fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff81324030)
Location: fs/squashfs/super.c:79
Inline: False
```
**Symbols:**

```
ffffffff81324030-ffffffff813247f3: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff81339ec0)
Location: fs/squashfs/super.c:79
Inline: False
```
**Symbols:**

```
ffffffff81339ec0-ffffffff8133a677: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff8134eb90)
Location: fs/squashfs/super.c:79
Inline: False
```
**Symbols:**

```
ffffffff8134eb90-ffffffff8134f378: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff81373240)
Location: fs/squashfs/super.c:79
Inline: False
```
**Symbols:**

```
ffffffff81373240-ffffffff81373a28: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:79
Inline: False
```
**Symbols:**

```
ffffffff813a1b90-ffffffff813a22d6: squashfs_fill_super (STB_LOCAL)
ffffffff813a22d6-ffffffff813a2456: squashfs_fill_super.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:79
Inline: False
```
**Symbols:**

```
ffffffff813ba950-ffffffff813bb096: squashfs_fill_super (STB_LOCAL)
ffffffff813bb0b4-ffffffff813bb234: squashfs_fill_super.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:66
Inline: False
```
**Symbols:**

```
ffffffff813e5210-ffffffff813e5920: squashfs_fill_super (STB_LOCAL)
ffffffff813e5934-ffffffff813e5ae5: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffff813ff290-ffffffff813ffae1: squashfs_fill_super (STB_LOCAL)
ffffffff813ffb04-ffffffff813ffb36: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffff8144cc10-ffffffff8144d4c5: squashfs_fill_super (STB_LOCAL)
ffffffff8144d4c5-ffffffff8144d4f7: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffff81469270-ffffffff81469b33: squashfs_fill_super (STB_LOCAL)
ffffffff81bed561-ffffffff81bed593: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffff8146e970-ffffffff8146f233: squashfs_fill_super (STB_LOCAL)
ffffffff81bdf643-ffffffff81bdf675: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:115
Inline: False
```
**Symbols:**

```
ffffffff814c5350-ffffffff814c5c22: squashfs_fill_super (STB_LOCAL)
ffffffff81ccf153-ffffffff81ccf185: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:135
Inline: False
```
**Symbols:**

```
ffffffff815501d0-ffffffff81550b71: squashfs_fill_super (STB_LOCAL)
ffffffff81e821db-ffffffff81e8220e: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff815f0f20)
Location: fs/squashfs/super.c:180
Inline: False
```
**Symbols:**

```
ffffffff815f0f20-ffffffff815f1849: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff81628f80)
Location: fs/squashfs/super.c:180
Inline: False
```
**Symbols:**

```
ffffffff81628f80-ffffffff81629938: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff816621a0)
Location: fs/squashfs/super.c:180
Inline: False
```
**Symbols:**

```
ffffffff816621a0-ffffffff81662b87: squashfs_fill_super (STB_LOCAL)
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
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffff8000104dd350)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffff8000104dd350-ffff8000104ddb38: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (c069ee18)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
c069ee18-c069f748: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (c000000000618d30)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
c000000000618d30-c0000000006196d0: squashfs_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffe000351dfc)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffe000351dfc-ffffffe0003525fc: squashfs_fill_super (STB_LOCAL)
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
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffff813f7870-ffffffff813f80c1: squashfs_fill_super (STB_LOCAL)
ffffffff813f80e4-ffffffff813f8116: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffff813e82f0-ffffffff813e8b41: squashfs_fill_super (STB_LOCAL)
ffffffff813e8b64-ffffffff813e8b96: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffff813f4bf0-ffffffff813f5441: squashfs_fill_super (STB_LOCAL)
ffffffff813f5464-ffffffff813f5496: squashfs_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int squashfs_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/super.c (0)
Location: fs/squashfs/super.c:68
Inline: False
```
**Symbols:**

```
ffffffff8140a820-ffffffff8140b071: squashfs_fill_super (STB_LOCAL)
ffffffff8140b094-ffffffff8140b0c6: squashfs_fill_super.cold (STB_LOCAL)
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
