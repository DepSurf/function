# Function: <code>sched_sync_hw_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (ffffffff8110df10)
Location: kernel/time/ntp.c:499
Inline: True
```
**Symbols:**

```
ffffffff8110df10-ffffffff8110dfbf: sched_sync_hw_clock.constprop.6 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff81119900)
Location: kernel/time/ntp.c:499
Inline: True
```
**Symbols:**

```
ffffffff81119900-ffffffff811199b2: sched_sync_hw_clock.constprop.5 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff81124e10)
Location: kernel/time/ntp.c:498
Inline: True
```
**Symbols:**

```
ffffffff81124e10-ffffffff81124ec2: sched_sync_hw_clock.constprop.3 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff8112f870)
Location: kernel/time/ntp.c:500
Inline: True
```
**Symbols:**

```
ffffffff8112f870-ffffffff8112f922: sched_sync_hw_clock.constprop.0 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff8113b7b0)
Location: kernel/time/ntp.c:500
Inline: True
```
**Symbols:**

```
ffffffff8113b7b0-ffffffff8113b862: sched_sync_hw_clock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (ffffffff8114ab30)
Location: kernel/time/ntp.c:500
Inline: True
Direct callers:
  - kernel/time/ntp.c:sync_cmos_clock
```
**Symbols:**

```
ffffffff8114ab30-ffffffff8114abe2: sched_sync_hw_clock.constprop.0 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff81147480)
Location: kernel/time/ntp.c:510
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff811485b0)
Location: kernel/time/ntp.c:510
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff8116c160)
Location: kernel/time/ntp.c:510
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff811a011d)
Location: kernel/time/ntp.c:510
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff811def2d)
Location: kernel/time/ntp.c:510
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff811f340d)
Location: kernel/time/ntp.c:510
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff8120954d)
Location: kernel/time/ntp.c:510
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffff8000101a5c6c)
Location: kernel/time/ntp.c:500
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (c03f0aa4)
Location: kernel/time/ntp.c:500
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (c000000000207970)
Location: kernel/time/ntp.c:500
Inline: True
```
**Symbols:**

```
c000000000207970-c000000000207a70: sched_sync_hw_clock.isra.0 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffe000131e34)
Location: kernel/time/ntp.c:500
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff81133f60)
Location: kernel/time/ntp.c:500
Inline: True
```
**Symbols:**

```
ffffffff81133f60-ffffffff81134012: sched_sync_hw_clock.constprop.0 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff811269c0)
Location: kernel/time/ntp.c:500
Inline: True
```
**Symbols:**

```
ffffffff811269c0-ffffffff81126a72: sched_sync_hw_clock.constprop.0 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff81131c80)
Location: kernel/time/ntp.c:500
Inline: True
```
**Symbols:**

```
ffffffff81131c80-ffffffff81131d32: sched_sync_hw_clock.constprop.0 (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff8113e6a0)
Location: kernel/time/ntp.c:500
Inline: True
```
**Symbols:**

```
ffffffff8113e6a0-ffffffff8113e752: sched_sync_hw_clock.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
