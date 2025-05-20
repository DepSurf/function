# Function: <code>perf_read_group</code>

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
In kernel/events/core.c (ffffffff8117f1c7)
Location: kernel/events/core.c:3959
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff81190dfd)
Location: kernel/events/core.c:4267
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff811a04dd)
Location: kernel/events/core.c:4364
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff811a7f20)
Location: kernel/events/core.c:4456
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff811bb690)
Location: kernel/events/core.c:4407
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff811db5bb)
Location: kernel/events/core.c:4745
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff811eb8fb)
Location: kernel/events/core.c:4746
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff8120329c)
Location: kernel/events/core.c:4789
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff8120febc)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_read_group(struct perf_event *event, u64 read_format, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81236500)
Location: kernel/events/core.c:5112
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff81236500-ffffffff81236622: perf_read_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_read_group(struct perf_event *event, u64 read_format, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f6c0)
Location: kernel/events/core.c:5191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff8123f6c0-ffffffff8123f7e2: perf_read_group (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81243a16)
Location: kernel/events/core.c:5275
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff8127e337)
Location: kernel/events/core.c:5381
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff812d31bf)
Location: kernel/events/core.c:5279
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff8133c28a)
Location: kernel/events/core.c:5495
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff8136cdda)
Location: kernel/events/core.c:5495
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139601a)
Location: kernel/events/core.c:5572
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffff800010296030)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (c04c7cf4)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (c000000000347b28)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffe0001c85e0)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff812084dc)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff811fa6bc)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff812062ac)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
In kernel/events/core.c (ffffffff81214fec)
Location: kernel/events/core.c:4884
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
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
</ul>
