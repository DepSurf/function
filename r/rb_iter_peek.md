# Function: <code>rb_iter_peek</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811496a0)
Location: kernel/trace/ring_buffer.c:3783
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
  - kernel/trace/ring_buffer.c:ring_buffer_read
```
**Symbols:**

```
ffffffff811496a0-ffffffff8114980a: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81152150)
Location: kernel/trace/ring_buffer.c:3778
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff81152150-ffffffff811522b3: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c500)
Location: kernel/trace/ring_buffer.c:3747
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff8115c500-ffffffff8115c663: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115f580)
Location: kernel/trace/ring_buffer.c:3761
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff8115f580-ffffffff8115f6c7: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116c640)
Location: kernel/trace/ring_buffer.c:3753
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff8116c640-ffffffff8116c78d: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117b0f0)
Location: kernel/trace/ring_buffer.c:3907
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff8117b0f0-ffffffff8117b269: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811886a0)
Location: kernel/trace/ring_buffer.c:3972
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff811886a0-ffffffff81188827: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195310)
Location: kernel/trace/ring_buffer.c:3949
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff81195310-ffffffff811954a6: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a1200)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff811a1200-ffffffff811a138a: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b64d0)
Location: kernel/trace/ring_buffer.c:4031
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff811b64d0-ffffffff811b66b7: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3f80)
Location: kernel/trace/ring_buffer.c:4577
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff811b3f80-ffffffff811b4167: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4ef0)
Location: kernel/trace/ring_buffer.c:4684
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff811b4ef0-ffffffff811b50d7: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811df150)
Location: kernel/trace/ring_buffer.c:4684
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff811df150-ffffffff811df337: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81216840)
Location: kernel/trace/ring_buffer.c:4725
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff81216840-ffffffff81216a6e: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125fd30)
Location: kernel/trace/ring_buffer.c:4831
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff8125fd30-ffffffff8125ff5e: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81277030)
Location: kernel/trace/ring_buffer.c:4838
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff81277030-ffffffff8127721f: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81291a90)
Location: kernel/trace/ring_buffer.c:4744
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff81291a90-ffffffff81291c7f: rb_iter_peek (STB_LOCAL)
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
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021bb10)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffff80001021bb10-ffff80001021bcac: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c04591f4)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
c04591f4-c0459430: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029d9c0)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
c00000000029d9c0-c00000000029dc14: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001798a4)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffe0001798a4-ffffffe0001799e8: rb_iter_peek (STB_LOCAL)
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
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81199820)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff81199820-ffffffff811999aa: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118ceb0)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff8118ceb0-ffffffff8118d03a: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811975f0)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff811975f0-ffffffff8119777a: rb_iter_peek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_peek(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a5220)
Location: kernel/trace/ring_buffer.c:3950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
```
**Symbols:**

```
ffffffff811a5220-ffffffff811a53aa: rb_iter_peek (STB_LOCAL)
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
