# Function: <code>__fdget_pos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122abe0)
Location: fs/file.c:772
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_lseek
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_readv
  - fs/read_write.c:SyS_writev
  - fs/read_write.c:compat_SyS_readv
  - fs/read_write.c:compat_SyS_writev
```
**Symbols:**

```
ffffffff8122abe0-ffffffff8122ac27: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81253320)
Location: fs/file.c:773
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_old_readdir
```
**Symbols:**

```
ffffffff81253320-ffffffff81253367: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81266570)
Location: fs/file.c:773
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_old_readdir
```
**Symbols:**

```
ffffffff81266570-ffffffff812665b7: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273d50)
Location: fs/file.c:759
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
  - fs/readdir.c:compat_SyS_getdents
  - fs/readdir.c:compat_SyS_old_readdir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
**Symbols:**

```
ffffffff81273d50-ffffffff81273d97: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296620)
Location: fs/file.c:762
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
  - fs/readdir.c:compat_SyS_getdents
  - fs/readdir.c:compat_SyS_old_readdir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
**Symbols:**

```
ffffffff81296620-ffffffff81296667: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc9e0)
Location: fs/file.c:758
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff812bc9e0-ffffffff812bca29: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1ca0)
Location: fs/file.c:788
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff812d1ca0-ffffffff812d1ce9: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eecd0)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff812eecd0-ffffffff812eed19: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300790)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff81300790-ffffffff813007d9: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813399b0)
Location: fs/file.c:819
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff813399b0-ffffffff813399f9: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813456e0)
Location: fs/file.c:955
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff813456e0-ffffffff81345729: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134ba80)
Location: fs/file.c:967
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff8134ba80-ffffffff8134bac9: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813998c0)
Location: fs/file.c:1027
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x64_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x64_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff813998c0-ffffffff81399909: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c290)
Location: fs/file.c:1029
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff8141c290-ffffffff8141c2f1: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a8370)
Location: fs/file.c:1039
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff814a8370-ffffffff814a83d1: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd350)
Location: fs/file.c:1056
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff814dd350-ffffffff814dd3cb: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150fd80)
Location: fs/file.c:1185
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff8150fd80-ffffffff8150fef0: __fdget_pos (STB_GLOBAL)
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
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b25b0)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__arm64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:__arm64_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__arm64_sys_getdents
```
**Symbols:**

```
ffff8000103b25b0-ffff8000103b2620: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c05918f0)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__se_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
```
**Symbols:**

```
c05918f0-c059194c: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae430)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__se_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__se_compat_sys_getdents
  - fs/readdir.c:__se_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:__se_sys_old_readdir
```
**Symbols:**

```
c0000000004ae430-c0000000004ae4c8: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002765fc)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
```
**Symbols:**

```
ffffffe0002765fc-ffffffe00027665e: __fdget_pos (STB_GLOBAL)
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
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8d70)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff812f8d70-ffffffff812f8db9: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9990)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff812e9990-ffffffff812e99d9: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6b80)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff812f6b80-ffffffff812f6bc9: __fdget_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307dd0)
Location: fs/file.c:794
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
**Symbols:**

```
ffffffff81307dd0-ffffffff81307e19: __fdget_pos (STB_GLOBAL)
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
