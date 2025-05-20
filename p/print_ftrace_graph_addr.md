# Function: <code>print_ftrace_graph_addr</code>

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
In arch/x86/kernel/dumpstack.c (ffffffff81031c30)
Location: arch/x86/kernel/dumpstack.c:43
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:print_context_stack
  - arch/x86/kernel/dumpstack.c:print_context_stack_bp
Direct callers:
  - arch/x86/kernel/dumpstack.c:print_context_stack
  - arch/x86/kernel/dumpstack.c:print_context_stack_bp
```
**Symbols:**

```
ffffffff81031c30-ffffffff81031c75: print_ftrace_graph_addr.isra.1.part.2 (STB_LOCAL)
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
In arch/x86/kernel/dumpstack.c (ffffffff81030f0c)
Location: arch/x86/kernel/dumpstack.c:43
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:print_context_stack_bp
  - arch/x86/kernel/dumpstack.c:print_context_stack
Direct callers:
  - arch/x86/kernel/dumpstack.c:print_context_stack_bp
  - arch/x86/kernel/dumpstack.c:print_context_stack
```
**Symbols:**

```
ffffffff81030d40-ffffffff81030d83: print_ftrace_graph_addr.isra.1.part.2 (STB_LOCAL)
```
</details>
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
