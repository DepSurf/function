# Function: <code>do_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122ec10)
Location: fs/namespace.c:2661
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff8122ec10-ffffffff8122fa0a: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81257430)
Location: fs/namespace.c:2646
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff81257430-ffffffff812580de: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126a8c0)
Location: fs/namespace.c:2765
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff8126a8c0-ffffffff8126b56e: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81278060)
Location: fs/namespace.c:2707
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff81278060-ffffffff81278d39: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129aaa0)
Location: fs/namespace.c:2772
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff8129aaa0-ffffffff8129b77c: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c0b60)
Location: fs/namespace.c:2803
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812c0b60-ffffffff812c1847: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d5db0)
Location: fs/namespace.c:2773
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812d5db0-ffffffff812d6afb: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f4530)
Location: fs/namespace.c:3039
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812f4530-ffffffff812f4f1d: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813060e0)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff813060e0-ffffffff81306a9c: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133fd50)
Location: fs/namespace.c:3128
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff8133fd50-ffffffff8134023b: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134c2ea)
Location: fs/namespace.c:3224
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff8134c390-ffffffff8134c421: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81352eba)
Location: fs/namespace.c:3257
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff81352f60-ffffffff81352ff1: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813a130a)
Location: fs/namespace.c:3331
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff813a13b0-ffffffff813a1441: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81424c99)
Location: fs/namespace.c:3374
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff81424d60-ffffffff81424e10: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814b13b9)
Location: fs/namespace.c:3479
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff814b1490-ffffffff814b1540: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e63f9)
Location: fs/namespace.c:3666
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff814e64d0-ffffffff814e6580: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8151a239)
Location: fs/namespace.c:3683
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff8151a310-ffffffff8151a3c0: do_mount (STB_GLOBAL)
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
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b9708)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__arm64_compat_sys_mount
```
**Symbols:**

```
ffff8000103b9708-ffff8000103ba128: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0597214)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
```
**Symbols:**

```
c0597214-c0597b48: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b6c00)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__se_compat_sys_mount
```
**Symbols:**

```
c0000000004b6c00-c0000000004b7804: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027ba4e)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
```
**Symbols:**

```
ffffffe00027ba4e-ffffffe00027c32e: do_mount (STB_GLOBAL)
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
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fe6c0)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812fe6c0-ffffffff812ff07c: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef2e0)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812ef2e0-ffffffff812efc9c: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fc4b0)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812fc4b0-ffffffff812fce6c: do_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130d810)
Location: fs/namespace.c:3070
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff8130d810-ffffffff8130e1ce: do_mount (STB_GLOBAL)
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
