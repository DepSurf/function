# Function: <code>ksys_ioctl</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812b0420)
Location: fs/ioctl.c:692
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff812b0420-ffffffff812b04b0: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812c5580)
Location: fs/ioctl.c:704
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff812c5580-ffffffff812c5610: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e2000)
Location: fs/ioctl.c:704
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff812e2000-ffffffff812e2090: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812f3ad0)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff812f3ad0-ffffffff812f3b60: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132c190)
Location: fs/ioctl.c:739
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff8132c190-ffffffff8132c250: ksys_ioctl (STB_GLOBAL)
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffff80001039f090)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__arm64_sys_ioctl
```
**Symbols:**

```
ffff80001039f090-ffff80001039f144: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c0583f68)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__se_sys_ioctl
```
**Symbols:**

```
c0583f68-c0583ff8: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c0000000004996e0)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__se_sys_ioctl
```
**Symbols:**

```
c0000000004996e0-c0000000004997f0: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffe000269f6a)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__se_sys_ioctl
```
**Symbols:**

```
ffffffe000269f6a-ffffffe000269ff6: ksys_ioctl (STB_GLOBAL)
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812ec0b0)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff812ec0b0-ffffffff812ec140: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812dcce0)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff812dcce0-ffffffff812dcd70: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e9ec0)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff812e9ec0-ffffffff812e9f50: ksys_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812faeb0)
Location: fs/ioctl.c:705
Inline: False
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff812faeb0-ffffffff812faf40: ksys_ioctl (STB_GLOBAL)
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
