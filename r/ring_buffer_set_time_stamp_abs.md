# Function: <code>ring_buffer_set_time_stamp_abs</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117c210)
Location: kernel/trace/ring_buffer.c:1446
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff8117c210-ffffffff8117c218: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189a10)
Location: kernel/trace/ring_buffer.c:1494
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff81189a10-ffffffff81189a18: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196fe0)
Location: kernel/trace/ring_buffer.c:1471
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff81196fe0-ffffffff81196fe8: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a29e0)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff811a29e0-ffffffff811a29e8: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct trace_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b95c0)
Location: kernel/trace/ring_buffer.c:1475
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff811b95c0-ffffffff811b95c8: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct trace_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7000)
Location: kernel/trace/ring_buffer.c:1722
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff811b7000-ffffffff811b7008: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct trace_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7a90)
Location: kernel/trace/ring_buffer.c:1805
Inline: False
```
**Symbols:**

```
ffffffff811b7a90-ffffffff811b7a98: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct trace_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1cc0)
Location: kernel/trace/ring_buffer.c:1805
Inline: False
```
**Symbols:**

```
ffffffff811e1cc0-ffffffff811e1cc8: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct trace_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81218a00)
Location: kernel/trace/ring_buffer.c:1841
Inline: False
```
**Symbols:**

```
ffffffff81218a00-ffffffff81218a10: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct trace_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81262920)
Location: kernel/trace/ring_buffer.c:1903
Inline: False
```
**Symbols:**

```
ffffffff81262920-ffffffff81262930: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct trace_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81279900)
Location: kernel/trace/ring_buffer.c:1901
Inline: False
```
**Symbols:**

```
ffffffff81279900-ffffffff81279910: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct trace_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812943e0)
Location: kernel/trace/ring_buffer.c:1742
Inline: False
```
**Symbols:**

```
ffffffff812943e0-ffffffff812943f0: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
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
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021cef0)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffff80001021cef0-ffff80001021cef8: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045b9ec)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
c045b9ec-c045ba00: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0000000002a0930)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
c0000000002a0930-c0000000002a0938: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017a6e4)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffe00017a6e4-ffffffe00017a6f4: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
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
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119b000)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff8119b000-ffffffff8119b008: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118e080)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff8118e080-ffffffff8118e088: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198dd0)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff81198dd0-ffffffff81198dd8: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ring_buffer_set_time_stamp_abs(struct ring_buffer *buffer, bool abs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a6a40)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
  - kernel/trace/trace.c:tracing_set_time_stamp_abs
```
**Symbols:**

```
ffffffff811a6a40-ffffffff811a6a48: ring_buffer_set_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer *buffer</code> ➡️ <code>struct trace_buffer *buffer</code>
</li>
</ul>
</details>
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
