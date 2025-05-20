# Function: <code>mount_capable</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf830)
Location: fs/super.c:479
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812cf830-ffffffff812cf85f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e12e0)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812e12e0-ffffffff812e130f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318640)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81318640-ffffffff8131866f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323a60)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81323a60-ffffffff81323a8f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81329b20)
Location: fs/super.c:486
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81329b20-ffffffff81329b4f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81377150)
Location: fs/super.c:486
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81377150-ffffffff8137717f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f63d0)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff813f63d0-ffffffff813f640f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147f4a0)
Location: fs/super.c:528
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8147f4a0-ffffffff8147f4df: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b40f0)
Location: fs/super.c:535
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff814b40f0-ffffffff814b412f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e6840)
Location: fs/super.c:689
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:vfs_cmd_create
```
**Symbols:**

```
ffffffff814e6840-ffffffff814e687f: mount_capable (STB_GLOBAL)
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
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388460)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__arm64_sys_fsconfig
```
**Symbols:**

```
ffff800010388460-ffff8000103884b8: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0570c64)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c0570c64-c0570ca4: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047f180)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c00000000047f180-c00000000047f1f0: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025aaec)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
ffffffe00025aaec-ffffffe00025ab34: mount_capable (STB_GLOBAL)
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
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d98c0)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812d98c0-ffffffff812d98ef: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ca540)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812ca540-ffffffff812ca56f: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d76d0)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812d76d0-ffffffff812d76ff: mount_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool mount_capable(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8520)
Location: fs/super.c:485
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812e8520-ffffffff812e854f: mount_capable (STB_GLOBAL)
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
