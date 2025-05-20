# Function: <code>do_mknodat</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ad270)
Location: fs/namei.c:3753
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff812ad270-ffffffff812ad487: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c2370)
Location: fs/namei.c:3742
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff812c2370-ffffffff812c2587: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812deb30)
Location: fs/namei.c:3741
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff812deb30-ffffffff812ded27: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0640)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff812f0640-ffffffff812f0837: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81327a98)
Location: fs/namei.c:3567
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff81327780-ffffffff813279ad: do_mknodat.part.0 (STB_LOCAL)
ffffffff81328a50-ffffffff81328ab1: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff813330d8)
Location: fs/namei.c:3569
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
Direct callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff81332d50-ffffffff81332f7d: do_mknodat.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81339168)
Location: fs/namei.c:3718
Inline: True
Inline callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
Direct callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff81338dc0-ffffffff8133900f: do_mknodat.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mknodat(int dfd, struct filename *name, umode_t mode, unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813865f0)
Location: fs/namei.c:3787
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff813865f0-ffffffff81386872: do_mknodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mknodat(int dfd, struct filename *name, umode_t mode, unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81407260)
Location: fs/namei.c:3881
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff81407260-ffffffff814074f2: do_mknodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mknodat(int dfd, struct filename *name, umode_t mode, unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81491640)
Location: fs/namei.c:3939
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff81491640-ffffffff814918fc: do_mknodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mknodat(int dfd, struct filename *name, umode_t mode, unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c5c10)
Location: fs/namei.c:4019
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff814c5c10-ffffffff814c5ec3: do_mknodat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mknodat(int dfd, struct filename *name, umode_t mode, unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f8500)
Location: fs/namei.c:4028
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff814f8500-ffffffff814f87ba: do_mknodat (STB_LOCAL)
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
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010399de0)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__arm64_sys_mknod
  - fs/namei.c:__arm64_sys_mknodat
```
**Symbols:**

```
ffff800010399de0-ffff80001039a018: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0580308)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__se_sys_mknod
  - fs/namei.c:__se_sys_mknodat
```
**Symbols:**

```
c0580308-c058053c: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000494870)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__se_sys_mknod
  - fs/namei.c:__se_sys_mknodat
```
**Symbols:**

```
c000000000494870-c000000000494b50: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002675aa)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__se_sys_mknod
  - fs/namei.c:__se_sys_mknodat
```
**Symbols:**

```
ffffffe0002675aa-ffffffe000267778: do_mknodat (STB_GLOBAL)
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
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e8c20)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff812e8c20-ffffffff812e8e17: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9860)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff812d9860-ffffffff812d9a57: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6a30)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff812e6a30-ffffffff812e6c27: do_mknodat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int do_mknodat(int dfd, const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f79b0)
Location: fs/namei.c:3736
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/initramfs.c:do_name
  - fs/namei.c:__ia32_sys_mknod
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:__ia32_sys_mknodat
  - fs/namei.c:__x64_sys_mknodat
```
**Symbols:**

```
ffffffff812f79b0-ffffffff812f7ba7: do_mknodat (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
