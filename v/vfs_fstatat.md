# Function: <code>vfs_fstatat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211580)
Location: fs/stat.c:90
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - fs/stat.c:SYSC_stat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newfstatat
  - fs/compat.c:C_SYSC_newfstatat
```
**Symbols:**

```
ffffffff81211580-ffffffff81211640: vfs_fstatat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81238030)
Location: fs/stat.c:90
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_stat
  - fs/compat.c:C_SYSC_newfstatat
```
**Symbols:**

```
ffffffff81238030-ffffffff812380f0: vfs_fstatat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124acf0)
Location: fs/stat.c:90
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - fs/stat.c:SYSC_newfstatat
  - fs/stat.c:SYSC_newlstat
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_lstat
  - fs/stat.c:SYSC_stat
  - fs/compat.c:C_SYSC_newfstatat
```
**Symbols:**

```
ffffffff8124acf0-ffffffff8124adb0: vfs_fstatat (STB_GLOBAL)
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
In arch/x86/ia32/sys_ia32.c (ffffffff8107b746)
Location: include/linux/fs.h:3038
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
```
```
In fs/stat.c (ffffffff81257451)
Location: include/linux/fs.h:3038
Inline: True
Inline callers:
  - fs/stat.c:C_SYSC_newfstatat
  - fs/stat.c:SYSC_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff81081e46)
Location: include/linux/fs.h:3104
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
```
```
In fs/stat.c (ffffffff812796a1)
Location: include/linux/fs.h:3104
Inline: True
Inline callers:
  - fs/stat.c:C_SYSC_newfstatat
  - fs/stat.c:SYSC_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff81085190)
Location: include/linux/fs.h:3125
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
```
```
In fs/stat.c (ffffffff812a0280)
Location: include/linux/fs.h:3125
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108bf00)
Location: include/linux/fs.h:3200
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
```
```
In fs/stat.c (ffffffff812b5260)
Location: include/linux/fs.h:3200
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108fd01)
Location: include/linux/fs.h:3211
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
```
```
In fs/stat.c (ffffffff812d2011)
Location: include/linux/fs.h:3211
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff81090861)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
```
```
In fs/stat.c (ffffffff812e3ba1)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103a611)
Location: include/linux/fs.h:3334
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
```
```
In fs/stat.c (ffffffff8131ada1)
Location: include/linux/fs.h:3334
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81326431)
Location: fs/stat.c:204
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81326870-ffffffff81326891: vfs_fstatat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c541)
Location: fs/stat.c:222
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8132c980-ffffffff8132c9a1: vfs_fstatat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379cb1)
Location: fs/stat.c:240
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8137a0f0-ffffffff8137a111: vfs_fstatat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f9110)
Location: fs/stat.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff813f9110-ffffffff813f918e: vfs_fstatat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814827e0)
Location: fs/stat.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff814827e0-ffffffff8148285e: vfs_fstatat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7400)
Location: fs/stat.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newfstatat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
```
**Symbols:**

```
ffffffff814b7400-ffffffff814b747e: vfs_fstatat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fstatat(int dfd, const char *filename, struct kstat *stat, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9c2d)
Location: fs/stat.c:279
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newlstat
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newlstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_lstat
  - fs/stat.c:__do_sys_stat
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
```
**Symbols:**

```
ffffffff814e9e40-ffffffff814e9f1c: vfs_fstatat (STB_GLOBAL)
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
In fs/stat.c (ffff80001038af80)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_fstatat64
  - fs/stat.c:__do_sys_newfstatat
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
In fs/stat.c (c0573184)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_fstatat64
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
In fs/stat.c (c0000000004823b8)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_fstatat64
  - fs/stat.c:__do_sys_newfstatat
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
In fs/stat.c (ffffffe00025c8a6)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f821)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
```
```
In fs/stat.c (ffffffff812dc181)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8107e331)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
```
```
In fs/stat.c (ffffffff812cce01)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f7d1)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
```
```
In fs/stat.c (ffffffff812d9f91)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
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
In arch/x86/ia32/sys_ia32.c (ffffffff81091bb1)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
```
```
In fs/stat.c (ffffffff812eaea1)
Location: include/linux/fs.h:3273
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newfstatat
  - fs/stat.c:__do_sys_newfstatat
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
