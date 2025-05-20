# Function: <code>divvy_up_power</code>

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
In drivers/thermal/power_allocator.c (ffffffff8168a0b1)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff816eae9e)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff8171bdbe)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff81734052)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff817a5214)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff817ecce4)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff81818e0a)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff8185af2b)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff8188ca3b)
Location: drivers/thermal/power_allocator.c:288
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
void divvy_up_power(u32 *req_power, u32 *max_power, int num_actors, u32 total_req_power, u32 power_range, u32 *granted_power, u32 *extra_actor_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff8195a900)
Location: drivers/thermal/gov_power_allocator.c:288
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff8195a900-ffffffff8195a9b8: divvy_up_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void divvy_up_power(u32 *req_power, u32 *max_power, int num_actors, u32 total_req_power, u32 power_range, u32 *granted_power, u32 *extra_actor_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff819615b0)
Location: drivers/thermal/gov_power_allocator.c:338
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff819615b0-ffffffff81961668: divvy_up_power (STB_LOCAL)
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
In drivers/thermal/gov_power_allocator.c (ffffffff81945a53)
Location: drivers/thermal/gov_power_allocator.c:337
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
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
In drivers/thermal/gov_power_allocator.c (ffffffff819ea483)
Location: drivers/thermal/gov_power_allocator.c:337
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
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
In drivers/thermal/gov_power_allocator.c (ffffffff81b50187)
Location: drivers/thermal/gov_power_allocator.c:337
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
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
In drivers/thermal/gov_power_allocator.c (ffffffff81ce80d6)
Location: drivers/thermal/gov_power_allocator.c:336
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
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
In drivers/thermal/gov_power_allocator.c (ffffffff81d508b6)
Location: drivers/thermal/gov_power_allocator.c:335
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
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
In drivers/thermal/gov_power_allocator.c (ffffffff81e0762e)
Location: drivers/thermal/gov_power_allocator.c:350
Inline: True
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
In drivers/thermal/power_allocator.c (ffff800010adb668)
Location: drivers/thermal/power_allocator.c:288
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void divvy_up_power(u32 *req_power, u32 *max_power, int num_actors, u32 total_req_power, u32 power_range, u32 *granted_power, u32 *extra_actor_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (c0bbb44c)
Location: drivers/thermal/power_allocator.c:288
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
**Symbols:**

```
c0bbb44c-c0bbb5b0: divvy_up_power (STB_LOCAL)
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
In drivers/thermal/power_allocator.c (c000000000bc31ec)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffe0006d5762)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff818328bb)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff817f9f4b)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff81881eeb)
Location: drivers/thermal/power_allocator.c:288
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
In drivers/thermal/power_allocator.c (ffffffff8189d956)
Location: drivers/thermal/power_allocator.c:288
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
</ul>
<b>Arch</b>
<ul>
</ul>
