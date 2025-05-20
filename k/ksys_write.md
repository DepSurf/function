# Function: <code>ksys_write</code>

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
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129af40)
Location: fs/read_write.c:617
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff8129af40-ffffffff8129aff4: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812afe40)
Location: fs/read_write.c:617
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff812afe40-ffffffff812afef4: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cc7a0)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff812cc7a0-ffffffff812cc87e: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812de1c0)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff812de1c0-ffffffff812de29e: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81314fa0)
Location: fs/read_write.c:654
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff81314fa0-ffffffff8131507e: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81320320)
Location: fs/read_write.c:649
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff81320320-ffffffff813203fe: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81326450)
Location: fs/read_write.c:647
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff81326450-ffffffff8132652e: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813739f0)
Location: fs/read_write.c:638
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff813739f0-ffffffff81373ace: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f2780)
Location: fs/read_write.c:633
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff813f2780-ffffffff813f2876: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147b380)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff8147b380-ffffffff8147b476: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814aff10)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff814aff10-ffffffff814b0006: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e16d0)
Location: fs/read_write.c:632
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff814e16d0-ffffffff814e17c6: ksys_write (STB_GLOBAL)
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
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010384448)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__arm64_sys_write
```
**Symbols:**

```
ffff800010384448-ffff800010384548: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056d214)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__se_sys_write
```
**Symbols:**

```
c056d214-c056d310: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047a4f0)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__se_sys_write
```
**Symbols:**

```
c00000000047a4f0-c00000000047a62c: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000257554)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__se_sys_write
```
**Symbols:**

```
ffffffe000257554-ffffffe000257616: ksys_write (STB_GLOBAL)
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
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d67a0)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff812d67a0-ffffffff812d687e: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c7420)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff812c7420-ffffffff812c74fe: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d45b0)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff812d45b0-ffffffff812d468e: ksys_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ksys_write(unsigned int fd, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e5410)
Location: fs/read_write.c:626
Inline: False
Direct callers:
  - init/initramfs.c:xwrite
  - fs/read_write.c:__ia32_sys_write
  - fs/read_write.c:__x64_sys_write
```
**Symbols:**

```
ffffffff812e5410-ffffffff812e54ee: ksys_write (STB_GLOBAL)
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
