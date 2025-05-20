# Function: <code>exclusive_event_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81179f80)
Location: kernel/events/core.c:3650
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81179f80-ffffffff81179f9b: exclusive_event_destroy.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8118aa60)
Location: kernel/events/core.c:3921
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8118aa60-ffffffff8118aa7b: exclusive_event_destroy.isra.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81199b60)
Location: kernel/events/core.c:4018
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81199b60-ffffffff81199b7b: exclusive_event_destroy.isra.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811a1a20)
Location: kernel/events/core.c:4105
Inline: True
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811a1a20-ffffffff811a1a3b: exclusive_event_destroy.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811b5630)
Location: kernel/events/core.c:4039
Inline: True
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811b5630-ffffffff811b564d: exclusive_event_destroy.isra.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811d44d0)
Location: kernel/events/core.c:4374
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811d44d0-ffffffff811d44ec: exclusive_event_destroy.isra.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e4b70)
Location: kernel/events/core.c:4375
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811e4b70-ffffffff811e4b8c: exclusive_event_destroy.isra.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811fbea0)
Location: kernel/events/core.c:4400
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811fbea0-ffffffff811fbeb5: exclusive_event_destroy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81208f70)
Location: kernel/events/core.c:4495
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81208f70-ffffffff81208f85: exclusive_event_destroy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81230410)
Location: kernel/events/core.c:4721
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81230410-ffffffff81230430: exclusive_event_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123a070)
Location: kernel/events/core.c:4800
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8123a070-ffffffff8123a090: exclusive_event_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e8a0)
Location: kernel/events/core.c:4884
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8123e8a0-ffffffff8123e8c0: exclusive_event_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81279380)
Location: kernel/events/core.c:4990
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81279380-ffffffff812793a0: exclusive_event_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cc370)
Location: kernel/events/core.c:4888
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff812cc370-ffffffff812cc3ab: exclusive_event_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81333f40)
Location: kernel/events/core.c:5100
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81333f40-ffffffff81333f7b: exclusive_event_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81364cb0)
Location: kernel/events/core.c:5100
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81364cb0-ffffffff81364ceb: exclusive_event_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138dc80)
Location: kernel/events/core.c:5149
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8138dc80-ffffffff8138dcbb: exclusive_event_destroy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffff800010295258)
Location: kernel/events/core.c:4495
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffff800010295258-ffff800010295298: exclusive_event_destroy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void exclusive_event_destroy(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0034)
Location: kernel/events/core.c:4495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
c04c0034-c04c0098: exclusive_event_destroy (STB_LOCAL)
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
In kernel/events/core.c (c00000000034bd4c)
Location: kernel/events/core.c:4495
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffe0001c9794)
Location: kernel/events/core.c:4495
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81201590)
Location: kernel/events/core.c:4495
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81201590-ffffffff812015a5: exclusive_event_destroy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811f42e0)
Location: kernel/events/core.c:4495
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811f42e0-ffffffff811f42f5: exclusive_event_destroy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811ff360)
Location: kernel/events/core.c:4495
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811ff360-ffffffff811ff375: exclusive_event_destroy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120e3f0)
Location: kernel/events/core.c:4495
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8120e3f0-ffffffff8120e405: exclusive_event_destroy.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
