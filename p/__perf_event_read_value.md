# Function: <code>__perf_event_read_value</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7760)
Location: kernel/events/core.c:4318
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff811b7760-ffffffff811b784d: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d7160)
Location: kernel/events/core.c:4656
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff811d7160-ffffffff811d724b: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e7590)
Location: kernel/events/core.c:4657
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff811e7590-ffffffff811e767b: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811febd0)
Location: kernel/events/core.c:4700
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff811febd0-ffffffff811fecc2: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120bc30)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff8120bc30-ffffffff8120bd22: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81234f90)
Location: kernel/events/core.c:5023
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff81234f90-ffffffff81235082: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f3e0)
Location: kernel/events/core.c:5102
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff8123f3e0-ffffffff8123f4d2: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812435b0)
Location: kernel/events/core.c:5186
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff812435b0-ffffffff812436a2: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127dec0)
Location: kernel/events/core.c:5292
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff8127dec0-ffffffff8127dfb2: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d2cc0)
Location: kernel/events/core.c:5190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff812d2cc0-ffffffff812d2dc1: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133bd00)
Location: kernel/events/core.c:5402
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff8133bd00-ffffffff8133be01: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136c850)
Location: kernel/events/core.c:5402
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff8136c850-ffffffff8136c951: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81395a60)
Location: kernel/events/core.c:5451
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff81395a60-ffffffff81395b61: __perf_event_read_value (STB_LOCAL)
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
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010295ca8)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffff800010295ca8-ffff800010295da4: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c5d08)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
c04c5d08-c04c5e74: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000343530)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
c000000000343530-c000000000343664: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c6b30)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffe0001c6b30-ffffffe0001c6c02: __perf_event_read_value (STB_LOCAL)
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
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204250)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff81204250-ffffffff81204342: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f6fe0)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff811f6fe0-ffffffff811f70d2: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202020)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff81202020-ffffffff81202112: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 __perf_event_read_value(struct perf_event *event, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81211870)
Location: kernel/events/core.c:4795
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff81211870-ffffffff81211962: __perf_event_read_value (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
