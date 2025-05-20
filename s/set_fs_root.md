# Function: <code>set_fs_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81241320)
Location: fs/fs_struct.c:13
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mntns_install
```
**Symbols:**

```
ffffffff81241320-ffffffff812413bf: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81269650)
Location: fs/fs_struct.c:13
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81269650-ffffffff812696ef: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8127c600)
Location: fs/fs_struct.c:13
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff8127c600-ffffffff8127c69f: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81289cd0)
Location: fs/fs_struct.c:14
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81289cd0-ffffffff81289d70: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812ac810)
Location: fs/fs_struct.c:14
Inline: False
Direct callers:
  - fs/open.c:SyS_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812ac810-ffffffff812ac8b0: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812d43f0)
Location: fs/fs_struct.c:14
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812d43f0-ffffffff812d448f: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812e97c0)
Location: fs/fs_struct.c:14
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812e97c0-ffffffff812e985f: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81308180)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81308180-ffffffff8130821f: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8131b220)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff8131b220-ffffffff8131b2bf: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81354ed0)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:init_mount_tree
```
**Symbols:**

```
ffffffff81354ed0-ffffffff81354f70: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813617f0)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:init_mount_tree
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff813617f0-ffffffff81361890: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813682d0)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff813682d0-ffffffff81368370: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813b6fd0)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff813b6fd0-ffffffff813b7070: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8143c600)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff8143c600-ffffffff8143c6bb: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff814cad00)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff814cad00-ffffffff814cadbb: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81500f40)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff81500f40-ffffffff81500ffb: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81535b60)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
  - fs/init.c:init_chroot
```
**Symbols:**

```
ffffffff81535b60-ffffffff81535c1b: set_fs_root (STB_GLOBAL)
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
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffff8000103d25a8)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffff8000103d25a8-ffff8000103d26a0: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c05ad268)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
c05ad268-c05ad334: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c0000000004d50b0)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
c0000000004d50b0-c0000000004d51c8: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffe00028d902)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffe00028d902-ffffffe00028d9bc: set_fs_root (STB_GLOBAL)
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
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81313800)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81313800-ffffffff8131389f: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81304410)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81304410-ffffffff813044af: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813115f0)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff813115f0-ffffffff8131168f: set_fs_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct *fs, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81322e40)
Location: fs/fs_struct.c:15
Inline: False
Direct callers:
  - fs/open.c:ksys_chroot
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81322e40-ffffffff81322ede: set_fs_root (STB_GLOBAL)
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
