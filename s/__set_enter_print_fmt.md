# Function: <code>__set_enter_print_fmt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81f85272)
Location: kernel/trace/trace_syscalls.c:196
Inline: True
```
**Symbols:**

```
ffffffff81f85272-ffffffff81f8537f: __set_enter_print_fmt.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81fae876)
Location: kernel/trace/trace_syscalls.c:207
Inline: True
```
**Symbols:**

```
ffffffff81fae876-ffffffff81fae987: __set_enter_print_fmt.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81feae9d)
Location: kernel/trace/trace_syscalls.c:207
Inline: True
```
**Symbols:**

```
ffffffff81feae9d-ffffffff81feafae: __set_enter_print_fmt.isra.7 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff820cb8c2)
Location: kernel/trace/trace_syscalls.c:207
Inline: True
```
**Symbols:**

```
ffffffff820cb8c2-ffffffff820cb9be: __set_enter_print_fmt.isra.7 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff826d3f31)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
```
**Symbols:**

```
ffffffff826d3f31-ffffffff826d402d: __set_enter_print_fmt.isra.7 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff826fe6ef)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff826fe6ef-ffffffff826fe7eb: __set_enter_print_fmt.isra.7 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff828b5609)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff828b5609-ffffffff828b5705: __set_enter_print_fmt.isra.7 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff828ce556)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff828ce556-ffffffff828ce65e: __set_enter_print_fmt.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff828d6ab4)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff828d6ab4-ffffffff828d6bbc: __set_enter_print_fmt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff82cf65f2)
Location: kernel/trace/trace_syscalls.c:212
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:set_syscall_print_fmt
  - kernel/trace/trace_syscalls.c:set_syscall_print_fmt
```
**Symbols:**

```
ffffffff82cf65f2-ffffffff82cf66e7: __set_enter_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff82fe30e3)
Location: kernel/trace/trace_syscalls.c:212
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:set_syscall_print_fmt
  - kernel/trace/trace_syscalls.c:set_syscall_print_fmt
```
**Symbols:**

```
ffffffff82fe30e3-ffffffff82fe31d8: __set_enter_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff831ed877)
Location: kernel/trace/trace_syscalls.c:212
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff831ed877-ffffffff831ed968: __set_enter_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff832d24f1)
Location: kernel/trace/trace_syscalls.c:212
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff832d24f1-ffffffff832d25e2: __set_enter_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff83486892)
Location: kernel/trace/trace_syscalls.c:212
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff83486892-ffffffff83486995: __set_enter_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff83eb5dd0)
Location: kernel/trace/trace_syscalls.c:210
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff83eb5dd0-ffffffff83eb5eec: __set_enter_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff836db1c0)
Location: kernel/trace/trace_syscalls.c:210
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff836db1c0-ffffffff836db2d6: __set_enter_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8390d730)
Location: kernel/trace/trace_syscalls.c:210
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff8390d730-ffffffff8390d846: __set_enter_print_fmt (STB_LOCAL)
```
</details>
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
In kernel/trace/trace_syscalls.c (ffff80001144f348)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffff80001144f348-ffff80001144f470: __set_enter_print_fmt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __set_enter_print_fmt(struct syscall_metadata *entry, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c1529a18)
Location: kernel/trace/trace_syscalls.c:208
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
c1529a18-c1529b2c: __set_enter_print_fmt (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (c0000000013762d8)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
c0000000013762d8-c000000001376490: __set_enter_print_fmt.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffe00000f79c)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffe00000f79c-ffffffe00000f8a0: __set_enter_print_fmt.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff828bf965)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff828bf965-ffffffff828bfa6d: __set_enter_print_fmt.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff828b8005)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff828b8005-ffffffff828b810d: __set_enter_print_fmt.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff828d26e8)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff828d26e8-ffffffff828d27f0: __set_enter_print_fmt.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_syscalls.c (ffffffff828d7b09)
Location: kernel/trace/trace_syscalls.c:208
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:init_syscall_trace
  - kernel/trace/trace_syscalls.c:init_syscall_trace
```
**Symbols:**

```
ffffffff828d7b09-ffffffff828d7c11: __set_enter_print_fmt.isra.0 (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
