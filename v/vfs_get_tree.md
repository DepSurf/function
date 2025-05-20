# Function: <code>vfs_get_tree</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1430
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812cff3b-ffffffff812cff64: vfs_get_tree.cold (STB_LOCAL)
ffffffff812cdbf0-ffffffff812cdcc7: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812e1b4b-ffffffff812e1b61: vfs_get_tree.cold (STB_LOCAL)
ffffffff812df630-ffffffff812df6e1: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81318e5b-ffffffff81318e71: vfs_get_tree.cold (STB_LOCAL)
ffffffff81316400-ffffffff813164b1: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1485
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81bea527-ffffffff81bea53d: vfs_get_tree.cold (STB_LOCAL)
ffffffff81321920-ffffffff813219d1: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1487
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81bdc563-ffffffff81bdc579: vfs_get_tree.cold (STB_LOCAL)
ffffffff813279b0-ffffffff81327a61: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1487
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81cc385b-ffffffff81cc3871: vfs_get_tree.cold (STB_LOCAL)
ffffffff81374f80-ffffffff81375031: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1486
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81e75fc0-ffffffff81e75fd5: vfs_get_tree.cold (STB_LOCAL)
ffffffff813f4220-ffffffff813f42e9: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147d2c0)
Location: fs/super.c:1491
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8147d2c0-ffffffff8147d39e: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b2080)
Location: fs/super.c:1508
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff814b2080-ffffffff814b215e: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e3e00)
Location: fs/super.c:1768
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:vfs_cmd_create
```
**Symbols:**

```
ffffffff814e3e00-ffffffff814e3ef5: vfs_get_tree (STB_GLOBAL)
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
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010386038)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__arm64_sys_fsconfig
```
**Symbols:**

```
ffff800010386038-ffff800010386128: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056ef64)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c056ef64-c056f078: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047c510)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c00000000047c510-c00000000047c664: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000258b66)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
ffffffe000258b66-ffffffe000258c2c: vfs_get_tree (STB_GLOBAL)
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
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812da12b-ffffffff812da141: vfs_get_tree.cold (STB_LOCAL)
ffffffff812d7c10-ffffffff812d7cc1: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812cadab-ffffffff812cadc1: vfs_get_tree.cold (STB_LOCAL)
ffffffff812c8890-ffffffff812c8941: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812d7f3b-ffffffff812d7f51: vfs_get_tree.cold (STB_LOCAL)
ffffffff812d5a20-ffffffff812d5ad1: vfs_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfs_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1536
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812e8d93-ffffffff812e8da9: vfs_get_tree.cold (STB_LOCAL)
ffffffff812e6a30-ffffffff812e6ae1: vfs_get_tree (STB_GLOBAL)
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
