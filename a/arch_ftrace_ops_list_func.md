# Function: <code>arch_ftrace_ops_list_func</code>

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
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_ftrace_ops_list_func(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120b450)
Location: kernel/trace/ftrace.c:7474
Inline: False
```
**Symbols:**

```
ffffffff8120b450-ffffffff8120b651: arch_ftrace_ops_list_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_ftrace_ops_list_func(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81253e70)
Location: kernel/trace/ftrace.c:7588
Inline: False
```
**Symbols:**

```
ffffffff81253e70-ffffffff81254071: arch_ftrace_ops_list_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void arch_ftrace_ops_list_func(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:7403
Inline: False
```
**Symbols:**

```
ffffffff820db653-ffffffff820db667: arch_ftrace_ops_list_func.cold (STB_LOCAL)
ffffffff8126b450-ffffffff8126b6c5: arch_ftrace_ops_list_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void arch_ftrace_ops_list_func(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:7403
Inline: False
```
**Symbols:**

```
ffffffff821b73bc-ffffffff821b73d0: arch_ftrace_ops_list_func.cold (STB_LOCAL)
ffffffff81285900-ffffffff81285b75: arch_ftrace_ops_list_func (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
