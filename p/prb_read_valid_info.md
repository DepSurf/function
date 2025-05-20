# Function: <code>prb_read_valid_info</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
bool prb_read_valid_info(struct printk_ringbuffer *rb, u64 seq, struct printk_info *info, unsigned int *line_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d140)
Location: kernel/printk/printk_ringbuffer.c:1956
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line_nolock
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_poll
```
**Symbols:**

```
ffffffff8111d140-ffffffff8111d196: prb_read_valid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool prb_read_valid_info(struct printk_ringbuffer *rb, u64 seq, struct printk_info *info, unsigned int *line_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d4d0)
Location: kernel/printk/printk_ringbuffer.c:1956
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:devkmsg_poll
```
**Symbols:**

```
ffffffff8111d4d0-ffffffff8111d526: prb_read_valid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool prb_read_valid_info(struct printk_ringbuffer *rb, u64 seq, struct printk_info *info, unsigned int *line_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d830)
Location: kernel/printk/printk_ringbuffer.c:1956
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:devkmsg_poll
```
**Symbols:**

```
ffffffff8113d830-ffffffff8113d886: prb_read_valid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool prb_read_valid_info(struct printk_ringbuffer *rb, u64 seq, struct printk_info *info, unsigned int *line_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff81160b90)
Location: kernel/printk/printk_ringbuffer.c:1967
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:devkmsg_poll
```
**Symbols:**

```
ffffffff81160b90-ffffffff81160bf3: prb_read_valid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool prb_read_valid_info(struct printk_ringbuffer *rb, u64 seq, struct printk_info *info, unsigned int *line_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff81194100)
Location: kernel/printk/printk_ringbuffer.c:1967
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:devkmsg_poll
```
**Symbols:**

```
ffffffff81194100-ffffffff81194163: prb_read_valid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool prb_read_valid_info(struct printk_ringbuffer *rb, u64 seq, struct printk_info *info, unsigned int *line_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811a5960)
Location: kernel/printk/printk_ringbuffer.c:1967
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:devkmsg_poll
```
**Symbols:**

```
ffffffff811a5960-ffffffff811a59c3: prb_read_valid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool prb_read_valid_info(struct printk_ringbuffer *rb, u64 seq, struct printk_info *info, unsigned int *line_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811b5450)
Location: kernel/printk/printk_ringbuffer.c:1967
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:find_first_fitting_seq
  - kernel/printk/printk.c:devkmsg_poll
```
**Symbols:**

```
ffffffff811b5450-ffffffff811b54b3: prb_read_valid_info (STB_GLOBAL)
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
