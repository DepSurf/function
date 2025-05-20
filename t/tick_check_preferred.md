# Function: <code>tick_check_preferred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff810fc600)
Location: kernel/time/tick-common.c:263
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_new_device
```
**Symbols:**

```
ffffffff810fc600-ffffffff810fc68d: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81103950)
Location: kernel/time/tick-common.c:263
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81103950-ffffffff811039dd: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8110b040)
Location: kernel/time/tick-common.c:263
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8110b040-ffffffff8110b0ce: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8110cf30)
Location: kernel/time/tick-common.c:263
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8110cf30-ffffffff8110cfb2: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff811181b0)
Location: kernel/time/tick-common.c:263
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff811181b0-ffffffff81118232: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81124d20)
Location: kernel/time/tick-common.c:263
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81124d20-ffffffff81124db1: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81130420)
Location: kernel/time/tick-common.c:259
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81130420-ffffffff811304b1: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8113af70)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8113af70-ffffffff8113b001: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81146b80)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81146b80-ffffffff81146c11: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81156a50)
Location: kernel/time/tick-common.c:304
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81156a50-ffffffff81156adf: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81152b70)
Location: kernel/time/tick-common.c:304
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81152b70-ffffffff81152bff: tick_check_preferred (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8115420b)
Location: kernel/time/tick-common.c:304
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
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
In kernel/time/tick-common.c (ffffffff81178978)
Location: kernel/time/tick-common.c:304
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
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
In kernel/time/tick-common.c (ffffffff811adbc2)
Location: kernel/time/tick-common.c:304
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
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
In kernel/time/tick-common.c (ffffffff811ee1e2)
Location: kernel/time/tick-common.c:304
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
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
In kernel/time/tick-common.c (ffffffff81202912)
Location: kernel/time/tick-common.c:303
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
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
In kernel/time/tick-common.c (ffffffff81218ed2)
Location: kernel/time/tick-common.c:303
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
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
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffff8000101b1700)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffff8000101b1700-ffff8000101b17d8: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (c03fc168)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
c03fc168-c03fc218: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (c000000000216a50)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
c000000000216a50-c000000000216b84: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffe000139f70)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffe000139f70-ffffffe00013a004: tick_check_preferred (STB_LOCAL)
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
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8113f330)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8113f330-ffffffff8113f3c1: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81131e60)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81131e60-ffffffff81131ef1: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8113d050)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8113d050-ffffffff8113d0e1: tick_check_preferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device *curdev, struct clock_event_device *newdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81149b40)
Location: kernel/time/tick-common.c:301
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81149b40-ffffffff81149bd1: tick_check_preferred (STB_LOCAL)
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
