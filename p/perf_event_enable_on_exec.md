# Function: <code>perf_event_enable_on_exec</code>

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
In kernel/events/core.c (ffffffff8117f95f)
Location: kernel/events/core.c:3157
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff81195a10)
Location: kernel/events/core.c:3383
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff811a5451)
Location: kernel/events/core.c:3454
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff811aca3c)
Location: kernel/events/core.c:3541
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff811c05a0)
Location: kernel/events/core.c:3444
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff811e0993)
Location: kernel/events/core.c:3777
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff811f0df3)
Location: kernel/events/core.c:3772
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff812085d8)
Location: kernel/events/core.c:3792
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff81215947)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_enable_on_exec(int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b880)
Location: kernel/events/core.c:4112
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff8123b880-ffffffff8123ba1d: perf_event_enable_on_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_enable_on_exec(int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245ea0)
Location: kernel/events/core.c:4189
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff81245ea0-ffffffff8124603d: perf_event_enable_on_exec (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81250730)
Location: kernel/events/core.c:4218
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff8128b480)
Location: kernel/events/core.c:4314
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_enable_on_exec(int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dacc0)
Location: kernel/events/core.c:4213
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff812dacc0-ffffffff812daf74: perf_event_enable_on_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_enable_on_exec(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81342fb0)
Location: kernel/events/core.c:4336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff81342fb0-ffffffff81343233: perf_event_enable_on_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_enable_on_exec(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81374010)
Location: kernel/events/core.c:4336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff81374010-ffffffff81374294: perf_event_enable_on_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_enable_on_exec(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139cec0)
Location: kernel/events/core.c:4368
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff8139cec0-ffffffff8139d144: perf_event_enable_on_exec (STB_LOCAL)
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
In kernel/events/core.c (ffff80001029f97c)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (c04cf848)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (c000000000350e90)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffe0001cf1ca)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff8120df98)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff81200d67)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff8120bd37)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff8121ab9e)
Location: kernel/events/core.c:3889
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_event_context *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>int ctxn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
