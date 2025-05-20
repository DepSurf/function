# Function: <code>fdget_pos</code>

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
In fs/read_write.c (ffffffff8120c398)
Location: fs/read_write.c:264
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
In fs/read_write.c (ffffffff8123371e)
Location: include/linux/file.h:65
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
In fs/readdir.c (ffffffff812485ea)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
```
In fs/compat.c (ffffffff8129133a)
Location: include/linux/file.h:65
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
In fs/read_write.c (ffffffff812462ae)
Location: include/linux/file.h:65
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
In fs/readdir.c (ffffffff8125b61a)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
```
In fs/compat.c (ffffffff812a60ca)
Location: include/linux/file.h:65
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
In fs/read_write.c (ffffffff81251a8e)
Location: include/linux/file.h:65
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
In fs/readdir.c (ffffffff8126847f)
Location: include/linux/file.h:65
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
In fs/read_write.c (ffffffff812733fe)
Location: include/linux/file.h:66
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
In fs/readdir.c (ffffffff8128ad2f)
Location: include/linux/file.h:66
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
In fs/read_write.c (ffffffff81299595)
Location: include/linux/file.h:66
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
In fs/readdir.c (ffffffff812b1006)
Location: include/linux/file.h:66
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
In fs/read_write.c (ffffffff812ae415)
Location: include/linux/file.h:68
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
In fs/readdir.c (ffffffff812c6206)
Location: include/linux/file.h:68
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
In fs/read_write.c (ffffffff812cb0ae)
Location: include/linux/file.h:70
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
In fs/readdir.c (ffffffff812e2cb6)
Location: include/linux/file.h:70
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
In fs/read_write.c (ffffffff812dcace)
Location: include/linux/file.h:70
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
In fs/readdir.c (ffffffff812f4a26)
Location: include/linux/file.h:70
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
In fs/read_write.c (ffffffff8131398e)
Location: include/linux/file.h:72
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
In fs/readdir.c (ffffffff8132d0e7)
Location: include/linux/file.h:72
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
In fs/read_write.c (ffffffff8131ee0e)
Location: include/linux/file.h:73
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
In fs/readdir.c (ffffffff813388c7)
Location: include/linux/file.h:73
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
In fs/read_write.c (ffffffff8132483e)
Location: include/linux/file.h:73
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
In fs/readdir.c (ffffffff8133ef30)
Location: include/linux/file.h:73
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
In fs/read_write.c (ffffffff8137247e)
Location: include/linux/file.h:73
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
In fs/readdir.c (ffffffff8138c8c0)
Location: include/linux/file.h:73
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
In fs/read_write.c (ffffffff813f05ae)
Location: include/linux/file.h:71
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
In fs/readdir.c (ffffffff8140d191)
Location: include/linux/file.h:71
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
In fs/read_write.c (ffffffff8147895e)
Location: include/linux/file.h:71
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
In fs/readdir.c (ffffffff81497c41)
Location: include/linux/file.h:71
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
In fs/read_write.c (ffffffff814ad3be)
Location: include/linux/file.h:72
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
In fs/readdir.c (ffffffff814ccbb1)
Location: include/linux/file.h:72
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
In fs/read_write.c (ffffffff814ded3e)
Location: include/linux/file.h:72
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
In fs/readdir.c (ffffffff814ff7d1)
Location: include/linux/file.h:72
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
In fs/read_write.c (ffff800010382504)
Location: include/linux/file.h:70
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
In fs/readdir.c (ffff80001039fb94)
Location: include/linux/file.h:70
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
In fs/read_write.c (c056c4b4)
Location: include/linux/file.h:70
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
In fs/readdir.c (c0584900)
Location: include/linux/file.h:70
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
In fs/read_write.c (c000000000478c38)
Location: include/linux/file.h:70
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
In fs/readdir.c (c000000000499e08)
Location: include/linux/file.h:70
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
In fs/read_write.c (ffffffe000256bb8)
Location: include/linux/file.h:70
Inline: True
Inline callers:
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_lseek
```
```
In fs/readdir.c (ffffffe00026a584)
Location: include/linux/file.h:70
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
In fs/read_write.c (ffffffff812d50ae)
Location: include/linux/file.h:70
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
In fs/readdir.c (ffffffff812ed006)
Location: include/linux/file.h:70
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
In fs/read_write.c (ffffffff812c5d2e)
Location: include/linux/file.h:70
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
In fs/readdir.c (ffffffff812ddc36)
Location: include/linux/file.h:70
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
In fs/read_write.c (ffffffff812d2ebe)
Location: include/linux/file.h:70
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
In fs/readdir.c (ffffffff812eae16)
Location: include/linux/file.h:70
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
In fs/read_write.c (ffffffff812e3d1e)
Location: include/linux/file.h:70
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
In fs/readdir.c (ffffffff812fbe06)
Location: include/linux/file.h:70
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
