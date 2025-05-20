# Function: <code>sync</code>

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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/xmon/xmon.c (c000000000109a04)
Location: arch/powerpc/xmon/xmon.c:323
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_print_symbol
  - arch/powerpc/xmon/xmon.c:xmon_print_symbol
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:scanhex
  - arch/powerpc/xmon/xmon.c:scanhex
  - arch/powerpc/xmon/xmon.c:proccall
  - arch/powerpc/xmon/xmon.c:proccall
  - arch/powerpc/xmon/xmon.c:show_tasks
  - arch/powerpc/xmon/xmon.c:show_tasks
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:dump_opal_msglog
  - arch/powerpc/xmon/xmon.c:dump_opal_msglog
  - arch/powerpc/xmon/xmon.c:dump_log_buf
  - arch/powerpc/xmon/xmon.c:dump_log_buf
  - arch/powerpc/xmon/xmon.c:dump_one_xive
  - arch/powerpc/xmon/xmon.c:dump_one_xive
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:mwrite
  - arch/powerpc/xmon/xmon.c:mwrite
  - arch/powerpc/xmon/xmon.c:mwrite
  - arch/powerpc/xmon/xmon.c:mread
  - arch/powerpc/xmon/xmon.c:mread
  - arch/powerpc/xmon/xmon.c:mread
  - arch/powerpc/xmon/xmon.c:write_spr
  - arch/powerpc/xmon/xmon.c:write_spr
  - arch/powerpc/xmon/xmon.c:read_spr
  - arch/powerpc/xmon/xmon.c:read_spr
  - arch/powerpc/xmon/xmon.c:cacheflush
  - arch/powerpc/xmon/xmon.c:cacheflush
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:get_function_bounds
  - arch/powerpc/xmon/xmon.c:get_function_bounds
  - arch/powerpc/xmon/xmon.c:show_uptime
  - arch/powerpc/xmon/xmon.c:show_uptime
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
