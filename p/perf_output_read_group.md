# Function: <code>perf_output_read_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117b8e7)
Location: kernel/events/core.c:5265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118ce77)
Location: kernel/events/core.c:5582
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119c4b7)
Location: kernel/events/core.c:5680
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a4a8f)
Location: kernel/events/core.c:5769
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b92a0)
Location: kernel/events/core.c:5719
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811da7bb)
Location: kernel/events/core.c:6080
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e9d3b)
Location: kernel/events/core.c:6089
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120048b)
Location: kernel/events/core.c:6167
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
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
In kernel/events/core.c (ffffffff8120d5eb)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_output_read_group(struct perf_output_handle *handle, struct perf_event *event, u64 enabled, u64 running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81235b50)
Location: kernel/events/core.c:6666
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
```
**Symbols:**

```
ffffffff81235b50-ffffffff81235dfc: perf_output_read_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_output_read_group(struct perf_output_handle *handle, struct perf_event *event, u64 enabled, u64 running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ffa0)
Location: kernel/events/core.c:6744
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
```
**Symbols:**

```
ffffffff8123ffa0-ffffffff8124024c: perf_output_read_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_output_read_group(struct perf_output_handle *handle, struct perf_event *event, u64 enabled, u64 running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243f30)
Location: kernel/events/core.c:6855
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
```
**Symbols:**

```
ffffffff81243f30-ffffffff812441da: perf_output_read_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_output_read_group(struct perf_output_handle *handle, struct perf_event *event, u64 enabled, u64 running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127e8a0)
Location: kernel/events/core.c:6979
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
```
**Symbols:**

```
ffffffff8127e8a0-ffffffff8127ebbf: perf_output_read_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_output_read_group(struct perf_output_handle *handle, struct perf_event *event, u64 enabled, u64 running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d3f60)
Location: kernel/events/core.c:6884
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
```
**Symbols:**

```
ffffffff812d3f60-ffffffff812d42b2: perf_output_read_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_output_read_group(struct perf_output_handle *handle, struct perf_event *event, u64 enabled, u64 running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813362a0)
Location: kernel/events/core.c:7143
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
```
**Symbols:**

```
ffffffff813362a0-ffffffff8133660d: perf_output_read_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_output_read_group(struct perf_output_handle *handle, struct perf_event *event, u64 enabled, u64 running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366fe0)
Location: kernel/events/core.c:7152
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
```
**Symbols:**

```
ffffffff81366fe0-ffffffff8136734d: perf_output_read_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_output_read_group(struct perf_output_handle *handle, struct perf_event *event, u64 enabled, u64 running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81390150)
Location: kernel/events/core.c:7225
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
```
**Symbols:**

```
ffffffff81390150-ffffffff813904bd: perf_output_read_group (STB_LOCAL)
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
In kernel/events/core.c (ffff800010294a20)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
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
In kernel/events/core.c (c04c64ac)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
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
In kernel/events/core.c (c000000000344bb4)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
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
In kernel/events/core.c (ffffffe0001c766a)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
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
In kernel/events/core.c (ffffffff81205c0b)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
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
In kernel/events/core.c (ffffffff811f898b)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
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
In kernel/events/core.c (ffffffff812039db)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
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
In kernel/events/core.c (ffffffff8121360b)
Location: kernel/events/core.c:6283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
