# Function: <code>do_sysctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t do_sysctl(int *args_name, int nlen, void *oldval, size_t oldlen, void *newval, size_t newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff81089c20)
Location: kernel/sysctl_binary.c:1401
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:SyS_sysctl
  - kernel/sysctl_binary.c:compat_SyS_sysctl
```
**Symbols:**

```
ffffffff81089c20-ffffffff81089ffe: do_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t do_sysctl(int *args_name, int nlen, void *oldval, size_t oldlen, void *newval, size_t newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff8108cb70)
Location: kernel/sysctl_binary.c:1392
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:SyS_sysctl
```
**Symbols:**

```
ffffffff8108cb70-ffffffff8108cf2a: do_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_sysctl(int *args_name, int nlen, void *oldval, size_t oldlen, void *newval, size_t newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff81091af0)
Location: kernel/sysctl_binary.c:1392
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:SyS_sysctl
```
**Symbols:**

```
ffffffff81091af0-ffffffff81091eaa: do_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff8108f18d)
Location: kernel/sysctl_binary.c:1392
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:SyS_sysctl
Direct callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:SyS_sysctl
```
**Symbols:**

```
ffffffff8108ec90-ffffffff8108f02a: do_sysctl.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff8109603d)
Location: kernel/sysctl_binary.c:1400
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:SyS_sysctl
Direct callers:
  - kernel/sysctl_binary.c:compat_SyS_sysctl
  - kernel/sysctl_binary.c:SyS_sysctl
```
**Symbols:**

```
ffffffff81095b50-ffffffff81095ed1: do_sysctl.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff8109915c)
Location: kernel/sysctl_binary.c:1382
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff81098d40-ffffffff81098e45: do_sysctl.isra.1.part.2 (STB_LOCAL)
ffffffff810991ed-ffffffff81099243: do_sysctl.isra.1.part.2.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff810a14dc)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff810a10c0-ffffffff810a11c5: do_sysctl.isra.1.part.2 (STB_LOCAL)
ffffffff810a156d-ffffffff810a15c3: do_sysctl.isra.1.part.2.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff810a5f2c)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff810a5b20-ffffffff810a5c11: do_sysctl.isra.0.part.0 (STB_LOCAL)
ffffffff810a5fbf-ffffffff810a6012: do_sysctl.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff810ac50c)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff810ac100-ffffffff810ac1f1: do_sysctl.isra.0.part.0 (STB_LOCAL)
ffffffff810ac59f-ffffffff810ac5f2: do_sysctl.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff810b40ec)
Location: kernel/sysctl_binary.c:78
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff810b3dc0-ffffffff810b3eb1: do_sysctl.part.0 (STB_LOCAL)
ffffffff810b425e-ffffffff810b42b1: do_sysctl.part.0.cold (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffff800010105708)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
```
**Symbols:**

```
ffff800010104e08-ffff8000101050cc: do_sysctl.isra.0.part.0 (STB_LOCAL)
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
In kernel/sysctl_binary.c (c0360a04)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (c00000000014cd54)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
**Symbols:**

```
c00000000014c9f0-c00000000014cc60: do_sysctl.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffe0000cac4c)
Location: kernel/sysctl_binary.c:1383
Inline: True
Direct callers:
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
**Symbols:**

```
ffffffe0000cac4c-ffffffe0000cadb6: do_sysctl.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff810a68a2)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff810a61f0-ffffffff810a6552: do_sysctl.part.0 (STB_LOCAL)
ffffffff810a691f-ffffffff810a6969: do_sysctl.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff81095282)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff81094bd0-ffffffff81094f32: do_sysctl.part.0 (STB_LOCAL)
ffffffff810952ff-ffffffff81095349: do_sysctl.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff810a5ddc)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff810a59d0-ffffffff810a5ac1: do_sysctl.isra.0.part.0 (STB_LOCAL)
ffffffff810a5e6f-ffffffff810a5ec2: do_sysctl.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl_binary.c (ffffffff810ade9c)
Location: kernel/sysctl_binary.c:1383
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
Direct callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_sys_sysctl
  - kernel/sysctl_binary.c:__x64_sys_sysctl
```
**Symbols:**

```
ffffffff810ada90-ffffffff810adb81: do_sysctl.isra.0.part.0 (STB_LOCAL)
ffffffff810adf2f-ffffffff810adf82: do_sysctl.isra.0.part.0.cold (STB_LOCAL)
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
