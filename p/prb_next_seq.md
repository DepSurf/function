# Function: <code>prb_next_seq</code>

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
u64 prb_next_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d200)
Location: kernel/printk/printk_ringbuffer.c:2006
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8111d200-ffffffff8111d261: prb_next_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 prb_next_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d590)
Location: kernel/printk/printk_ringbuffer.c:2006
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8111d590-ffffffff8111d5ec: prb_next_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 prb_next_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d8f0)
Location: kernel/printk/printk_ringbuffer.c:2006
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8113d8f0-ffffffff8113d94c: prb_next_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 prb_next_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff81160c60)
Location: kernel/printk/printk_ringbuffer.c:2017
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff81160c60-ffffffff81160d05: prb_next_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 prb_next_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811941f0)
Location: kernel/printk/printk_ringbuffer.c:2017
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff811941f0-ffffffff81194295: prb_next_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 prb_next_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811a5a50)
Location: kernel/printk/printk_ringbuffer.c:2017
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff811a5a50-ffffffff811a5af5: prb_next_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 prb_next_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811b5540)
Location: kernel/printk/printk_ringbuffer.c:2017
Inline: False
Direct callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff811b5540-ffffffff811b55e5: prb_next_seq (STB_GLOBAL)
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
