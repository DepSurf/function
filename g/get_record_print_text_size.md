# Function: <code>get_record_print_text_size</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t get_record_print_text_size(struct printk_info *info, unsigned int line_count, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119dba)
Location: kernel/printk/printk.c:1407
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line_nolock
```
**Symbols:**

```
ffffffff811186a0-ffffffff81118799: get_record_print_text_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119628)
Location: kernel/printk/printk.c:1423
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113906c)
Location: kernel/printk/printk.c:1417
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115ca3c)
Location: kernel/printk/printk.c:1433
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118f53c)
Location: kernel/printk/printk.c:1514
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a0ddc)
Location: kernel/printk/printk.c:1483
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811afecc)
Location: kernel/printk/printk.c:1480
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
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
</ul>
