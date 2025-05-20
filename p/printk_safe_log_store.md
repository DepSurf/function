# Function: <code>printk_safe_log_store</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810e4dd0)
Location: kernel/printk/printk_safe.c:83
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810e4dd0-ffffffff810e4e7d: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810ed030)
Location: kernel/printk/printk_safe.c:80
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810ed030-ffffffff810ed0dd: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810f5120)
Location: kernel/printk/printk_safe.c:80
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810f5120-ffffffff810f5201: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811008d0)
Location: kernel/printk/printk_safe.c:80
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff811008d0-ffffffff811009b1: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811090c0)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff811090c0-ffffffff811091a1: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811154a0)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff811154a0-ffffffff81115581: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81120fa0)
Location: kernel/printk/printk_safe.c:69
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81120fa0-ffffffff8112107f: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8111bc00)
Location: kernel/printk/printk_safe.c:71
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8111bc00-ffffffff8111bcdf: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8111c070)
Location: kernel/printk/printk_safe.c:71
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff8111c070-ffffffff8111c14f: printk_safe_log_store (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffff800010176c00)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffff800010176c00-ffff800010176d6c: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c03c8790)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
c03c8790-c03c88c8: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c0000000001d0120)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
c0000000001d0120-c0000000001d02c0: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffe000111b6c)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffe000111b6c-ffffffe000111c3e: printk_safe_log_store (STB_LOCAL)
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
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110da80)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8110da80-ffffffff8110db61: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810fe7e0)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810fe7e0-ffffffff810fe8c1: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110b970)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8110b970-ffffffff8110ba51: printk_safe_log_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81116e80)
Location: kernel/printk/printk_safe.c:68
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81116e80-ffffffff81116f61: printk_safe_log_store (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
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
