# Function: <code>uprobe_perf_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int uprobe_perf_close(struct trace_uprobe *tu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8116f8e0)
Location: kernel/trace/trace_uprobe.c:1037
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff8116f8e0-ffffffff8116f9a2: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int uprobe_perf_close(struct trace_uprobe *tu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8117cfd0)
Location: kernel/trace/trace_uprobe.c:1037
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff8117cfd0-ffffffff8117d092: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int uprobe_perf_close(struct trace_uprobe *tu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81188be0)
Location: kernel/trace/trace_uprobe.c:1037
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff81188be0-ffffffff81188ca2: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int uprobe_perf_close(struct trace_uprobe *tu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8118b7f0)
Location: kernel/trace/trace_uprobe.c:1040
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff8118b7f0-ffffffff8118b8b8: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int uprobe_perf_close(struct trace_uprobe *tu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81199290)
Location: kernel/trace/trace_uprobe.c:1040
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff81199290-ffffffff81199358: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int uprobe_perf_close(struct trace_uprobe *tu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811ae990)
Location: kernel/trace/trace_uprobe.c:1023
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811ae990-ffffffff811aea5f: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int uprobe_perf_close(struct trace_uprobe *tu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811bd020)
Location: kernel/trace/trace_uprobe.c:1025
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811bd020-ffffffff811bd0ef: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int uprobe_perf_close(struct trace_uprobe *tu, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811cc6d0)
Location: kernel/trace/trace_uprobe.c:1047
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811cc6d0-ffffffff811cc79d: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d83f0)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
```
**Symbols:**

```
ffffffff811d83f0-ffffffff811d8506: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f5070)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
```
**Symbols:**

```
ffffffff811f5070-ffffffff811f51de: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f3a00)
Location: kernel/trace/trace_uprobe.c:1270
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
```
**Symbols:**

```
ffffffff811f3a00-ffffffff811f3b6e: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4840)
Location: kernel/trace/trace_uprobe.c:1275
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811f4840-ffffffff811f49ae: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81225bf0)
Location: kernel/trace/trace_uprobe.c:1275
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff81225bf0-ffffffff81225d5e: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81266720)
Location: kernel/trace/trace_uprobe.c:1267
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff81266720-ffffffff812668b5: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812b85d0)
Location: kernel/trace/trace_uprobe.c:1273
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff812b85d0-ffffffff812b8765: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812dbc00)
Location: kernel/trace/trace_uprobe.c:1273
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff812dbc00-ffffffff812dbda1: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812f9ce0)
Location: kernel/trace/trace_uprobe.c:1269
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff812f9ce0-ffffffff812f9e81: uprobe_perf_close (STB_LOCAL)
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
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffff800010259490)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
```
**Symbols:**

```
ffff800010259490-ffff8000102595f0: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048b610)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
```
**Symbols:**

```
c048b610-c048b76c: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fb9a0)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
```
**Symbols:**

```
c0000000002fb9a0-c0000000002fbb34: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d0a10)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
```
**Symbols:**

```
ffffffff811d0a10-ffffffff811d0b26: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811c37e0)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
```
**Symbols:**

```
ffffffff811c37e0-ffffffff811c38f6: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811ce7e0)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
```
**Symbols:**

```
ffffffff811ce7e0-ffffffff811ce8f6: uprobe_perf_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uprobe_perf_close(struct trace_event_call *call, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811dca40)
Location: kernel/trace/trace_uprobe.c:1257
Inline: False
```
**Symbols:**

```
ffffffff811dca40-ffffffff811dcb58: uprobe_perf_close (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_event_call *call</code>
</li>
<li>
<b>Param removed. </b>
<code>struct trace_uprobe *tu</code>
</li>
</ul>
</details>
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
