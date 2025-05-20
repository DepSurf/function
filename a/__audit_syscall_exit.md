# Function: <code>__audit_syscall_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81128660)
Location: kernel/auditsc.c:1543
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81128660-ffffffff8112891d: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81130810)
Location: kernel/auditsc.c:1542
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81130810-ffffffff81130aa9: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113a580)
Location: kernel/auditsc.c:1547
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff8113a580-ffffffff8113a819: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113bbb0)
Location: kernel/auditsc.c:1556
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff8113bbb0-ffffffff8113be5b: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81148930)
Location: kernel/auditsc.c:1556
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81148930-ffffffff81148bdb: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81157330)
Location: kernel/auditsc.c:1564
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81157330-ffffffff811575ab: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81164350)
Location: kernel/auditsc.c:1532
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81164350-ffffffff811645a4: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81170f90)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81170f90-ffffffff81171215: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117ce10)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff8117ce10-ffffffff8117d095: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190130)
Location: kernel/auditsc.c:1705
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
```
**Symbols:**

```
ffffffff81190130-ffffffff811903f2: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d3b0)
Location: kernel/auditsc.c:1723
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff8118d3b0-ffffffff8118d673: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e200)
Location: kernel/auditsc.c:1721
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff8118e200-ffffffff8118e4b3: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1731
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff81cb367f-ffffffff81cb369a: __audit_syscall_exit.cold (STB_LOCAL)
ffffffff811b7010-ffffffff811b72cf: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e9f10)
Location: kernel/auditsc.c:2058
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff811e9f10-ffffffff811e9ff4: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81230070)
Location: kernel/auditsc.c:2036
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff81230070-ffffffff812301a2: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81246b60)
Location: kernel/auditsc.c:2033
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff81246b60-ffffffff81246c92: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81260a10)
Location: kernel/auditsc.c:2028
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff81260a10-ffffffff81260b42: __audit_syscall_exit (STB_GLOBAL)
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
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f1c80)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
```
**Symbols:**

```
ffff8000101f1c80-ffff8000101f1eb0: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0432158)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
```
**Symbols:**

```
c0432158-c04323b8: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0000000002660c0)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
```
**Symbols:**

```
c0000000002660c0-c0000000002663c8: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165518)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
```
**Symbols:**

```
ffffffe000165518-ffffffe0001656fc: __audit_syscall_exit (STB_GLOBAL)
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
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81175430)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81175430-ffffffff811756b5: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811685d0)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff811685d0-ffffffff81168855: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81173200)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81173200-ffffffff81173485: __audit_syscall_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_syscall_exit(int success, long int return_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81180a70)
Location: kernel/auditsc.c:1674
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81180a70-ffffffff81180cf5: __audit_syscall_exit (STB_GLOBAL)
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
