# Function: <code>fdput_pos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120c3b6)
Location: fs/read_write.c:269
Inline: True
Inline callers:
  - fs/read_write.c:compat_SyS_lseek
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_readv
  - fs/read_write.c:SyS_writev
  - fs/read_write.c:compat_SyS_readv
  - fs/read_write.c:compat_SyS_writev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233762)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
```
```
In fs/readdir.c (ffffffff81248633)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
```
In fs/compat.c (ffffffff81291383)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_old_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812462f2)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
```
```
In fs/readdir.c (ffffffff8125b663)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
```
In fs/compat.c (ffffffff812a6113)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_old_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251ad2)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
```
```
In fs/readdir.c (ffffffff812684d1)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/readdir.c:compat_SyS_getdents
  - fs/readdir.c:compat_SyS_old_readdir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273442)
Location: include/linux/file.h:71
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
```
```
In fs/readdir.c (ffffffff8128ad81)
Location: include/linux/file.h:71
Inline: True
Inline callers:
  - fs/readdir.c:compat_SyS_getdents
  - fs/readdir.c:compat_SyS_old_readdir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812995d6)
Location: include/linux/file.h:71
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff812b105b)
Location: include/linux/file.h:71
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ae456)
Location: include/linux/file.h:73
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff812c625b)
Location: include/linux/file.h:73
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cb0ec)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff812e2d00)
Location: include/linux/file.h:75
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dcb0c)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff812f4a70)
Location: include/linux/file.h:75
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813139cc)
Location: include/linux/file.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff8132d119)
Location: include/linux/file.h:77
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131ee61)
Location: include/linux/file.h:78
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff813388f9)
Location: include/linux/file.h:78
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81324891)
Location: include/linux/file.h:78
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff8133ef63)
Location: include/linux/file.h:78
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813724d1)
Location: include/linux/file.h:78
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff8138c8f3)
Location: include/linux/file.h:78
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f0615)
Location: include/linux/file.h:76
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff8140d1c9)
Location: include/linux/file.h:76
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814789c5)
Location: include/linux/file.h:76
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff81497c79)
Location: include/linux/file.h:76
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ad425)
Location: include/linux/file.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff814ccbe9)
Location: include/linux/file.h:77
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814deda5)
Location: include/linux/file.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff814ff809)
Location: include/linux/file.h:77
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010382548)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__arm64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffff80001039fbf8)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:__arm64_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__arm64_sys_getdents
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c508)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__se_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (c0584930)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478c8c)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__se_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (c000000000499e6c)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/readdir.c:__se_compat_sys_getdents
  - fs/readdir.c:__se_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:__se_sys_old_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256c0c)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffe00026a5de)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d50ec)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff812ed050)
Location: include/linux/file.h:75
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5d6c)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff812ddc80)
Location: include/linux/file.h:75
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2efc)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff812eae60)
Location: include/linux/file.h:75
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e3d5c)
Location: include/linux/file.h:75
Inline: True
Inline callers:
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffff812fbe50)
Location: include/linux/file.h:75
Inline: True
Inline callers:
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
</details>
</li>
</ul>

## Differences
