# Function: <code>account_event</code>

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
In kernel/events/core.c (ffffffff8117a600)
Location: kernel/events/core.c:7822
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff8117a600-ffffffff8117a6d0: account_event.part.81 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81190802)
Location: kernel/events/core.c:8898
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff8119f6d0)
Location: kernel/events/core.c:9092
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff811a611e)
Location: kernel/events/core.c:9310
Inline: True
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
In kernel/events/core.c (ffffffff811b9d14)
Location: kernel/events/core.c:9332
Inline: True
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
In kernel/events/core.c (ffffffff811d9373)
Location: kernel/events/core.c:9854
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff811e97b3)
Location: kernel/events/core.c:9897
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff81202cc1)
Location: kernel/events/core.c:10225
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff8120fb76)
Location: kernel/events/core.c:10341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81239ed0)
Location: kernel/events/core.c:10920
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81239ed0-ffffffff8123a0ba: account_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243550)
Location: kernel/events/core.c:11202
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81243550-ffffffff81243752: account_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248500)
Location: kernel/events/core.c:11345
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81248500-ffffffff81248716: account_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81282b50)
Location: kernel/events/core.c:11457
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81282b50-ffffffff81282dc3: account_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812ce740)
Location: kernel/events/core.c:11393
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff812ce740-ffffffff812ce9e4: account_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81336890)
Location: kernel/events/core.c:11696
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81336890-ffffffff81336acd: account_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81367650)
Location: kernel/events/core.c:11736
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81367650-ffffffff8136788d: account_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:11820
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81394a00-ffffffff81394c9c: account_event (STB_LOCAL)
ffffffff821bdf94-ffffffff821bdfa9: account_event.cold (STB_LOCAL)
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
In kernel/events/core.c (ffff8000102979b8)
Location: kernel/events/core.c:10341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void account_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c6d78)
Location: kernel/events/core.c:10341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
c04c6d78-c04c7128: account_event (STB_LOCAL)
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
In kernel/events/core.c (c000000000347694)
Location: kernel/events/core.c:10341
Inline: True
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
In kernel/events/core.c (ffffffe0001ca158)
Location: kernel/events/core.c:10341
Inline: True
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
In kernel/events/core.c (ffffffff81208196)
Location: kernel/events/core.c:10341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff811fb2bd)
Location: kernel/events/core.c:10341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff81205f66)
Location: kernel/events/core.c:10341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
In kernel/events/core.c (ffffffff81214e1d)
Location: kernel/events/core.c:10341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
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
