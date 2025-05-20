# Function: <code>perf_remove_from_owner</code>

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
In kernel/events/core.c (ffffffff811808f1)
Location: kernel/events/core.c:3758
Inline: True
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
In kernel/events/core.c (ffffffff81192baf)
Location: kernel/events/core.c:4027
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff811a238f)
Location: kernel/events/core.c:4124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff811a9c8e)
Location: kernel/events/core.c:4211
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff811bd578)
Location: kernel/events/core.c:4145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff811dd7c6)
Location: kernel/events/core.c:4483
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff811edbc6)
Location: kernel/events/core.c:4484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff81205616)
Location: kernel/events/core.c:4518
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff812129a6)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff8123e599)
Location: kernel/events/core.c:4841
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff81248989)
Location: kernel/events/core.c:4920
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_remove_from_owner(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812441e0)
Location: kernel/events/core.c:5004
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff812441e0-ffffffff812442d7: perf_remove_from_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_remove_from_owner(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127ebc0)
Location: kernel/events/core.c:5110
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8127ebc0-ffffffff8127ecb7: perf_remove_from_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_remove_from_owner(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d3670)
Location: kernel/events/core.c:5008
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff812d3670-ffffffff812d37c9: perf_remove_from_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_remove_from_owner(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133b300)
Location: kernel/events/core.c:5223
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8133b300-ffffffff8133b459: perf_remove_from_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_remove_from_owner(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136d1b0)
Location: kernel/events/core.c:5223
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8136d1b0-ffffffff8136d309: perf_remove_from_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_remove_from_owner(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81396400)
Location: kernel/events/core.c:5272
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81396400-ffffffff81396559: perf_remove_from_owner (STB_LOCAL)
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
In kernel/events/core.c (ffff80001029cdf0)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (c04cc3ec)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (c00000000034d690)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffe0001cb582)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff8120aff6)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff811fddd0)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff81208d96)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
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
In kernel/events/core.c (ffffffff81217b1d)
Location: kernel/events/core.c:4613
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
