# Function: <code>ksys_fchmod</code>

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
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812964e0)
Location: fs/open.c:568
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff812964e0-ffffffff81296568: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab2d0)
Location: fs/open.c:557
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff812ab2d0-ffffffff812ab358: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7ad0)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff812c7ad0-ffffffff812c7b58: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d94e0)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff812d94e0-ffffffff812d9568: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130f2a0)
Location: fs/open.c:606
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff8130f2a0-ffffffff8130f328: ksys_fchmod (STB_GLOBAL)
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
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037e848)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__arm64_sys_fchmod
```
**Symbols:**

```
ffff80001037e848-ffff80001037e8e8: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569208)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_fchmod
```
**Symbols:**

```
c0569208-c056929c: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474420)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_fchmod
```
**Symbols:**

```
c000000000474420-c000000000474508: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254504)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__se_sys_fchmod
```
**Symbols:**

```
ffffffe000254504-ffffffe00025458e: ksys_fchmod (STB_GLOBAL)
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
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1ac0)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff812d1ac0-ffffffff812d1b48: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2740)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff812c2740-ffffffff812c27c8: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cf8d0)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff812cf8d0-ffffffff812cf958: ksys_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_fchmod(unsigned int fd, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e06e0)
Location: fs/open.c:577
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
**Symbols:**

```
ffffffff812e06e0-ffffffff812e0768: ksys_fchmod (STB_GLOBAL)
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
