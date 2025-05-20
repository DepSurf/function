# Function: <code>_perf_event_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117db70)
Location: kernel/events/core.c:1778
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8117db70-ffffffff8117dc66: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118fe50)
Location: kernel/events/core.c:1934
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8118fe50-ffffffff8118feb3: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119fdc0)
Location: kernel/events/core.c:1966
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8119fdc0-ffffffff8119fe23: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a79e0)
Location: kernel/events/core.c:1979
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811a79e0-ffffffff811a7a43: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bb150)
Location: kernel/events/core.c:1972
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811bb150-ffffffff811bb1b3: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811db070)
Location: kernel/events/core.c:2169
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811db070-ffffffff811db0d3: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eb3b0)
Location: kernel/events/core.c:2169
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811eb3b0-ffffffff811eb413: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201e60)
Location: kernel/events/core.c:2171
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81201e60-ffffffff81201ec5: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ed10)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8120ed10-ffffffff8120ed75: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81238bc0)
Location: kernel/events/core.c:2403
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81238bc0-ffffffff81238c25: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242b40)
Location: kernel/events/core.c:2443
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81242b40-ffffffff81242ba5: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81247fa0)
Location: kernel/events/core.c:2445
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81247fa0-ffffffff81248005: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81282300)
Location: kernel/events/core.c:2520
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81282300-ffffffff81282365: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d896e)
Location: kernel/events/core.c:2433
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff812d1af0-ffffffff812d1b5c: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81340f0e)
Location: kernel/events/core.c:2438
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8133a8c0-ffffffff8133a928: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81371e9e)
Location: kernel/events/core.c:2438
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8136b7a0-ffffffff8136b808: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139b20e)
Location: kernel/events/core.c:2476
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81394420-ffffffff81394488: _perf_event_disable (STB_LOCAL)
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
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010298b08)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffff800010298b08-ffff800010298b88: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0ec0)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
c04c0ec0-c04c0f3c: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000345d80)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
c000000000345d80-c000000000345e90: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c8c16)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffe0001c8c16-ffffffe0001c8cf0: _perf_event_disable (STB_LOCAL)
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
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207330)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81207330-ffffffff81207395: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f9f50)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811f9f50-ffffffff811f9fa9: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205100)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81205100-ffffffff81205165: _perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c920)
Location: kernel/events/core.c:2256
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8120c920-ffffffff8120c974: _perf_event_disable (STB_LOCAL)
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
