# Function: <code>function_graph_enter</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a0440)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811a0440-ffffffff811a055a: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811ae2c0)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811ae2c0-ffffffff811ae3da: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b9a30)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811b9a30-ffffffff811b9b4a: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d2a00)
Location: kernel/trace/fgraph.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811d2a00-ffffffff811d2ad2: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811cfb70)
Location: kernel/trace/fgraph.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811cfb70-ffffffff811cfc42: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d0ca0)
Location: kernel/trace/fgraph.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811d0ca0-ffffffff811d0ddd: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/fgraph.c (0)
Location: kernel/trace/fgraph.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff81cb6176-ffffffff81cb618a: function_graph_enter.cold (STB_LOCAL)
ffffffff811fd900-ffffffff811fda57: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff81238240)
Location: kernel/trace/fgraph.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff81238240-ffffffff81238367: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff81285060)
Location: kernel/trace/fgraph.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff81285060-ffffffff81285187: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812a1d00)
Location: kernel/trace/fgraph.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff812a1d00-ffffffff812a1e27: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812bd430)
Location: kernel/trace/fgraph.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff812bd430-ffffffff812bd557: function_graph_enter (STB_GLOBAL)
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
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffff800010238110)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/arm64/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffff800010238110-ffff800010238280: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0473c9c)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/arm/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
c0473c9c-c0473e2c: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0000000002c4390)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/powerpc/kernel/trace/ftrace.c:prepare_ftrace_return
  - arch/powerpc/kernel/trace/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
c0000000002c4390-c0000000002c452c: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffe00018f0e0)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/riscv/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffe00018f0e0-ffffffe00018f1d6: function_graph_enter (STB_GLOBAL)
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
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b2050)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811b2050-ffffffff811b216a: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a4e60)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811a4e60-ffffffff811a4f7a: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811afe20)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811afe20-ffffffff811aff3a: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int function_graph_enter(long unsigned int ret, long unsigned int func, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811bde90)
Location: kernel/trace/fgraph.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811bde90-ffffffff811bdfaa: function_graph_enter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
