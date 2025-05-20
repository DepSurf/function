# Function: <code>arch_syscall_match_sym_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81f85200)
Location: kernel/trace/trace_syscalls.c:35
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81fae804)
Location: kernel/trace/trace_syscalls.c:35
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81feae2b)
Location: kernel/trace/trace_syscalls.c:35
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff820cb850)
Location: kernel/trace/trace_syscalls.c:35
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff826d3ebf)
Location: kernel/trace/trace_syscalls.c:36
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811974a7)
Location: arch/x86/include/asm/ftrace.h:52
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811974a7-ffffffff81197532: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811a5617)
Location: arch/x86/include/asm/ftrace.h:52
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811a5617-ffffffff811a56a2: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b3538)
Location: arch/x86/include/asm/ftrace.h:49
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811b3538-ffffffff811b35c3: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811beb28)
Location: arch/x86/include/asm/ftrace.h:49
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811beb28-ffffffff811bebb3: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811d8388)
Location: arch/x86/include/asm/ftrace.h:66
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811d8388-ffffffff811d8445: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81be6214)
Location: arch/x86/include/asm/ftrace.h:84
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81be6214-ffffffff81be62d1: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81bd7ecf)
Location: arch/x86/include/asm/ftrace.h:84
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81bd7ecf-ffffffff81bd7f8c: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81cb65cb)
Location: arch/x86/include/asm/ftrace.h:84
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81cb65cb-ffffffff81cb6688: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81e6759e)
Location: arch/x86/include/asm/ftrace.h:96
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81e6759e-ffffffff81e67665: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff83eb6125)
Location: arch/x86/include/asm/ftrace.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff836db505)
Location: arch/x86/include/asm/ftrace.h:119
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8390da75)
Location: arch/x86/include/asm/ftrace.h:119
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
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
In kernel/trace/trace_syscalls.c (ffff80001144f2c8)
Location: arch/arm64/include/asm/ftrace.h:73
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c0479784)
Location: arch/arm/include/asm/ftrace.h:61
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
c0479784-c047982c: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c0000000002cdb3c)
Location: arch/powerpc/include/asm/ftrace.h:88
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
c0000000002cdb3c-c0000000002cdc80: arch_syscall_match_sym_name (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffe00000f742)
Location: kernel/trace/trace_syscalls.c:36
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
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
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b7148)
Location: arch/x86/include/asm/ftrace.h:49
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811b7148-ffffffff811b71d3: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811a9f38)
Location: arch/x86/include/asm/ftrace.h:49
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811a9f38-ffffffff811a9fc3: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b4f18)
Location: arch/x86/include/asm/ftrace.h:49
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811b4f18-ffffffff811b4fa3: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char *sym, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811c2fb8)
Location: arch/x86/include/asm/ftrace.h:49
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811c2fb8-ffffffff811c3043: arch_syscall_match_sym_name (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
