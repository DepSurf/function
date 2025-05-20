# Function: <code>_do_fork</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int _do_fork(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810801b0)
Location: kernel/fork.c:1702
Inline: False
Direct callers:
  - kernel/fork.c:kernel_thread
  - kernel/fork.c:sys_fork
  - kernel/fork.c:sys_vfork
  - kernel/fork.c:SyS_clone
```
**Symbols:**

```
ffffffff810801b0-ffffffff81080503: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int _do_fork(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081f60)
Location: kernel/fork.c:1761
Inline: False
Direct callers:
  - kernel/fork.c:SyS_clone
  - kernel/fork.c:sys_vfork
  - kernel/fork.c:sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff81081f60-ffffffff81082345: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int _do_fork(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810869c0)
Location: kernel/fork.c:1922
Inline: False
Direct callers:
  - kernel/fork.c:SyS_clone
  - kernel/fork.c:sys_vfork
  - kernel/fork.c:sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810869c0-ffffffff81086da5: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int _do_fork(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81083710)
Location: kernel/fork.c:2018
Inline: False
Direct callers:
  - kernel/fork.c:SyS_clone
  - kernel/fork.c:sys_vfork
  - kernel/fork.c:sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff81083710-ffffffff81083afd: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int _do_fork(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81089ff0)
Location: kernel/fork.c:2027
Inline: False
Direct callers:
  - kernel/fork.c:SyS_clone
  - kernel/fork.c:sys_vfork
  - kernel/fork.c:sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff81089ff0-ffffffff8108a3e3: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int _do_fork(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108d800)
Location: kernel/fork.c:2101
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
  - kernel/fork.c:__x64_sys_vfork
  - kernel/fork.c:__x64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff8108d800-ffffffff8108dbf3: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int _do_fork(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81095a90)
Location: kernel/fork.c:2206
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
  - kernel/fork.c:__x64_sys_vfork
  - kernel/fork.c:__x64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff81095a90-ffffffff81095e83: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099dd0)
Location: kernel/fork.c:2354
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
  - kernel/fork.c:__x64_sys_vfork
  - kernel/fork.c:__x64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff81099dd0-ffffffff8109a130: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a03b0)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
  - kernel/fork.c:__x64_sys_vfork
  - kernel/fork.c:__x64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810a03b0-ffffffff810a0710: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a7290)
Location: kernel/fork.c:2426
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:__do_sys_clone
  - kernel/fork.c:__do_sys_vfork
  - kernel/fork.c:__do_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810a7290-ffffffff810a7553: _do_fork (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f4c20)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - kernel/fork.c:__arm64_sys_clone3
  - kernel/fork.c:__arm64_sys_clone
  - kernel/fork.c:__arm64_sys_vfork
  - kernel/fork.c:__arm64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffff8000100f4c20-ffff8000100f50d0: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03533c4)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_clone3
  - kernel/fork.c:__se_sys_clone
  - kernel/fork.c:sys_vfork
  - kernel/fork.c:sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
c03533c4-c03537d0: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013ac60)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_clone3
  - kernel/fork.c:__se_sys_clone
  - kernel/fork.c:sys_vfork
  - kernel/fork.c:sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
c00000000013ac60-c00000000013b11c: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c139c)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_clone3
  - kernel/fork.c:__se_sys_clone
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffe0000c139c-ffffffe0000c16c8: _do_fork (STB_GLOBAL)
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
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099cd0)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
  - kernel/fork.c:__x64_sys_vfork
  - kernel/fork.c:__x64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff81099cd0-ffffffff8109a030: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088710)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
  - kernel/fork.c:__x64_sys_vfork
  - kernel/fork.c:__x64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff81088710-ffffffff81088a70: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099c80)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
  - kernel/fork.c:__x64_sys_vfork
  - kernel/fork.c:__x64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff81099c80-ffffffff81099fe0: _do_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int _do_fork(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a18d0)
Location: kernel/fork.c:2339
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
  - kernel/fork.c:__x64_sys_vfork
  - kernel/fork.c:__x64_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810a18d0-ffffffff810a1c5b: _do_fork (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kernel_clone_args *args</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int clone_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int stack_start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int stack_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int *parent_tidptr</code>
</li>
<li>
<b>Param removed. </b>
<code>int *child_tidptr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int tls</code>
</li>
</ul>
</details>
</li>
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
