# Function: <code>_perf_event_refresh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117db00)
Location: kernel/events/core.c:2369
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8117db00-ffffffff8117db2f: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118ffa0)
Location: kernel/events/core.c:2569
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff8118ffa0-ffffffff8118ffcf: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119ff10)
Location: kernel/events/core.c:2633
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff8119ff10-ffffffff8119ff3f: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a7b30)
Location: kernel/events/core.c:2716
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff811a7b30-ffffffff811a7b5d: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bb2a0)
Location: kernel/events/core.c:2628
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff811bb2a0-ffffffff811bb2cd: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811db1c0)
Location: kernel/events/core.c:2837
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff811db1c0-ffffffff811db1ed: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eb500)
Location: kernel/events/core.c:2837
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff811eb500-ffffffff811eb52d: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201f50)
Location: kernel/events/core.c:2855
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff81201f50-ffffffff81201f7d: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ee00)
Location: kernel/events/core.c:2940
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff8120ee00-ffffffff8120ee2d: _perf_event_refresh (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8124017d)
Location: kernel/events/core.c:3109
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
In kernel/events/core.c (ffffffff8124a6cd)
Location: kernel/events/core.c:3153
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
In kernel/events/core.c (ffffffff8124e815)
Location: kernel/events/core.c:3155
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
In kernel/events/core.c (ffffffff8128c685)
Location: kernel/events/core.c:3197
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
In kernel/events/core.c (ffffffff812e129e)
Location: kernel/events/core.c:3108
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
In kernel/events/core.c (ffffffff813497fe)
Location: kernel/events/core.c:3109
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
In kernel/events/core.c (ffffffff8137abfb)
Location: kernel/events/core.c:3109
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
In kernel/events/core.c (ffffffff813a3dfb)
Location: kernel/events/core.c:3147
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
In kernel/events/core.c (ffff80001029df88)
Location: kernel/events/core.c:2940
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0fc8)
Location: kernel/events/core.c:2940
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
c04c0fc8-c04c101c: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000346080)
Location: kernel/events/core.c:2940
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
c000000000346080-c0000000003460e8: _perf_event_refresh (STB_LOCAL)
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
In kernel/events/core.c (ffffffe0001c9110)
Location: kernel/events/core.c:2940
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
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
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207420)
Location: kernel/events/core.c:2940
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff81207420-ffffffff8120744d: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa030)
Location: kernel/events/core.c:2940
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff811fa030-ffffffff811fa05d: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812051f0)
Location: kernel/events/core.c:2940
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff812051f0-ffffffff8120521d: _perf_event_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _perf_event_refresh(struct perf_event *event, int refresh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c9f0)
Location: kernel/events/core.c:2940
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_event_refresh
```
**Symbols:**

```
ffffffff8120c9f0-ffffffff8120ca1d: _perf_event_refresh (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
