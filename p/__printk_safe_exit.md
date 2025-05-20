# Function: <code>__printk_safe_exit</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810e4fd0)
Location: kernel/printk/printk_safe.c:359
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff810e4fd0-ffffffff810e4fe2: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810ed230)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff810ed230-ffffffff810ed242: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810f5500)
Location: kernel/printk/printk_safe.c:368
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff810f5500-ffffffff810f5512: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81100ca0)
Location: kernel/printk/printk_safe.c:368
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff81100ca0-ffffffff81100cb2: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81109440)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff81109440-ffffffff81109452: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81115810)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff81115810-ffffffff81115822: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811211b0)
Location: kernel/printk/printk_safe.c:357
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff811211b0-ffffffff811211c2: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8111be30)
Location: kernel/printk/printk_safe.c:365
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8111be30-ffffffff8111be42: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8111c20c)
Location: kernel/printk/printk_safe.c:355
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8111c390-ffffffff8111c3a2: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8113c440)
Location: kernel/printk/printk_safe.c:24
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff8113c440-ffffffff8113c452: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8115f5d0)
Location: kernel/printk/printk_safe.c:24
Inline: False
Direct callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff8115f5d0-ffffffff8115f5e6: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81192900)
Location: kernel/printk/printk_safe.c:24
Inline: False
Direct callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff81192900-ffffffff81192916: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811a41a0)
Location: kernel/printk/printk_safe.c:24
Inline: False
Direct callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/printk/printk.c:console_emit_next_record
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - mm/page_alloc.c:__build_all_zonelists
```
**Symbols:**

```
ffffffff811a41a0-ffffffff811a41b6: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811b37d0)
Location: kernel/printk/printk_safe.c:24
Inline: False
Direct callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/printk/printk.c:console_emit_next_record
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - mm/page_alloc.c:__build_all_zonelists
  - lib/stackdepot.c:stack_depot_save_flags
```
**Symbols:**

```
ffffffff811b37d0-ffffffff811b37e6: __printk_safe_exit (STB_GLOBAL)
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
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffff800010176f88)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffff800010176f88-ffff800010176fc4: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c03c8d0c)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
c03c8d0c-c03c8d48: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c0000000001d08b0)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
c0000000001d08b0-c0000000001d0908: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffe000111f36)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffe000111f36-ffffffe000111f7e: __printk_safe_exit (STB_GLOBAL)
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
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110ddf0)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8110ddf0-ffffffff8110de02: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810feb50)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff810feb50-ffffffff810feb62: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110bce0)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8110bce0-ffffffff8110bcf2: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __printk_safe_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811171f0)
Location: kernel/printk/printk_safe.c:356
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff811171f0-ffffffff81117202: __printk_safe_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
