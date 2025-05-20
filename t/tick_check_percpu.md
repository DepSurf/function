# Function: <code>tick_check_percpu</code>

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
In kernel/time/tick-common.c (ffffffff810fc560)
Location: kernel/time/tick-common.c:247
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_new_device
```
**Symbols:**

```
ffffffff810fc560-ffffffff810fc5fa: tick_check_percpu.isra.8 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff811038a0)
Location: kernel/time/tick-common.c:247
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff811038a0-ffffffff81103942: tick_check_percpu.isra.8 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8110af90)
Location: kernel/time/tick-common.c:247
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8110af90-ffffffff8110b034: tick_check_percpu.isra.8 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8110ce90)
Location: kernel/time/tick-common.c:247
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8110ce90-ffffffff8110cf2f: tick_check_percpu.isra.8 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81118110)
Location: kernel/time/tick-common.c:247
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81118110-ffffffff811181af: tick_check_percpu.isra.8 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81124c70)
Location: kernel/time/tick-common.c:247
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81124c70-ffffffff81124d19: tick_check_percpu.isra.11 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81130370)
Location: kernel/time/tick-common.c:243
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81130370-ffffffff81130419: tick_check_percpu.isra.12 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8113aec0)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8113aec0-ffffffff8113af6c: tick_check_percpu.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81146ad0)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81146ad0-ffffffff81146b7c: tick_check_percpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tick_check_percpu(struct clock_event_device *curdev, struct clock_event_device *newdev, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81156990)
Location: kernel/time/tick-common.c:288
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81156990-ffffffff81156a43: tick_check_percpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tick_check_percpu(struct clock_event_device *curdev, struct clock_event_device *newdev, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81152ab0)
Location: kernel/time/tick-common.c:288
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81152ab0-ffffffff81152b63: tick_check_percpu (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8115416d)
Location: kernel/time/tick-common.c:288
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
In kernel/time/tick-common.c (ffffffff811788c4)
Location: kernel/time/tick-common.c:288
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
In kernel/time/tick-common.c (ffffffff811adb10)
Location: kernel/time/tick-common.c:288
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
In kernel/time/tick-common.c (ffffffff811ee130)
Location: kernel/time/tick-common.c:288
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
In kernel/time/tick-common.c (ffffffff81202860)
Location: kernel/time/tick-common.c:287
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
In kernel/time/tick-common.c (ffffffff81218e20)
Location: kernel/time/tick-common.c:287
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-common.c (ffff8000101b15b8)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffff8000101b15b8-ffff8000101b1700: tick_check_percpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tick_check_percpu(struct clock_event_device *curdev, struct clock_event_device *newdev, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (c03fc0b4)
Location: kernel/time/tick-common.c:285
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
c03fc0b4-c03fc168: tick_check_percpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-common.c (c000000000216900)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
c000000000216900-c000000000216a44: tick_check_percpu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-common.c (ffffffe00013a004)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffe00013a004-ffffffe00013a0c4: tick_check_percpu.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8113f280)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8113f280-ffffffff8113f32c: tick_check_percpu.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81131db0)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81131db0-ffffffff81131e5c: tick_check_percpu.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8113cfa0)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff8113cfa0-ffffffff8113d04c: tick_check_percpu.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81149a90)
Location: kernel/time/tick-common.c:285
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
```
**Symbols:**

```
ffffffff81149a90-ffffffff81149b3c: tick_check_percpu.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
