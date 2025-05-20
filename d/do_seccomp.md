# Function: <code>do_seccomp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, const char *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8113b680)
Location: kernel/seccomp.c:817
Inline: True
Direct callers:
  - kernel/seccomp.c:SyS_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
```
**Symbols:**

```
ffffffff8113b680-ffffffff8113bc83: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, const char *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81143e40)
Location: kernel/seccomp.c:782
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:SyS_seccomp
```
**Symbols:**

```
ffffffff81143e40-ffffffff8114443d: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, const char *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114dd00)
Location: kernel/seccomp.c:781
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:SyS_seccomp
```
**Symbols:**

```
ffffffff8114dd00-ffffffff8114e2ed: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, const char *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81150330)
Location: kernel/seccomp.c:896
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:SyS_seccomp
```
**Symbols:**

```
ffffffff81150330-ffffffff8115098e: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, const char *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115c540)
Location: kernel/seccomp.c:920
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:SyS_seccomp
```
**Symbols:**

```
ffffffff8115c540-ffffffff8115cbc8: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, const char *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116b8e0)
Location: kernel/seccomp.c:926
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff8116b8e0-ffffffff8116bfa3: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811790e0)
Location: kernel/seccomp.c:1365
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff811790e0-ffffffff811799c5: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811865b0)
Location: kernel/seccomp.c:1380
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff811865b0-ffffffff811867aa: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81192530)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff81192530-ffffffff8119272a: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a73e0)
Location: kernel/seccomp.c:1424
Inline: False
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff811a73e0-ffffffff811a7531: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4b20)
Location: kernel/seccomp.c:1915
Inline: False
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff811a4b20-ffffffff811a4c71: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a56f0)
Location: kernel/seccomp.c:1963
Inline: False
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff811a56f0-ffffffff811a58df: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cee40)
Location: kernel/seccomp.c:1945
Inline: False
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff811cee40-ffffffff811cf02f: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81202f80)
Location: kernel/seccomp.c:1982
Inline: False
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff81202f80-ffffffff81203183: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8124adf0)
Location: kernel/seccomp.c:1982
Inline: False
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff8124adf0-ffffffff8124aff3: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812620f0)
Location: kernel/seccomp.c:1982
Inline: False
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff812620f0-ffffffff81262313: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127c330)
Location: kernel/seccomp.c:2046
Inline: False
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff8127c330-ffffffff8127c553: do_seccomp (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff800010209e08)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__arm64_sys_seccomp
```
**Symbols:**

```
ffff800010209e08-ffff80001020a0a4: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0448ce4)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__se_sys_seccomp
```
**Symbols:**

```
c0448ce4-c0448f90: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int do_seccomp(struct pt_regs *regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000019264)
Location: arch/powerpc/kernel/ptrace.c:3220
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
```
```
In kernel/seccomp.c (c000000000287210)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__se_sys_seccomp
```
**Symbols:**

```
c000000000287210-c000000000287520: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016bd3e)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__se_sys_seccomp
```
**Symbols:**

```
ffffffe00016bd3e-ffffffe00016bf06: do_seccomp (STB_LOCAL)
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
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8118ab50)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff8118ab50-ffffffff8118ad4a: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117dc70)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff8117dc70-ffffffff8117de64: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81188920)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff81188920-ffffffff81188b1a: do_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int do_seccomp(unsigned int op, unsigned int flags, void *uargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81196290)
Location: kernel/seccomp.c:1403
Inline: True
Direct callers:
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:prctl_set_seccomp
  - kernel/seccomp.c:__ia32_sys_seccomp
  - kernel/seccomp.c:__x64_sys_seccomp
```
**Symbols:**

```
ffffffff81196290-ffffffff8119648b: do_seccomp (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char *uargs</code> ➡️ <code>void *uargs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pt_regs *regs</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>void *uargs</code>
</li>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
