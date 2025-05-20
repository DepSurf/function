# Function: <code>cdev_is_power_actor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81688531)
Location: include/linux/thermal.h:384
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_set_power
```
```
In drivers/thermal/power_allocator.c (ffffffff81689db2)
Location: include/linux/thermal.h:384
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e930b)
Location: include/linux/thermal.h:405
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff816eb39c)
Location: include/linux/thermal.h:405
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817183db)
Location: include/linux/thermal.h:431
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff8171c2bc)
Location: include/linux/thermal.h:431
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8173068b)
Location: include/linux/thermal.h:431
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff8173454c)
Location: include/linux/thermal.h:431
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817a170b)
Location: include/linux/thermal.h:432
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff817a5731)
Location: include/linux/thermal.h:432
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e8c96)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff817ed1c8)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81814b46)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff818192e8)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81856c30)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff8185b442)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81888680)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff8188cf52)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819570ae)
Location: drivers/thermal/thermal_core.h:49
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8195b574)
Location: drivers/thermal/thermal_core.h:49
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allow_maximum_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
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
In drivers/thermal/gov_power_allocator.c (ffffffff819621e4)
Location: drivers/thermal/thermal_core.h:62
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allow_maximum_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In drivers/thermal/gov_power_allocator.c (ffffffff81945e19)
Location: drivers/thermal/thermal_core.h:62
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In drivers/thermal/gov_power_allocator.c (ffffffff819ea839)
Location: drivers/thermal/thermal_core.h:62
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In drivers/thermal/gov_power_allocator.c (ffffffff81b5058d)
Location: drivers/thermal/thermal_core.h:62
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In drivers/thermal/gov_power_allocator.c (ffffffff81ce84c5)
Location: drivers/thermal/thermal_core.h:62
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In drivers/thermal/gov_power_allocator.c (ffffffff81d50ca6)
Location: drivers/thermal/thermal_core.h:68
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In drivers/thermal/gov_power_allocator.c (ffffffff81e07a18)
Location: drivers/thermal/thermal_core.h:65
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
  - drivers/thermal/gov_power_allocator.c:power_allocator_update_tz
  - drivers/thermal/gov_power_allocator.c:power_allocator_update_tz
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad5e7c)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffff800010adbbe0)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb6638)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (c0bbbfec)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bbbf5c)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (c000000000bc38d4)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006d1192)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d5bb0)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182e500)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff81832dd2)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f5b90)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff817fa462)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187db30)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff81882402)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81899560)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/thermal_core.c:power_actor_get_min_power
  - drivers/thermal/thermal_core.c:power_actor_get_max_power
```
```
In drivers/thermal/power_allocator.c (ffffffff8189dea2)
Location: include/linux/thermal.h:418
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
</ul>

## Differences
