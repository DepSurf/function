# Function: <code>prb_rec_init_rd</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119cb2)
Location: kernel/printk/printk_ringbuffer.h:330
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line_nolock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d164)
Location: kernel/printk/printk_ringbuffer.h:330
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119bf6)
Location: kernel/printk/printk_ringbuffer.h:330
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d4f4)
Location: kernel/printk/printk_ringbuffer.h:330
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81139bfc)
Location: kernel/printk/printk_ringbuffer.h:330
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d854)
Location: kernel/printk/printk_ringbuffer.h:330
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115c7c5)
Location: kernel/printk/printk_ringbuffer.h:332
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81160bcc)
Location: kernel/printk/printk_ringbuffer.h:332
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118f2b5)
Location: kernel/printk/printk_ringbuffer.h:332
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8119413c)
Location: kernel/printk/printk_ringbuffer.h:332
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a0b55)
Location: kernel/printk/printk_ringbuffer.h:332
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a599c)
Location: kernel/printk/printk_ringbuffer.h:332
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811afc45)
Location: kernel/printk/printk_ringbuffer.h:332
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b548c)
Location: kernel/printk/printk_ringbuffer.h:332
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
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
