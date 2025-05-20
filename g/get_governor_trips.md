# Function: <code>get_governor_trips</code>

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
In drivers/thermal/power_allocator.c (ffffffff8168a665)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (ffffffff816eb465)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (ffffffff8171c385)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (ffffffff81734625)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (ffffffff817a5825)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void get_governor_trips(struct thermal_zone_device *tz, struct power_allocator_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (0)
Location: drivers/thermal/gov_power_allocator.c:468
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
```
**Symbols:**

```
ffffffff8195afe0-ffffffff8195b0e3: get_governor_trips (STB_LOCAL)
ffffffff8195bbf8-ffffffff8195bc11: get_governor_trips.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void get_governor_trips(struct thermal_zone_device *tz, struct power_allocator_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (0)
Location: drivers/thermal/gov_power_allocator.c:519
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
```
**Symbols:**

```
ffffffff81961c70-ffffffff81961d73: get_governor_trips (STB_LOCAL)
ffffffff81c25d2c-ffffffff81c25d45: get_governor_trips.cold (STB_LOCAL)
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
In drivers/thermal/gov_power_allocator.c (0)
Location: drivers/thermal/gov_power_allocator.c:520
Inline: True
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
In drivers/thermal/gov_power_allocator.c (0)
Location: drivers/thermal/gov_power_allocator.c:520
Inline: True
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
In drivers/thermal/gov_power_allocator.c (0)
Location: drivers/thermal/gov_power_allocator.c:520
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
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
In drivers/thermal/gov_power_allocator.c (0)
Location: drivers/thermal/gov_power_allocator.c:511
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
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
In drivers/thermal/gov_power_allocator.c (0)
Location: drivers/thermal/gov_power_allocator.c:510
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
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
In drivers/thermal/gov_power_allocator.c (ffffffff81e06c92)
Location: drivers/thermal/gov_power_allocator.c:493
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (ffffffe0006d5376)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
In drivers/thermal/power_allocator.c (0)
Location: drivers/thermal/power_allocator.c:468
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_bind
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
