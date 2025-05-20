# Function: <code>vfs_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_stat(const char *name, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211640)
Location: fs/stat.c:121
Inline: True
Inline callers:
  - fs/stat.c:SYSC_stat
  - fs/stat.c:SYSC_newstat
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
  - fs/compat.c:C_SYSC_newstat
```
**Symbols:**

```
ffffffff81211640-ffffffff8121165d: vfs_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_stat(const char *name, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812385c1)
Location: fs/stat.c:121
Inline: True
Inline callers:
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_stat
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
  - fs/compat.c:C_SYSC_newstat
```
**Symbols:**

```
ffffffff812380f0-ffffffff8123810d: vfs_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vfs_stat(const char *name, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124b281)
Location: fs/stat.c:121
Inline: True
Inline callers:
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_stat
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
  - fs/compat.c:C_SYSC_newstat
```
**Symbols:**

```
ffffffff8124adb0-ffffffff8124adcd: vfs_stat (STB_GLOBAL)
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
In init/do_mounts_md.c (ffffffff810027e4)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b5d6)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
```
```
In fs/stat.c (ffffffff81257371)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/stat.c:C_SYSC_newstat
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_stat
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
In init/do_mounts_md.c (ffffffff81002814)
Location: include/linux/fs.h:3094
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81081cd6)
Location: include/linux/fs.h:3094
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
```
```
In fs/stat.c (ffffffff812795c1)
Location: include/linux/fs.h:3094
Inline: True
Inline callers:
  - fs/stat.c:C_SYSC_newstat
  - fs/stat.c:SYSC_newstat
  - fs/stat.c:SYSC_stat
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
In init/do_mounts_md.c (ffffffff81002f79)
Location: include/linux/fs.h:3115
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81085018)
Location: include/linux/fs.h:3115
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
```
In fs/stat.c (ffffffff812a0128)
Location: include/linux/fs.h:3115
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In init/do_mounts_md.c (ffffffff81003006)
Location: include/linux/fs.h:3190
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108bd88)
Location: include/linux/fs.h:3190
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
```
In fs/stat.c (ffffffff812b5108)
Location: include/linux/fs.h:3190
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In init/do_mounts_md.c (ffffffff81003134)
Location: include/linux/fs.h:3201
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108fb89)
Location: include/linux/fs.h:3201
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
```
In fs/stat.c (ffffffff812d1e99)
Location: include/linux/fs.h:3201
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In init/do_mounts_md.c (ffffffff81003124)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff810906e9)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
```
In fs/stat.c (ffffffff812e3a29)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In init/do_mounts_md.c (ffffffff81004311)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a4b9)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
```
In fs/stat.c (ffffffff8131ac49)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103ace0)
Location: include/linux/fs.h:3125
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
```
In fs/stat.c (ffffffff813260c9)
Location: include/linux/fs.h:3125
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103c6b0)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
```
In fs/stat.c (ffffffff8132c1d9)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In arch/x86/kernel/sys_ia32.c (ffffffff810421b0)
Location: include/linux/fs.h:3360
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
```
In fs/stat.c (ffffffff81379949)
Location: include/linux/fs.h:3360
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In arch/x86/kernel/sys_ia32.c (ffffffff81049ecb)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
```
In fs/stat.c (ffffffff813f936b)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In arch/x86/kernel/sys_ia32.c (ffffffff810550bb)
Location: include/linux/fs.h:3292
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
```
In fs/stat.c (ffffffff81482aab)
Location: include/linux/fs.h:3292
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In arch/x86/kernel/sys_ia32.c (ffffffff810562cb)
Location: include/linux/fs.h:2907
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
```
In fs/stat.c (ffffffff814b76cb)
Location: include/linux/fs.h:2907
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In arch/x86/kernel/sys_ia32.c (ffffffff8105d51b)
Location: include/linux/fs.h:3188
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
```
In fs/stat.c (ffffffff814e9d30)
Location: include/linux/fs.h:3188
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In init/do_mounts_md.c (ffff800010085774)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In fs/stat.c (ffff80001038ae44)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_stat64
  - fs/stat.c:__do_sys_newstat
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
In init/do_mounts_md.c (c0303f44)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In fs/stat.c (c0573018)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_stat64
  - fs/stat.c:__do_sys_newstat
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
In init/do_mounts_md.c (c000000000011408)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In fs/stat.c (c00000000048290c)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_stat64
  - fs/stat.c:__do_sys_newstat
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
In init/do_mounts_md.c (ffffffe0000b4b0e)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In fs/stat.c (ffffffe00025c822)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_sys_newstat
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
In init/do_mounts_md.c (ffffffff81003124)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f6a9)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
```
In fs/stat.c (ffffffff812dc009)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In init/do_mounts_md.c (ffffffff81001604)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107e1b9)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
```
In fs/stat.c (ffffffff812ccc89)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In init/do_mounts_md.c (ffffffff81003124)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f659)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
```
In fs/stat.c (ffffffff812d9e19)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
In init/do_mounts_md.c (ffffffff81003174)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - init/do_mounts_md.c:bstat
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81091a39)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
```
In fs/stat.c (ffffffff812ead29)
Location: include/linux/fs.h:3263
Inline: True
Inline callers:
  - fs/stat.c:__do_compat_sys_newstat
  - fs/stat.c:__do_sys_newstat
  - fs/stat.c:__do_sys_stat
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
