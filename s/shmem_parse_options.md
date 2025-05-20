# Function: <code>shmem_parse_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shmem_parse_options(char *options, struct shmem_sb_info *sbinfo, bool remount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a69a0)
Location: mm/shmem.c:2757
Inline: False
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff811a69a0-ffffffff811a6d4e: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shmem_parse_options(char *options, struct shmem_sb_info *sbinfo, bool remount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811be5d0)
Location: mm/shmem.c:3390
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_remount_fs
```
**Symbols:**

```
ffffffff811be5d0-ffffffff811be9ae: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_parse_options(char *options, struct shmem_sb_info *sbinfo, bool remount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cedd0)
Location: mm/shmem.c:3307
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_remount_fs
```
**Symbols:**

```
ffffffff811cedd0-ffffffff811cf192: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_parse_options(char *options, struct shmem_sb_info *sbinfo, bool remount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d7b00)
Location: mm/shmem.c:3457
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_remount_fs
```
**Symbols:**

```
ffffffff811d7b00-ffffffff811d7edd: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_parse_options(char *options, struct shmem_sb_info *sbinfo, bool remount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ec980)
Location: mm/shmem.c:3482
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_remount_fs
```
**Symbols:**

```
ffffffff811ec980-ffffffff811ecd56: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int shmem_parse_options(char *options, struct shmem_sb_info *sbinfo, bool remount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3292
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_remount_fs
```
**Symbols:**

```
ffffffff8120df70-ffffffff8120e33f: shmem_parse_options (STB_LOCAL)
ffffffff812140b8-ffffffff812140f4: shmem_parse_options.cold.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int shmem_parse_options(char *options, struct shmem_sb_info *sbinfo, bool remount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3278
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_remount_fs
```
**Symbols:**

```
ffffffff81220b10-ffffffff81220edb: shmem_parse_options (STB_LOCAL)
ffffffff81226f8b-ffffffff81226fc7: shmem_parse_options.cold.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shmem_parse_options(char *options, struct shmem_sb_info *sbinfo, bool remount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3360
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_remount_fs
```
**Symbols:**

```
ffffffff812302b0-ffffffff8123067e: shmem_parse_options (STB_LOCAL)
ffffffff81236b0b-ffffffff81236b61: shmem_parse_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123e1a0)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
ffffffff8123e1a0-ffffffff8123e264: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126b4e0)
Location: mm/shmem.c:3457
Inline: False
```
**Symbols:**

```
ffffffff8126b4e0-ffffffff8126b5a4: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81275e80)
Location: mm/shmem.c:3534
Inline: False
```
**Symbols:**

```
ffffffff81275e80-ffffffff81275f44: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127b290)
Location: mm/shmem.c:3479
Inline: False
```
**Symbols:**

```
ffffffff8127b290-ffffffff8127b354: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812b9140)
Location: mm/shmem.c:3450
Inline: False
```
**Symbols:**

```
ffffffff812b9140-ffffffff812b9204: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81314fe0)
Location: mm/shmem.c:3457
Inline: False
```
**Symbols:**

```
ffffffff81314fe0-ffffffff813150bc: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81388eb0)
Location: mm/shmem.c:3571
Inline: False
```
**Symbols:**

```
ffffffff81388eb0-ffffffff81388f8c: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bb0e0)
Location: mm/shmem.c:3754
Inline: False
```
**Symbols:**

```
ffffffff813bb0e0-ffffffff813bb1bc: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e59e0)
Location: mm/shmem.c:4075
Inline: False
```
**Symbols:**

```
ffffffff813e59e0-ffffffff813e5abc: shmem_parse_options (STB_LOCAL)
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
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102cfd70)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
ffff8000102cfd70-ffff8000102cfe5c: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa03c)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
c04fa03c-c04fa11c: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038dbc0)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
c00000000038dbc0-c00000000038dd68: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ed4a2)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
ffffffe0001ed4a2-ffffffe0001ed56c: shmem_parse_options (STB_LOCAL)
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
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812367f0)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
ffffffff812367f0-ffffffff812368b4: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81229850)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
ffffffff81229850-ffffffff81229914: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81234590)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
ffffffff81234590-ffffffff81234654: shmem_parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_parse_options(struct fs_context *fc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812446f0)
Location: mm/shmem.c:3494
Inline: False
```
**Symbols:**

```
ffffffff812446f0-ffffffff812447b4: shmem_parse_options (STB_LOCAL)
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
<b>Param added. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>char *options</code>
</li>
<li>
<b>Param removed. </b>
<code>struct shmem_sb_info *sbinfo</code>
</li>
<li>
<b>Param removed. </b>
<code>bool remount</code>
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
