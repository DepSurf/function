# Function: <code>legacy_clone_args_valid</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a2cf)
Location: kernel/fork.c:2420
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
```
**Symbols:**

```
ffffffff8109a420-ffffffff8109a43c: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a089f)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
```
**Symbols:**

```
ffffffff810a09e0-ffffffff810a09fc: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a77a5)
Location: kernel/fork.c:2492
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff810a7850-ffffffff810a786c: legacy_clone_args_valid (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f52f4)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__arm64_sys_clone
```
**Symbols:**

```
ffff8000100f5340-ffff8000100f5378: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03539f4)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone
```
**Symbols:**

```
c03537d0-c0353818: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013b3a0)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone
```
**Symbols:**

```
c00000000013b410-c00000000013b438: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c179e)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone
```
**Symbols:**

```
ffffffe0000c16c8-ffffffe0000c16f6: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a1bf)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
```
**Symbols:**

```
ffffffff8109a300-ffffffff8109a31c: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088bff)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
```
**Symbols:**

```
ffffffff81088d40-ffffffff81088d5c: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a16f)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
```
**Symbols:**

```
ffffffff8109a2b0-ffffffff8109a2cc: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1def)
Location: kernel/fork.c:2405
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
```
**Symbols:**

```
ffffffff810a1f30-ffffffff810a1f4c: legacy_clone_args_valid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
