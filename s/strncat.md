# Function: <code>strncat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f20c0)
Location: lib/string.c:268
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
```
**Symbols:**

```
ffffffff813f20c0-ffffffff813f2106: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438a60)
Location: lib/string.c:268
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
```
**Symbols:**

```
ffffffff81438a60-ffffffff81438aa4: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455a50)
Location: lib/string.c:268
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
```
**Symbols:**

```
ffffffff81455a50-ffffffff81455a94: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8114b001)
Location: include/linux/string.h:271
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
```
**Symbols:**

```
ffffffff818f69f0-ffffffff818f6a38: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81157607)
Location: include/linux/string.h:306
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff8197d3f0-ffffffff8197d438: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811661bf)
Location: include/linux/string.h:307
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff819d9930-ffffffff819d996e: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81172e83)
Location: include/linux/string.h:314
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff81a11b50-ffffffff81a11b8e: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8117fc2b)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff81a810b0-ffffffff81a810eb: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8118ba9b)
Location: include/linux/string.h:342
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff81ab82b0-ffffffff81ab82eb: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811a057b)
Location: include/linux/string.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff815f2ed0-ffffffff815f2f11: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119d63b)
Location: include/linux/string.h:409
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff81617580-ffffffff816175c1: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119e2ab)
Location: include/linux/fortify-string.h:150
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff815fac00-ffffffff815fac3d: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811c8051)
Location: include/linux/fortify-string.h:150
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff816684a0-ffffffff816684dd: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
char *strncat(const char * p, const const char * q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811fbca2)
Location: include/linux/fortify-string.h:224
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:last_cmd_set
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff81782810-ffffffff8178286b: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
char *strncat(const char * p, const const char * q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81243302)
Location: include/linux/fortify-string.h:388
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:last_cmd_set
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff8203f720-ffffffff8203f77b: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
char *strncat(const char * p, const const char * q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8125a434)
Location: include/linux/fortify-string.h:458
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:last_cmd_set
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff820bdba0-ffffffff820bdbfb: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
char *strncat(const char * p, const const char * q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utnonansi.c (ffffffff81a55005)
Location: include/linux/fortify-string.h:403
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff82198420-ffffffff8219847b: strncat (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffff800010202fc0)
Location: include/linux/string.h:342
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
```
**Symbols:**

```
ffff800010d92790-ffff800010d927d8: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c0442084)
Location: include/linux/string.h:342
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_line_info
```
**Symbols:**

```
c0e8edc8-c0e8ee24: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c00000000027d3dc)
Location: include/linux/string.h:342
Inline: True
Inline callers:
  - drivers/video/fbdev/offb.c:offb_init_fb
```
**Symbols:**

```
c000000000ed64e0-c000000000ed6544: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bd26a)
Location: lib/string.c:305
Inline: True
```
**Symbols:**

```
ffffffe0008bd26a-ffffffe0008bd2ac: strncat (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811840bb)
Location: include/linux/string.h:342
Inline: True
```
**Symbols:**

```
ffffffff81a57100-ffffffff81a5713b: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811771fb)
Location: include/linux/string.h:342
Inline: True
```
**Symbols:**

```
ffffffff81a141e0-ffffffff81a1421b: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81181e8b)
Location: include/linux/string.h:342
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff81ac34f0-ffffffff81ac352b: strncat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *strncat(char *p, const char *q, __kernel_size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8118f7ab)
Location: include/linux/string.h:342
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat
```
**Symbols:**

```
ffffffff81acf9c0-ffffffff81acf9fb: strncat (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *p</code>
</li>
<li>
<b>Param added. </b>
<code>const char *q</code>
</li>
<li>
<b>Param removed. </b>
<code>char *dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *src</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t count</code> ➡️ <code>__kernel_size_t count</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *p</code> ➡️ <code>const char * p</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *q</code> ➡️ <code>const const char * q</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *dest</code>
</li>
<li>
<b>Param added. </b>
<code>const char *src</code>
</li>
<li>
<b>Param removed. </b>
<code>char *p</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *q</code>
</li>
<li>
<b>Param type changed. </b>
<code>__kernel_size_t count</code> ➡️ <code>size_t count</code>
</li>
</ul>
</details>
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
