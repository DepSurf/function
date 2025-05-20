# Function: <code>hv_init_tsc_clocksource</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff8290fb58)
Location: drivers/clocksource/hyperv_timer.c:275
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff82919833)
Location: drivers/clocksource/hyperv_timer.c:274
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool hv_init_tsc_clocksource();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff82d2bf47)
Location: drivers/clocksource/hyperv_timer.c:421
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff82d2bf47-ffffffff82d2bffd: hv_init_tsc_clocksource (STB_LOCAL)
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
In drivers/clocksource/hyperv_timer.c (ffffffff8301a914)
Location: drivers/clocksource/hyperv_timer.c:421
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff83225962)
Location: drivers/clocksource/hyperv_timer.c:499
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff8330fb23)
Location: drivers/clocksource/hyperv_timer.c:496
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff834c995a)
Location: drivers/clocksource/hyperv_timer.c:496
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff83f0b065)
Location: drivers/clocksource/hyperv_timer.c:505
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff83731235)
Location: drivers/clocksource/hyperv_timer.c:520
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff839657d5)
Location: drivers/clocksource/hyperv_timer.c:520
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In drivers/clocksource/hyperv_timer.c (ffffffff828fe99f)
Location: drivers/clocksource/hyperv_timer.c:274
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff828f64d5)
Location: drivers/clocksource/hyperv_timer.c:274
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff82913bce)
Location: drivers/clocksource/hyperv_timer.c:274
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In drivers/clocksource/hyperv_timer.c (ffffffff8291a895)
Location: drivers/clocksource/hyperv_timer.c:274
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
