# Function: <code>xmon_print_symbol</code>

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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xmon_print_symbol(long unsigned int address, const char *mid, const char *after);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/xmon/xmon.c (c0000000001098e0)
Location: arch/powerpc/xmon/xmon.c:3531
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:print_address
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:xmon_core
```
**Symbols:**

```
c0000000001098e0-c000000000109a4c: xmon_print_symbol (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
