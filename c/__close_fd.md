# Function: <code>__close_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a9d0)
Location: fs/file.c:634
Inline: False
Direct callers:
  - fs/open.c:SyS_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff8122a9d0-ffffffff8122aa91: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81253130)
Location: fs/file.c:635
Inline: False
Direct callers:
  - fs/open.c:SyS_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81253130-ffffffff812531e0: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81266380)
Location: fs/file.c:635
Inline: False
Direct callers:
  - fs/open.c:SyS_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81266380-ffffffff8126642d: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273b60)
Location: fs/file.c:621
Inline: False
Direct callers:
  - fs/open.c:SyS_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81273b60-ffffffff81273c0d: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296440)
Location: fs/file.c:625
Inline: False
Direct callers:
  - fs/open.c:SyS_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81296440-ffffffff812964dd: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc1b0)
Location: fs/file.c:620
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812bc1b0-ffffffff812bc24f: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d13a0)
Location: fs/file.c:620
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812d13a0-ffffffff812d143f: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ee3c0)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812ee3c0-ffffffff812ee45f: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ffe80)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812ffe80-ffffffff812fff1f: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338fc0)
Location: fs/file.c:626
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81338fc0-ffffffff8133905f: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b1190)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__arm64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffff8000103b1190-ffff8000103b12c0: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590d4c)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__se_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
c0590d4c-c0590e38: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ad2d0)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__se_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
c0000000004ad2d0-c0000000004ad440: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000275970)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__se_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffe000275970-ffffffe000275aaa: __close_fd (STB_GLOBAL)
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
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8460)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812f8460-ffffffff812f84ff: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9080)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812e9080-ffffffff812e911f: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6270)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812f6270-ffffffff812f630f: __close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __close_fd(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81306d30)
Location: fs/file.c:621
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_copy
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81306d30-ffffffff81306dcf: __close_fd (STB_GLOBAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
