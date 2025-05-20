# Function: <code>__audit_syscall_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81128570)
Location: kernel/auditsc.c:1494
Inline: False
```
**Symbols:**

```
ffffffff81128570-ffffffff8112865e: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81130720)
Location: kernel/auditsc.c:1493
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff81130720-ffffffff81130810: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113a490)
Location: kernel/auditsc.c:1498
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff8113a490-ffffffff8113a580: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113bac0)
Location: kernel/auditsc.c:1507
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff8113bac0-ffffffff8113bbac: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81148820)
Location: kernel/auditsc.c:1507
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff81148820-ffffffff81148921: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811571d0)
Location: kernel/auditsc.c:1518
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff811571d0-ffffffff8115732a: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81164220)
Location: kernel/auditsc.c:1486
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff81164220-ffffffff81164344: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81170e70)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff81170e70-ffffffff81170f8f: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117ccf0)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff8117ccf0-ffffffff8117ce0f: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190010)
Location: kernel/auditsc.c:1659
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff81190010-ffffffff8119012f: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d290)
Location: kernel/auditsc.c:1677
Inline: False
```
**Symbols:**

```
ffffffff8118d290-ffffffff8118d3af: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e0e0)
Location: kernel/auditsc.c:1675
Inline: False
```
**Symbols:**

```
ffffffff8118e0e0-ffffffff8118e1fc: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b6ef0)
Location: kernel/auditsc.c:1685
Inline: False
```
**Symbols:**

```
ffffffff811b6ef0-ffffffff811b700c: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e9da0)
Location: kernel/auditsc.c:2009
Inline: False
```
**Symbols:**

```
ffffffff811e9da0-ffffffff811e9f05: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122fef0)
Location: kernel/auditsc.c:1987
Inline: False
```
**Symbols:**

```
ffffffff8122fef0-ffffffff81230055: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812469e0)
Location: kernel/auditsc.c:1984
Inline: False
```
**Symbols:**

```
ffffffff812469e0-ffffffff81246b45: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81260890)
Location: kernel/auditsc.c:1979
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff81260890-ffffffff812609f5: __audit_syscall_entry (STB_GLOBAL)
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
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f1b70)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
```
**Symbols:**

```
ffff8000101f1b70-ffff8000101f1c7c: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0432028)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
```
**Symbols:**

```
c0432028-c0432158: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000265f20)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
```
**Symbols:**

```
c000000000265f20-c0000000002660c0: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165450)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
```
**Symbols:**

```
ffffffe000165450-ffffffe000165518: __audit_syscall_entry (STB_GLOBAL)
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
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81175310)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff81175310-ffffffff8117542f: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811684b0)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff811684b0-ffffffff811685cf: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811730e0)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff811730e0-ffffffff811731ff: __audit_syscall_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_syscall_entry(int major, long unsigned int a1, long unsigned int a2, long unsigned int a3, long unsigned int a4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81180950)
Location: kernel/auditsc.c:1628
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff81180950-ffffffff81180a6f: __audit_syscall_entry (STB_GLOBAL)
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
