# Function: <code>vfs_parse_fs_param</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130a780)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8130a780-ffffffff8130a939: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131d740)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8131d740-ffffffff8131d8f9: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (ffffffff81357180)
Location: fs/fs_context.c:98
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81357180-ffffffff81357266: vfs_parse_fs_param.part.0 (STB_LOCAL)
ffffffff81357270-ffffffff81357320: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (ffffffff81363b30)
Location: fs/fs_context.c:98
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81363b30-ffffffff81363c16: vfs_parse_fs_param.part.0 (STB_LOCAL)
ffffffff81363c20-ffffffff81363cd0: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136a5d0)
Location: fs/fs_context.c:98
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8136a5d0-ffffffff8136a749: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9300)
Location: fs/fs_context.c:127
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff813b9300-ffffffff813b9407: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143eb00)
Location: fs/fs_context.c:127
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8143eb00-ffffffff8143ec12: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814cd730)
Location: fs/fs_context.c:127
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff814cd730-ffffffff814cd842: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81503900)
Location: fs/fs_context.c:127
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81503900-ffffffff81503a12: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81538550)
Location: fs/fs_context.c:127
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81538550-ffffffff81538662: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d54b0)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__arm64_sys_fsconfig
```
**Symbols:**

```
ffff8000103d54b0-ffff8000103d56a0: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05af718)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c05af718-c05af8e8: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d89c0)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c0000000004d89c0-c0000000004d8eb8: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028f8c4)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
ffffffe00028f8c4-ffffffe00028fa50: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81315d20)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81315d20-ffffffff81315ed9: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306910)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81306910-ffffffff81306ac9: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81313b10)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81313b10-ffffffff81313cc9: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_parse_fs_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81325360)
Location: fs/fs_context.c:126
Inline: True
Direct callers:
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81325360-ffffffff81325519: vfs_parse_fs_param (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
