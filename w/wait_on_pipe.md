# Function: <code>wait_on_pipe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, bool full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114ba20)
Location: kernel/trace/trace.c:1144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8114ba20-ffffffff8114ba53: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, bool full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81154440)
Location: kernel/trace/trace.c:1379
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81154440-ffffffff81154472: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, bool full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115ea80)
Location: kernel/trace/trace.c:1423
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8115ea80-ffffffff8115eab2: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, bool full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161cb0)
Location: kernel/trace/trace.c:1422
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81161cb0-ffffffff81161ce5: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, bool full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116ed80)
Location: kernel/trace/trace.c:1422
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8116ed80-ffffffff8116edb5: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, bool full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117ddf0)
Location: kernel/trace/trace.c:1433
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8117ddf0-ffffffff8117de24: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118b6f0)
Location: kernel/trace/trace.c:1434
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8118b6f0-ffffffff8118b71e: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198a30)
Location: kernel/trace/trace.c:1613
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81198a30-ffffffff81198a62: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4320)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811a4320-ffffffff811a4352: wait_on_pipe (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811bc194)
Location: kernel/trace/trace.c:1735
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
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
In kernel/trace/trace.c (ffffffff811b9da4)
Location: kernel/trace/trace.c:1885
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
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
In kernel/trace/trace.c (ffffffff811ba441)
Location: kernel/trace/trace.c:1882
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
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
In kernel/trace/trace.c (ffffffff811e4c74)
Location: kernel/trace/trace.c:1896
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
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
In kernel/trace/trace.c (ffffffff8121bfdf)
Location: kernel/trace/trace.c:1887
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
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
In kernel/trace/trace.c (ffffffff81265cc1)
Location: kernel/trace/trace.c:1893
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
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
In kernel/trace/trace.c (ffffffff8127d031)
Location: kernel/trace/trace.c:1945
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1958
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffff81296630-ffffffff812966b7: wait_on_pipe (STB_LOCAL)
ffffffff821b7ac5-ffffffff821b7ae0: wait_on_pipe.cold (STB_LOCAL)
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
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021f2a8)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffff80001021f2a8-ffff80001021f2e8: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045d700)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
c045d700-c045d744: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a2c10)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
c0000000002a2c10-c0000000002a2c70: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017bd4c)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffe00017bd4c-ffffffe00017bd82: wait_on_pipe (STB_LOCAL)
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
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c940)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8119c940-ffffffff8119c972: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118f9a0)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8118f9a0-ffffffff8118f9d2: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119a710)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8119a710-ffffffff8119a742: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wait_on_pipe(struct trace_iterator *iter, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a83b0)
Location: kernel/trace/trace.c:1631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811a83b0-ffffffff811a83e2: wait_on_pipe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool full</code> ➡️ <code>int full</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
