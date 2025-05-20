# Function: <code>find_first_fitting_seq</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 find_first_fitting_seq(u64 start_seq, u64 max_seq, size_t size, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118cd0)
Location: kernel/printk/printk.c:1447
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:syslog_print_all
```
**Symbols:**

```
ffffffff81118cd0-ffffffff81118e28: find_first_fitting_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 find_first_fitting_seq(u64 start_seq, u64 max_seq, size_t size, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81139780)
Location: kernel/printk/printk.c:1441
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:syslog_print_all
```
**Symbols:**

```
ffffffff81139780-ffffffff811398d8: find_first_fitting_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 find_first_fitting_seq(u64 start_seq, u64 max_seq, size_t size, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115c250)
Location: kernel/printk/printk.c:1457
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:syslog_print_all
```
**Symbols:**

```
ffffffff8115c250-ffffffff8115c433: find_first_fitting_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 find_first_fitting_seq(u64 start_seq, u64 max_seq, size_t size, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118ed20)
Location: kernel/printk/printk.c:1538
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:syslog_print_all
```
**Symbols:**

```
ffffffff8118ed20-ffffffff8118ef03: find_first_fitting_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 find_first_fitting_seq(u64 start_seq, u64 max_seq, size_t size, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a05c0)
Location: kernel/printk/printk.c:1507
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:syslog_print_all
```
**Symbols:**

```
ffffffff811a05c0-ffffffff811a07a3: find_first_fitting_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 find_first_fitting_seq(u64 start_seq, u64 max_seq, size_t size, bool syslog, bool time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811af680)
Location: kernel/printk/printk.c:1504
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:syslog_print_all
```
**Symbols:**

```
ffffffff811af680-ffffffff811af863: find_first_fitting_seq (STB_LOCAL)
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
