# Function: <code>perf_event_mmap_event</code>

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
In kernel/events/core.c (ffffffff8118400a)
Location: kernel/events/core.c:6018
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff81195d91)
Location: kernel/events/core.c:6535
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff811a57e3)
Location: kernel/events/core.c:6633
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff811acecc)
Location: kernel/events/core.c:6856
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff811c0a1c)
Location: kernel/events/core.c:6848
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff811e0e1c)
Location: kernel/events/core.c:7222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff811f127c)
Location: kernel/events/core.c:7231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff81208a8c)
Location: kernel/events/core.c:7315
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff81215dfc)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_mmap_event(struct perf_mmap_event *mmap_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81233580)
Location: kernel/events/core.c:7982
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffff81233580-ffffffff8123390f: perf_event_mmap_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_mmap_event(struct perf_mmap_event *mmap_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123d350)
Location: kernel/events/core.c:8164
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffff8123d350-ffffffff8123d6df: perf_event_mmap_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_mmap_event(struct perf_mmap_event *mmap_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241de0)
Location: kernel/events/core.c:8290
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffff81241de0-ffffffff81242144: perf_event_mmap_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_mmap_event(struct perf_mmap_event *mmap_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127c710)
Location: kernel/events/core.c:8414
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffff8127c710-ffffffff8127ca5f: perf_event_mmap_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_mmap_event(struct perf_mmap_event *mmap_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d0f00)
Location: kernel/events/core.c:8319
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffff812d0f00-ffffffff812d1280: perf_event_mmap_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_mmap_event(struct perf_mmap_event *mmap_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813386f0)
Location: kernel/events/core.c:8601
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffff813386f0-ffffffff81338a5c: perf_event_mmap_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_mmap_event(struct perf_mmap_event *mmap_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81369ca0)
Location: kernel/events/core.c:8629
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffff81369ca0-ffffffff8136a00e: perf_event_mmap_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_mmap_event(struct perf_mmap_event *mmap_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81392bb0)
Location: kernel/events/core.c:8710
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffff81392bb0-ffffffff81392ed9: perf_event_mmap_event (STB_LOCAL)
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
In kernel/events/core.c (ffff80001029ff60)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (c04cfe38)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (c0000000003515dc)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffe0001cf5fe)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff8120e44c)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff812011fc)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff8120c1ec)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
In kernel/events/core.c (ffffffff8121b066)
Location: kernel/events/core.c:7431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
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
