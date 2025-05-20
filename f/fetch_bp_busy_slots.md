# Function: <code>fetch_bp_busy_slots</code>

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
In kernel/events/hw_breakpoint.c (ffffffff81186a50)
Location: kernel/events/hw_breakpoint.c:145
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff81198f10)
Location: kernel/events/hw_breakpoint.c:145
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff811a88f0)
Location: kernel/events/hw_breakpoint.c:145
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff811b009f)
Location: kernel/events/hw_breakpoint.c:145
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff811c3bb8)
Location: kernel/events/hw_breakpoint.c:145
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff811e3deb)
Location: kernel/events/hw_breakpoint.c:146
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff811f429b)
Location: kernel/events/hw_breakpoint.c:146
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8120bf8c)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8121926c)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff81244cd0)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff81244cd0-ffffffff81244e42: fetch_bp_busy_slots.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8124f320)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff8124f320-ffffffff8124f492: fetch_bp_busy_slots.constprop.0 (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff81253e8b)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8128f882)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff812e4896)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/events/hw_breakpoint.c (ffff8000102a434c)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (c04d39a0)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (c0000000003569e0)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/events/hw_breakpoint.c (ffffffff812118bc)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8120464c)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8120f65c)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8121e56c)
Location: kernel/events/hw_breakpoint.c:133
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
</details>
</li>
</ul>

## Differences
