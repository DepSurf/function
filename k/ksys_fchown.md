# Function: <code>ksys_fchown</code>

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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812968f0)
Location: fs/open.c:706
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff812968f0-ffffffff8129699d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab6e0)
Location: fs/open.c:695
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff812ab6e0-ffffffff812ab78d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7ee0)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff812c7ee0-ffffffff812c7f8d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d98f0)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff812d98f0-ffffffff812d999d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130f6b0)
Location: fs/open.c:744
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff8130f6b0-ffffffff8130f75d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131b960)
Location: fs/open.c:747
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff8131b960-ffffffff8131ba0d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81321ab0)
Location: fs/open.c:755
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff81321ab0-ffffffff81321b5d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136ef90)
Location: fs/open.c:752
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff8136ef90-ffffffff8136f03d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ed900)
Location: fs/open.c:777
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff813ed900-ffffffff813ed9c9: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81476020)
Location: fs/open.c:809
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff81476020-ffffffff814760e9: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814aa940)
Location: fs/open.c:841
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff814aa940-ffffffff814aaa0c: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814dbde0)
Location: fs/open.c:861
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff814dbde0-ffffffff814dbeac: ksys_fchown (STB_GLOBAL)
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037ec20)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__arm64_sys_fchown16
  - fs/open.c:__arm64_sys_fchown
```
**Symbols:**

```
ffff80001037ec20-ffff80001037ecf0: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569568)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__se_sys_fchown16
  - fs/open.c:__se_sys_fchown
```
**Symbols:**

```
c0569568-c0569624: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474940)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_fchown
```
**Symbols:**

```
c000000000474940-c000000000474a68: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254884)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_fchown
```
**Symbols:**

```
ffffffe000254884-ffffffe000254928: ksys_fchown (STB_GLOBAL)
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1ed0)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff812d1ed0-ffffffff812d1f7d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2b50)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff812c2b50-ffffffff812c2bfd: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cfce0)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff812cfce0-ffffffff812cfd8d: ksys_fchown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e0af0)
Location: fs/open.c:715
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - kernel/uid16.c:__ia32_sys_fchown16
  - kernel/uid16.c:__x64_sys_fchown16
  - fs/open.c:__ia32_sys_fchown
  - fs/open.c:__x64_sys_fchown
```
**Symbols:**

```
ffffffff812e0af0-ffffffff812e0b9d: ksys_fchown (STB_GLOBAL)
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
