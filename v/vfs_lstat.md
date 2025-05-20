# Function: <code>vfs_lstat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_lstat(const char *name, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211660)
Location: fs/stat.c:127
Inline: True
Inline callers:
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_newlstat
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - fs/compat.c:C_SYSC_newlstat
```
**Symbols:**

```
ffffffff81211660-ffffffff81211680: vfs_lstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_lstat(const char *name, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81238621)
Location: fs/stat.c:127
Inline: True
Inline callers:
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_lstat
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - fs/compat.c:C_SYSC_newlstat
```
**Symbols:**

```
ffffffff81238110-ffffffff81238130: vfs_lstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vfs_lstat(const char *name, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124b2e1)
Location: fs/stat.c:127
Inline: True
Inline callers:
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_lstat
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - fs/compat.c:C_SYSC_newlstat
```
**Symbols:**

```
ffffffff8124add0-ffffffff8124adf0: vfs_lstat (STB_GLOBAL)
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
In init/initramfs.c (ffffffff8209f327)
Location: include/linux/fs.h:3033
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b656)
Location: include/linux/fs.h:3033
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
```
```
In fs/stat.c (ffffffff812573e1)
Location: include/linux/fs.h:3033
Inline: True
Inline callers:
  - fs/stat.c:C_SYSC_newlstat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_lstat
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
In init/initramfs.c (ffffffff826a5327)
Location: include/linux/fs.h:3099
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81081d56)
Location: include/linux/fs.h:3099
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
```
```
In fs/stat.c (ffffffff81279631)
Location: include/linux/fs.h:3099
Inline: True
Inline callers:
  - fs/stat.c:C_SYSC_newlstat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_lstat
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
In init/initramfs.c (ffffffff826ce5e7)
Location: include/linux/fs.h:3120
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff810850d8)
Location: include/linux/fs.h:3120
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
```
```
In fs/stat.c (ffffffff812a01d8)
Location: include/linux/fs.h:3120
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In init/initramfs.c (ffffffff8288462a)
Location: include/linux/fs.h:3195
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108be48)
Location: include/linux/fs.h:3195
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
```
```
In fs/stat.c (ffffffff812b51b8)
Location: include/linux/fs.h:3195
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In init/initramfs.c (ffffffff8289b679)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108fc49)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
```
```
In fs/stat.c (ffffffff812d1f59)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In init/initramfs.c (ffffffff8289e65e)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff810907a9)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
```
```
In fs/stat.c (ffffffff812e3ae9)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In init/initramfs.c (ffffffff82cc536a)
Location: include/linux/fs.h:3329
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a569)
Location: include/linux/fs.h:3329
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
```
```
In fs/stat.c (ffffffff8131acf9)
Location: include/linux/fs.h:3329
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103ad93)
Location: include/linux/fs.h:3129
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
```
```
In fs/stat.c (ffffffff813262d9)
Location: include/linux/fs.h:3129
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103c763)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
```
```
In fs/stat.c (ffffffff8132c3e9)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In arch/x86/kernel/sys_ia32.c (ffffffff81042263)
Location: include/linux/fs.h:3364
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
```
```
In fs/stat.c (ffffffff81379b59)
Location: include/linux/fs.h:3364
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In arch/x86/kernel/sys_ia32.c (ffffffff81049f7b)
Location: include/linux/fs.h:3142
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
```
```
In fs/stat.c (ffffffff813f95bb)
Location: include/linux/fs.h:3142
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8105518b)
Location: include/linux/fs.h:3296
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
```
```
In fs/stat.c (ffffffff81482d7b)
Location: include/linux/fs.h:3296
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8105639b)
Location: include/linux/fs.h:2911
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
```
```
In fs/stat.c (ffffffff814b799b)
Location: include/linux/fs.h:2911
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8105d5eb)
Location: include/linux/fs.h:3192
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
```
```
In fs/stat.c (ffffffff814e9c2d)
Location: include/linux/fs.h:3192
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In init/initramfs.c (ffff8000114328e0)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In fs/stat.c (ffff80001038aee4)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_newlstat
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
In init/initramfs.c (c150294c)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In fs/stat.c (c0573098)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_newlstat
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
In init/initramfs.c (c000000001346204)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In fs/stat.c (c0000000004829bc)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_newlstat
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
In init/initramfs.c (ffffffe00000244c)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In fs/stat.c (ffffffe00025c864)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_newlstat
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
In init/initramfs.c (ffffffff8288c65e)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f769)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
```
```
In fs/stat.c (ffffffff812dc0c9)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In init/initramfs.c (ffffffff8288a5db)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107e279)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
```
```
In fs/stat.c (ffffffff812ccd49)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In init/initramfs.c (ffffffff8289f65e)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f719)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
```
```
In fs/stat.c (ffffffff812d9ed9)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
In init/initramfs.c (ffffffff8289f663)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81091af9)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
```
```
In fs/stat.c (ffffffff812eade9)
Location: include/linux/fs.h:3268
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_lstat
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
</ul>
