# Function: <code>vfs_fstat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_fstat(unsigned int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211520)
Location: fs/stat.c:77
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - fs/stat.c:SYSC_fstat
  - fs/stat.c:SYSC_newfstat
  - fs/compat.c:C_SYSC_newfstat
```
**Symbols:**

```
ffffffff81211520-ffffffff81211578: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_fstat(unsigned int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81237fd0)
Location: fs/stat.c:77
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_fstat
  - fs/compat.c:C_SYSC_newfstat
```
**Symbols:**

```
ffffffff81237fd0-ffffffff81238028: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_fstat(unsigned int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124ac90)
Location: fs/stat.c:77
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_fstat
  - fs/compat.c:C_SYSC_newfstat
```
**Symbols:**

```
ffffffff8124ac90-ffffffff8124ace8: vfs_fstat (STB_GLOBAL)
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
In arch/x86/ia32/sys_ia32.c (ffffffff8107b6d6)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
```
```
In fs/stat.c (ffffffff812574c1)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/stat.c:C_SYSC_newfstat
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_fstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff81081dd6)
Location: include/linux/fs.h:3110
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
```
```
In fs/stat.c (ffffffff81279711)
Location: include/linux/fs.h:3110
Inline: True
Inline callers:
  - fs/stat.c:C_SYSC_newfstat
  - fs/stat.c:SYSC_newfstat
  - fs/stat.c:SYSC_fstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108523c)
Location: include/linux/fs.h:3131
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
```
```
In fs/stat.c (ffffffff812a032c)
Location: include/linux/fs.h:3131
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108bfac)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
```
```
In fs/stat.c (ffffffff812b530c)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108fdad)
Location: include/linux/fs.h:3217
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
```
```
In fs/stat.c (ffffffff812d20bd)
Location: include/linux/fs.h:3217
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8109090d)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
```
```
In fs/stat.c (ffffffff812e3c4d)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103a6bd)
Location: include/linux/fs.h:3340
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
```
```
In fs/stat.c (ffffffff8131b0dd)
Location: include/linux/fs.h:3340
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_fstat(int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81326610)
Location: fs/stat.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff81326610-ffffffff8132668e: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_fstat(int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c720)
Location: fs/stat.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff8132c720-ffffffff8132c79e: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_fstat(int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379e90)
Location: fs/stat.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff81379e90-ffffffff81379f0e: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_fstat(int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f8e10)
Location: fs/stat.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff813f8e10-ffffffff813f8eae: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_fstat(int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482440)
Location: fs/stat.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff81482440-ffffffff814824de: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_fstat(int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7050)
Location: fs/stat.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
```
**Symbols:**

```
ffffffff814b7050-ffffffff814b70f1: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_fstat(int fd, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e93d0)
Location: fs/stat.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
  - fs/stat.c:vfs_fstatat
```
**Symbols:**

```
ffffffff814e93d0-ffffffff814e9471: vfs_fstat (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038b020)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_newfstat
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (c057310c)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_newfstat
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000482a64)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_newfstat
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c8e8)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_newfstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f8cd)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
```
```
In fs/stat.c (ffffffff812dc22d)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8107e3dd)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
```
```
In fs/stat.c (ffffffff812ccead)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f87d)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
```
```
In fs/stat.c (ffffffff812da03d)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
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
In arch/x86/ia32/sys_ia32.c (ffffffff81091c5d)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
```
```
In fs/stat.c (ffffffff812eaf4d)
Location: include/linux/fs.h:3279
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstat
  - fs/stat.c:__do_sys_newfstat
  - fs/stat.c:__do_sys_fstat
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
