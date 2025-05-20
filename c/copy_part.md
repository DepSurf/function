# Function: <code>copy_part</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_part(unsigned int offset, unsigned int size, void *from, void **kbuf, unsigned int *pos, unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810434f0)
Location: arch/x86/kernel/fpu/xstate.c:1026
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
```
**Symbols:**

```
ffffffff810434f0-ffffffff81043594: copy_part (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_part(struct membuf *to, unsigned int *last, unsigned int offset, unsigned int size, void *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810434f0)
Location: arch/x86/kernel/fpu/xstate.c:1060
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
```
**Symbols:**

```
ffffffff810434f0-ffffffff81043592: copy_part (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct membuf *to</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int *last</code>
</li>
<li>
<b>Param removed. </b>
<code>void **kbuf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *pos</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *count</code>
</li>
<li>
<b>Param reordered. </b>
<code>offset, size, from, kbuf, pos, count</code> ➡️ <code>to, last, offset, size, from</code>
</li>
</ul>
</details>
</li>
</ul>
