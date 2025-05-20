# Function: <code>ring_buffer_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81180540)
Location: kernel/events/core.c:4530
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
**Symbols:**

```
ffffffff81180540-ffffffff811806ad: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81192290)
Location: kernel/events/core.c:4820
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81192290-ffffffff8119240b: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1a40)
Location: kernel/events/core.c:4917
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811a1a40-ffffffff811a1bbb: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a9260)
Location: kernel/events/core.c:5009
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811a9260-ffffffff811a93ad: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bcac0)
Location: kernel/events/core.c:4959
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811bcac0-ffffffff811bcc0d: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dcc80)
Location: kernel/events/core.c:5316
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811dcc80-ffffffff811dcdd0: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ed080)
Location: kernel/events/core.c:5325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811ed080-ffffffff811ed1d0: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204a70)
Location: kernel/events/core.c:5371
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81204a70-ffffffff81204bc0: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81211660)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81211660-ffffffff812117b0: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123d740)
Location: kernel/events/core.c:5735
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8123d740-ffffffff8123d888: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81247ae0)
Location: kernel/events/core.c:5814
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81247ae0-ffffffff81247c28: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124b9a0)
Location: kernel/events/core.c:5898
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8124b9a0-ffffffff8124bae8: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81286b80)
Location: kernel/events/core.c:6006
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81286b80-ffffffff81286cdd: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812db3b0)
Location: kernel/events/core.c:5904
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff812db3b0-ffffffff812db5a7: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81343670)
Location: kernel/events/core.c:6122
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81343670-ffffffff81343867: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813746d0)
Location: kernel/events/core.c:6122
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff813746d0-ffffffff813748c7: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139da00)
Location: kernel/events/core.c:6195
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8139da00-ffffffff8139dbf7: ring_buffer_attach (STB_LOCAL)
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
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029b990)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffff80001029b990-ffff80001029bb80: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04caf50)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
c04caf50-c04cb0b0: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034ba20)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
c00000000034ba20-c00000000034bbd4: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5fde)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffe0001c5fde-ffffffe0001c60f8: ring_buffer_attach (STB_LOCAL)
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
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209cb0)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81209cb0-ffffffff81209e00: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fca60)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811fca60-ffffffff811fcbb0: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207a50)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81207a50-ffffffff81207ba0: ring_buffer_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ring_buffer_attach(struct perf_event *event, struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812167e0)
Location: kernel/events/core.c:5466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff812167e0-ffffffff81216930: ring_buffer_attach (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer *rb</code> ➡️ <code>struct perf_buffer *rb</code>
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
