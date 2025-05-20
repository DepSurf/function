# Function: <code>replace_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122ace0)
Location: fs/file.c:861
Inline: False
Direct callers:
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff8122ace0-ffffffff8122ad7e: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81253430)
Location: fs/file.c:867
Inline: False
Direct callers:
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81253430-ffffffff812534d2: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81266680)
Location: fs/file.c:867
Inline: False
Direct callers:
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81266680-ffffffff81266722: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273e60)
Location: fs/file.c:853
Inline: False
Direct callers:
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81273e60-ffffffff81273f0f: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296730)
Location: fs/file.c:856
Inline: False
Direct callers:
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81296730-ffffffff812967df: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bcaf0)
Location: fs/file.c:852
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff812bcaf0-ffffffff812bcb94: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1db0)
Location: fs/file.c:882
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff812d1db0-ffffffff812d1e54: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eede0)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff812eede0-ffffffff812eee8b: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813008a0)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff813008a0-ffffffff8130094b: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339ac0)
Location: fs/file.c:913
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81339ac0-ffffffff81339b6b: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81345800)
Location: fs/file.c:1049
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - fs/file.c:__receive_fd
  - fs/coredump.c:umh_pipe_setup
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81345800-ffffffff813458bb: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134bba0)
Location: fs/file.c:1061
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - fs/file.c:receive_fd_replace
  - fs/coredump.c:umh_pipe_setup
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff8134bba0-ffffffff8134bc5b: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813999e0)
Location: fs/file.c:1121
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - fs/file.c:receive_fd_replace
  - fs/coredump.c:umh_pipe_setup
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff813999e0-ffffffff81399a9e: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c3f0)
Location: fs/file.c:1123
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - fs/file.c:receive_fd_replace
  - fs/coredump.c:umh_pipe_setup
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff8141c3f0-ffffffff8141c4d3: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a8510)
Location: fs/file.c:1133
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - fs/file.c:receive_fd_replace
  - fs/coredump.c:umh_pipe_setup
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff814a8510-ffffffff814a85f3: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd500)
Location: fs/file.c:1148
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - kernel/usermode_driver.c:umd_setup
  - fs/file.c:receive_fd_replace
  - fs/coredump.c:umh_pipe_setup
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff814dd500-ffffffff814dd5e3: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81510020)
Location: fs/file.c:1277
Inline: False
Direct callers:
  - fs/file.c:receive_fd_replace
  - fs/coredump.c:umh_pipe_setup
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81510020-ffffffff81510103: replace_fd (STB_GLOBAL)
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
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b27e8)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffff8000103b27e8-ffff8000103b28d0: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0591a88)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
c0591a88-c0591b38: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae6a0)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
c0000000004ae6a0-c0000000004ae7d8: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe00027679e)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffe00027679e-ffffffe000276868: replace_fd (STB_GLOBAL)
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
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8e80)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff812f8e80-ffffffff812f8f2b: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9aa0)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff812e9aa0-ffffffff812e9b4b: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6c90)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff812f6c90-ffffffff812f6d3b: replace_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307f00)
Location: fs/file.c:888
Inline: False
Direct callers:
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - kernel/umh.c:umh_pipe_setup
  - fs/coredump.c:umh_pipe_setup
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff81307f00-ffffffff81307faa: replace_fd (STB_GLOBAL)
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
