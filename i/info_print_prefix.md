# Function: <code>info_print_prefix</code>

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
size_t info_print_prefix(const struct printk_info *info, bool syslog, bool time, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81117e30)
Location: kernel/printk/printk.c:1268
Inline: True
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:record_print_text
```
**Symbols:**

```
ffffffff81117e30-ffffffff81117ef8: info_print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info *info, bool syslog, bool time, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118500)
Location: kernel/printk/printk.c:1284
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:record_print_text
```
**Symbols:**

```
ffffffff81118500-ffffffff811185c8: info_print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info *info, bool syslog, bool time, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81138880)
Location: kernel/printk/printk.c:1278
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:record_print_text
```
**Symbols:**

```
ffffffff81138880-ffffffff81138948: info_print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info *info, bool syslog, bool time, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115b280)
Location: kernel/printk/printk.c:1294
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:record_print_text
```
**Symbols:**

```
ffffffff8115b280-ffffffff8115b366: info_print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info *info, bool syslog, bool time, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118d680)
Location: kernel/printk/printk.c:1375
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:record_print_text
```
**Symbols:**

```
ffffffff8118d680-ffffffff8118d766: info_print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info *info, bool syslog, bool time, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119ee20)
Location: kernel/printk/printk.c:1344
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:record_print_text
```
**Symbols:**

```
ffffffff8119ee20-ffffffff8119ef04: info_print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info *info, bool syslog, bool time, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811adf10)
Location: kernel/printk/printk.c:1341
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:record_print_text
```
**Symbols:**

```
ffffffff811adf10-ffffffff811adff4: info_print_prefix (STB_LOCAL)
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
