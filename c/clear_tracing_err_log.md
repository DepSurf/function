# Function: <code>clear_tracing_err_log</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119afb9)
Location: kernel/trace/trace.c:7031
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a6a25)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bf5c5)
Location: kernel/trace/trace.c:7277
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd1f5)
Location: kernel/trace/trace.c:7351
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
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
In kernel/trace/trace.c (ffffffff811bccf5)
Location: kernel/trace/trace.c:7687
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
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
In kernel/trace/trace.c (ffffffff811e77a5)
Location: kernel/trace/trace.c:7851
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
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
In kernel/trace/trace.c (ffffffff8121e327)
Location: kernel/trace/trace.c:7883
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
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
In kernel/trace/trace.c (ffffffff81268a27)
Location: kernel/trace/trace.c:7937
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_tracing_err_log(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127bcc0)
Location: kernel/trace/trace.c:8100
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
**Symbols:**

```
ffffffff8127bcc0-ffffffff8127bd75: clear_tracing_err_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_tracing_err_log(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812969b0)
Location: kernel/trace/trace.c:8136
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
**Symbols:**

```
ffffffff812969b0-ffffffff81296a65: clear_tracing_err_log (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff8000102238bc)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0461130)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a83d0)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017ef70)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f045)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81192095)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ce15)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811aaab5)
Location: kernel/trace/trace.c:7081
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_err_log_open
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
