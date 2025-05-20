# Function: <code>record_print_text</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
size_t record_print_text(struct printk_record *r, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1306
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line_nolock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
```
**Symbols:**

```
ffffffff81117f00-ffffffff81118051: record_print_text (STB_LOCAL)
ffffffff81be10f5-ffffffff81be1101: record_print_text.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
size_t record_print_text(struct printk_record *r, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1322
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
```
**Symbols:**

```
ffffffff811185d0-ffffffff81118722: record_print_text (STB_LOCAL)
ffffffff81bd3176-ffffffff81bd3182: record_print_text.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t record_print_text(struct printk_record *r, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1316
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
```
**Symbols:**

```
ffffffff81138950-ffffffff81138aa2: record_print_text (STB_LOCAL)
ffffffff81cabfc2-ffffffff81cabfce: record_print_text.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t record_print_text(struct printk_record *r, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1332
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
```
**Symbols:**

```
ffffffff8115b370-ffffffff8115b4df: record_print_text (STB_LOCAL)
ffffffff81e5c4a0-ffffffff81e5c4ac: record_print_text.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t record_print_text(struct printk_record *r, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118de50)
Location: kernel/printk/printk.c:1413
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
```
**Symbols:**

```
ffffffff8118de50-ffffffff8118dfcd: record_print_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t record_print_text(struct printk_record *r, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119f7b0)
Location: kernel/printk/printk.c:1382
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
```
**Symbols:**

```
ffffffff8119f7b0-ffffffff8119f92d: record_print_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t record_print_text(struct printk_record *r, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811ae7e0)
Location: kernel/printk/printk.c:1379
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
```
**Symbols:**

```
ffffffff811ae7e0-ffffffff811ae95d: record_print_text (STB_LOCAL)
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
