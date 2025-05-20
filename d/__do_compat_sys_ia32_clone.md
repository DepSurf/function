# Function: <code>__do_compat_sys_ia32_clone</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, long unsigned int tls_val, int *child_tidptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a240)
Location: arch/x86/kernel/sys_ia32.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_clone
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff8103a240-ffffffff8103a2c6: __do_compat_sys_ia32_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, long unsigned int tls_val, int *child_tidptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103aa50)
Location: arch/x86/kernel/sys_ia32.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_clone
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff8103aa50-ffffffff8103aac2: __do_compat_sys_ia32_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, long unsigned int tls_val, int *child_tidptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c450)
Location: arch/x86/kernel/sys_ia32.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_clone
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff8103c450-ffffffff8103c4c2: __do_compat_sys_ia32_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, long unsigned int tls_val, int *child_tidptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81041f50)
Location: arch/x86/kernel/sys_ia32.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__x64_compat_sys_ia32_clone
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff81041f50-ffffffff81041fc2: __do_compat_sys_ia32_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, long unsigned int tls_val, int *child_tidptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8104a210)
Location: arch/x86/kernel/sys_ia32.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff8104a210-ffffffff8104a2b3: __do_compat_sys_ia32_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, long unsigned int tls_val, int *child_tidptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81055490)
Location: arch/x86/kernel/sys_ia32.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff81055490-ffffffff81055533: __do_compat_sys_ia32_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, long unsigned int tls_val, int *child_tidptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81056030)
Location: arch/x86/kernel/sys_ia32.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff81056030-ffffffff810560c3: __do_compat_sys_ia32_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_ia32_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, long unsigned int tls_val, int *child_tidptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d280)
Location: arch/x86/kernel/sys_ia32.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_clone
```
**Symbols:**

```
ffffffff8105d280-ffffffff8105d313: __do_compat_sys_ia32_clone (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
