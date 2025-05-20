# Function: <code>tick_setup_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff810fc780)
Location: kernel/time/tick-common.c:177
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_install_replacement
  - kernel/time/tick-common.c:tick_check_new_device
```
**Symbols:**

```
ffffffff810fc780-ffffffff810fc876: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81103ad0)
Location: kernel/time/tick-common.c:177
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81103ad0-ffffffff81103bc6: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8110b1c0)
Location: kernel/time/tick-common.c:177
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff8110b1c0-ffffffff8110b2bf: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff8110d0b0)
Location: kernel/time/tick-common.c:177
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff8110d0b0-ffffffff8110d1af: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81118330)
Location: kernel/time/tick-common.c:177
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81118330-ffffffff8111842f: tick_setup_device (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81124eb0)
Location: kernel/time/tick-common.c:177
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81124eb0-ffffffff81124fb4: tick_setup_device.isra.13 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff811305b0)
Location: kernel/time/tick-common.c:173
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff811305b0-ffffffff811306b4: tick_setup_device.isra.14 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8113b100)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff8113b100-ffffffff8113b203: tick_setup_device.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81146d10)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81146d10-ffffffff81146e13: tick_setup_device.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81156bd0)
Location: kernel/time/tick-common.c:204
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81156bd0-ffffffff81156ccd: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81152cf0)
Location: kernel/time/tick-common.c:205
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81152cf0-ffffffff81152de2: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81153fe0)
Location: kernel/time/tick-common.c:205
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81153fe0-ffffffff811540d2: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81178700)
Location: kernel/time/tick-common.c:205
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81178700-ffffffff811787f0: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff811ad910)
Location: kernel/time/tick-common.c:205
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff811ad910-ffffffff811ada1a: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff811edf10)
Location: kernel/time/tick-common.c:205
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff811edf10-ffffffff811ee01a: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (ffffffff81202640)
Location: kernel/time/tick-common.c:205
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81202640-ffffffff8120274a: tick_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/tick-common.c:205
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81218b30-ffffffff81218d0d: tick_setup_device (STB_LOCAL)
ffffffff821b5ec8-ffffffff821b5ef8: tick_setup_device.cold (STB_LOCAL)
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
In kernel/time/tick-common.c (ffff8000101b1b58)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffff8000101b1b58-ffff8000101b1cac: tick_setup_device.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device *td, struct clock_event_device *newdev, int cpu, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (c03fc398)
Location: kernel/time/tick-common.c:201
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
c03fc398-c03fc4a0: tick_setup_device (STB_LOCAL)
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
In kernel/time/tick-common.c (c000000000216d60)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
c000000000216d60-c000000000216f04: tick_setup_device.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffe00013a38e)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffe00013a38e-ffffffe00013a46a: tick_setup_device.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8113f4c0)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff8113f4c0-ffffffff8113f5c3: tick_setup_device.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81131ff0)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81131ff0-ffffffff811321c0: tick_setup_device.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff8113d1e0)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff8113d1e0-ffffffff8113d2e3: tick_setup_device.isra.0 (STB_LOCAL)
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
In kernel/time/tick-common.c (ffffffff81149cd0)
Location: kernel/time/tick-common.c:201
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_install_replacement
```
**Symbols:**

```
ffffffff81149cd0-ffffffff81149dd3: tick_setup_device.isra.0 (STB_LOCAL)
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
