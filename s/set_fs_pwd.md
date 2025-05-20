# Function: <code>set_fs_pwd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812413c0)
Location: fs/fs_struct.c:32
Inline: False
Direct callers:
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_fchdir
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mntns_install
```
**Symbols:**

```
ffffffff812413c0-ffffffff8124145f: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812696f0)
Location: fs/fs_struct.c:32
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812696f0-ffffffff8126978f: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8127c6a0)
Location: fs/fs_struct.c:32
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff8127c6a0-ffffffff8127c73f: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81289d70)
Location: fs/fs_struct.c:33
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81289d70-ffffffff81289e10: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812ac8b0)
Location: fs/fs_struct.c:33
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812ac8b0-ffffffff812ac950: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812d4490)
Location: fs/fs_struct.c:33
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812d4490-ffffffff812d452f: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812e9860)
Location: fs/fs_struct.c:33
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812e9860-ffffffff812e98ff: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81308220)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81308220-ffffffff813082bf: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8131b2c0)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff8131b2c0-ffffffff8131b35f: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81354f70)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:init_mount_tree
```
**Symbols:**

```
ffffffff81354f70-ffffffff81355010: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81361890)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/usermode_driver.c:umd_setup
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:init_mount_tree
  - fs/init.c:init_chdir
```
**Symbols:**

```
ffffffff81361890-ffffffff81361930: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81368370)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/usermode_driver.c:umd_setup
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chdir
```
**Symbols:**

```
ffffffff81368370-ffffffff81368410: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813b7070)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/usermode_driver.c:umd_setup
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chdir
```
**Symbols:**

```
ffffffff813b7070-ffffffff813b7110: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8143c6c0)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/usermode_driver.c:umd_setup
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chdir
```
**Symbols:**

```
ffffffff8143c6c0-ffffffff8143c77b: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff814cadd0)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/usermode_driver.c:umd_setup
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chdir
```
**Symbols:**

```
ffffffff814cadd0-ffffffff814cae8b: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81501010)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/usermode_driver.c:umd_setup
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chdir
```
**Symbols:**

```
ffffffff81501010-ffffffff815010cb: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81535c30)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chdir
```
**Symbols:**

```
ffffffff81535c30-ffffffff81535ceb: set_fs_pwd (STB_GLOBAL)
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
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffff8000103d26a0)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__arm64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffff8000103d26a0-ffff8000103d2798: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c05ad334)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
c05ad334-c05ad400: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c0000000004d51d0)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
c0000000004d51d0-c0000000004d52e8: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffe00028d9bc)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffe00028d9bc-ffffffe00028da76: set_fs_pwd (STB_GLOBAL)
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
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813138a0)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff813138a0-ffffffff8131393f: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813044b0)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff813044b0-ffffffff8130454f: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81311690)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81311690-ffffffff8131172f: set_fs_pwd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_fs_pwd(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81322ee0)
Location: fs/fs_struct.c:34
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81322ee0-ffffffff81322f7e: set_fs_pwd (STB_GLOBAL)
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
