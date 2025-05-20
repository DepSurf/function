# Function: <code>print_ip_sym</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810eaa2f)
Location: include/linux/kallsyms.h:123
Inline: True
Inline callers:
  - kernel/stacktrace.c:print_stack_trace
```
```
In kernel/trace/ftrace.c (ffffffff81142f89)
Location: include/linux/kallsyms.h:123
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810f16d8)
Location: include/linux/kallsyms.h:123
Inline: True
Inline callers:
  - kernel/stacktrace.c:print_stack_trace
```
```
In kernel/trace/ftrace.c (ffffffff8114ae5b)
Location: include/linux/kallsyms.h:123
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
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
In kernel/trace/ftrace.c (ffffffff81154d4b)
Location: include/linux/kallsyms.h:123
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
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
In kernel/trace/ftrace.c (ffffffff8115773a)
Location: include/linux/kallsyms.h:123
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
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
In kernel/trace/ftrace.c (ffffffff8116423a)
Location: include/linux/kallsyms.h:132
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81177a9a)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81177a9a-ffffffff81177ab2: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81185044)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81185044-ffffffff8118505c: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191f2a)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81191f2a-ffffffff81191f42: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119df5a)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8119df5a-ffffffff8119df72: print_ip_sym (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff811b4651)
Location: include/linux/kallsyms.h:169
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff811b4651-ffffffff811b4670: print_ip_sym.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81be510e)
Location: include/linux/kallsyms.h:169
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81be510e-ffffffff81be512d: print_ip_sym.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81bd6f51)
Location: include/linux/kallsyms.h:160
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81bd6f51-ffffffff81bd6f70: print_ip_sym.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81cb41b0)
Location: include/linux/kallsyms.h:177
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81cb41b0-ffffffff81cb41cf: print_ip_sym.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81e65165)
Location: include/linux/kallsyms.h:173
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81e65165-ffffffff81e65192: print_ip_sym.constprop.0 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81255e66)
Location: include/linux/kallsyms.h:182
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
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
In kernel/trace/ftrace.c (ffffffff8126d216)
Location: include/linux/kallsyms.h:170
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
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
In kernel/trace/ftrace.c (ffffffff81287806)
Location: include/linux/kallsyms.h:170
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
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
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010216f54)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffff800010216f54-ffff800010216f78: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0455cd8)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
c0455cd8-c0455cfc: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000029923c)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
c00000000029923c-c000000000299278: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/stacktrace.c (ffffffe0000b73dc)
Location: include/linux/kallsyms.h:168
Inline: True
Inline callers:
  - arch/riscv/kernel/stacktrace.c:print_trace_address
```
```
In kernel/trace/ftrace.c (ffffffe000176890)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffe000176890-ffffffe0001768b4: print_ip_sym (STB_LOCAL)
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
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119657a)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8119657a-ffffffff81196592: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118968a)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8118968a-ffffffff811896a2: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119434a)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8119434a-ffffffff81194362: print_ip_sym (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_ip_sym(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a1f3a)
Location: include/linux/kallsyms.h:168
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff811a1f3a-ffffffff811a1f52: print_ip_sym (STB_LOCAL)
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
