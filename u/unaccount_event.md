# Function: <code>unaccount_event</code>

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
In kernel/events/core.c (ffffffff811806c6)
Location: kernel/events/core.c:3580
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81192426)
Location: kernel/events/core.c:3834
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811a1bd6)
Location: kernel/events/core.c:3931
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811a93c6)
Location: kernel/events/core.c:4016
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811bcc26)
Location: kernel/events/core.c:3950
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811dcde6)
Location: kernel/events/core.c:4285
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811ed1e6)
Location: kernel/events/core.c:4286
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81204bd6)
Location: kernel/events/core.c:4307
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff812117c6)
Location: kernel/events/core.c:4402
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unaccount_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81239d00)
Location: kernel/events/core.c:4626
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81239d00-ffffffff81239eca: unaccount_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unaccount_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243360)
Location: kernel/events/core.c:4703
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81243360-ffffffff81243542: unaccount_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unaccount_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248300)
Location: kernel/events/core.c:4785
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81248300-ffffffff812484f6: unaccount_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unaccount_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81282660)
Location: kernel/events/core.c:4891
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81282660-ffffffff812828ac: unaccount_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unaccount_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cdf80)
Location: kernel/events/core.c:4789
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff812cdf80-ffffffff812ce200: unaccount_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unaccount_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81335970)
Location: kernel/events/core.c:5003
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81335970-ffffffff81335b89: unaccount_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unaccount_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813666c0)
Location: kernel/events/core.c:5003
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff813666c0-ffffffff813668d9: unaccount_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void unaccount_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:5052
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81394770-ffffffff813949e4: unaccount_event (STB_LOCAL)
ffffffff821bdf7f-ffffffff821bdf94: unaccount_event.cold (STB_LOCAL)
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
In kernel/events/core.c (ffff80001029bb98)
Location: kernel/events/core.c:4402
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (c04cb0c8)
Location: kernel/events/core.c:4402
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (c00000000034bc10)
Location: kernel/events/core.c:4402
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
In kernel/events/core.c (ffffffe0001c96da)
Location: kernel/events/core.c:4402
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209e16)
Location: kernel/events/core.c:4402
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811fcbc6)
Location: kernel/events/core.c:4402
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81207bb6)
Location: kernel/events/core.c:4402
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81216946)
Location: kernel/events/core.c:4402
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
