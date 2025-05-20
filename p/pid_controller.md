# Function: <code>pid_controller</code>

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
In drivers/thermal/power_allocator.c (ffffffff81689f9f)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
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
In drivers/thermal/power_allocator.c (ffffffff816ead90)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff8171bcb0)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff81733f44)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff817a5106)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff817ecbe2)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff81818d0b)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff8185ae4b)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff8188c95b)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 pid_controller(struct thermal_zone_device *tz, int control_temp, u32 max_allocatable_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff8195b2a0)
Location: drivers/thermal/gov_power_allocator.c:192
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff8195b2a0-ffffffff8195b519: pid_controller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 pid_controller(struct thermal_zone_device *tz, int control_temp, u32 max_allocatable_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81961f30)
Location: drivers/thermal/gov_power_allocator.c:217
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff81961f30-ffffffff81962184: pid_controller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 pid_controller(struct thermal_zone_device *tz, int control_temp, u32 max_allocatable_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff819454f0)
Location: drivers/thermal/gov_power_allocator.c:217
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff819454f0-ffffffff8194577f: pid_controller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 pid_controller(struct thermal_zone_device *tz, int control_temp, u32 max_allocatable_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff819e9f20)
Location: drivers/thermal/gov_power_allocator.c:217
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff819e9f20-ffffffff819ea1ac: pid_controller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 pid_controller(struct thermal_zone_device *tz, int control_temp, u32 max_allocatable_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4fbe0)
Location: drivers/thermal/gov_power_allocator.c:217
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff81b4fbe0-ffffffff81b4fe99: pid_controller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 pid_controller(struct thermal_zone_device *tz, int control_temp, u32 max_allocatable_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce7b30)
Location: drivers/thermal/gov_power_allocator.c:216
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff81ce7b30-ffffffff81ce7de9: pid_controller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 pid_controller(struct thermal_zone_device *tz, int control_temp, u32 max_allocatable_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81d50310)
Location: drivers/thermal/gov_power_allocator.c:215
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff81d50310-ffffffff81d505c9: pid_controller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 pid_controller(struct thermal_zone_device *tz, int control_temp, u32 max_allocatable_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81e07190)
Location: drivers/thermal/gov_power_allocator.c:238
Inline: False
```
**Symbols:**

```
ffffffff81e07190-ffffffff81e07497: pid_controller (STB_LOCAL)
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
In drivers/thermal/power_allocator.c (ffff800010adb5a4)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (c0bbb8b8)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (c000000000bc310c)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffe0006d568e)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff818327db)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff817f9e6b)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff81881e0b)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In drivers/thermal/power_allocator.c (ffffffff8189d873)
Location: drivers/thermal/power_allocator.c:192
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
