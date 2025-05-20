# Function: <code>smk_fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81363330)
Location: security/smack/smackfs.c:2903
Inline: False
```
**Symbols:**

```
ffffffff81363330-ffffffff8136336d: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81399500)
Location: security/smack/smackfs.c:2853
Inline: False
```
**Symbols:**

```
ffffffff81399500-ffffffff8139953d: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813b00e0)
Location: security/smack/smackfs.c:2848
Inline: False
```
**Symbols:**

```
ffffffff813b00e0-ffffffff813b011d: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813c6cb0)
Location: security/smack/smackfs.c:2853
Inline: False
```
**Symbols:**

```
ffffffff813c6cb0-ffffffff813c6ced: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813ecfa0)
Location: security/smack/smackfs.c:2853
Inline: False
```
**Symbols:**

```
ffffffff813ecfa0-ffffffff813ecfdd: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2853
Inline: False
```
**Symbols:**

```
ffffffff8141dd60-ffffffff8141dd8a: smk_fill_super (STB_LOCAL)
ffffffff814208eb-ffffffff81420905: smk_fill_super.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2853
Inline: False
```
**Symbols:**

```
ffffffff8143a380-ffffffff8143a3aa: smk_fill_super (STB_LOCAL)
ffffffff8143cf3b-ffffffff8143cf55: smk_fill_super.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
ffffffff81467fd0-ffffffff81467ffe: smk_fill_super (STB_LOCAL)
ffffffff8146aad8-ffffffff8146aaf2: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
ffffffff81481db0-ffffffff81481dde: smk_fill_super (STB_LOCAL)
ffffffff814848b8-ffffffff814848d2: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2854
Inline: False
```
**Symbols:**

```
ffffffff814d7e50-ffffffff814d7e80: smk_fill_super (STB_LOCAL)
ffffffff814daa08-ffffffff814daa22: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2876
Inline: False
```
**Symbols:**

```
ffffffff814f53c0-ffffffff814f53f0: smk_fill_super (STB_LOCAL)
ffffffff81bf122b-ffffffff81bf1245: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2878
Inline: False
```
**Symbols:**

```
ffffffff814fc1d0-ffffffff814fc200: smk_fill_super (STB_LOCAL)
ffffffff81be33b4-ffffffff81be33ce: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2879
Inline: False
```
**Symbols:**

```
ffffffff81556e50-ffffffff81556e80: smk_fill_super (STB_LOCAL)
ffffffff81cd54ea-ffffffff81cd5504: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2878
Inline: False
```
**Symbols:**

```
ffffffff815f10d0-ffffffff815f1107: smk_fill_super (STB_LOCAL)
ffffffff81e882fb-ffffffff81e88315: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816a1600)
Location: security/smack/smackfs.c:2878
Inline: False
```
**Symbols:**

```
ffffffff816a1600-ffffffff816a165a: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816d9f50)
Location: security/smack/smackfs.c:2889
Inline: False
```
**Symbols:**

```
ffffffff816d9f50-ffffffff816d9faa: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff817169f0)
Location: security/smack/smackfs.c:2901
Inline: False
```
**Symbols:**

```
ffffffff817169f0-ffffffff81716a4a: smk_fill_super (STB_LOCAL)
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
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffff800010573a08)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
ffff800010573a08-ffff800010573a6c: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0726b58)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
c0726b58-c0726bac: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0000000006dbf10)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
c0000000006dbf10-c0000000006dbf94: smk_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffe0003c6d0e)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
ffffffe0003c6d0e-ffffffe0003c6d6a: smk_fill_super (STB_LOCAL)
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
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
ffffffff8147a390-ffffffff8147a3be: smk_fill_super (STB_LOCAL)
ffffffff8147ce98-ffffffff8147ceb2: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
ffffffff8146adb0-ffffffff8146adde: smk_fill_super (STB_LOCAL)
ffffffff8146d8b8-ffffffff8146d8d2: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
ffffffff81476430-ffffffff8147645e: smk_fill_super (STB_LOCAL)
ffffffff81478f38-ffffffff81478f52: smk_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int smk_fill_super(struct super_block *sb, struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (0)
Location: security/smack/smackfs.c:2826
Inline: False
```
**Symbols:**

```
ffffffff8148dc70-ffffffff8148dc9e: smk_fill_super (STB_LOCAL)
ffffffff814909e8-ffffffff81490a02: smk_fill_super.cold (STB_LOCAL)
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
