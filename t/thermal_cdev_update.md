# Function: <code>thermal_cdev_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81684ef0)
Location: drivers/thermal/thermal_core.c:1617
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81684ef0-ffffffff81685048: thermal_cdev_update.part.20 (STB_LOCAL)
ffffffff81685050-ffffffff8168506a: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e4c10)
Location: drivers/thermal/thermal_core.c:1623
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff816e4c10-ffffffff816e4d77: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff81719f00)
Location: drivers/thermal/thermal_helpers.c:169
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81719f00-ffffffff8171a067: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff817321b0)
Location: drivers/thermal/thermal_helpers.c:169
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff817321b0-ffffffff81732316: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff817a3300)
Location: drivers/thermal/thermal_helpers.c:169
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff817a3300-ffffffff817a346f: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff817eafb0)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff817eafb0-ffffffff817eb138: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff81816e90)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81816e90-ffffffff81817018: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff81859090)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81859090-ffffffff81859218: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff8188ab40)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff8188ab40-ffffffff8188acc8: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff819593f0)
Location: drivers/thermal/thermal_helpers.c:178
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/gov_step_wise.c:step_wise_throttle
  - drivers/thermal/gov_power_allocator.c:allow_maximum_power
```
**Symbols:**

```
ffffffff819593f0-ffffffff81959578: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff8195ea90)
Location: drivers/thermal/thermal_helpers.c:188
Inline: False
Direct callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/gov_step_wise.c:step_wise_throttle
  - drivers/thermal/gov_power_allocator.c:allow_maximum_power
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
**Symbols:**

```
ffffffff8195ea90-ffffffff8195ec2b: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff819422c0)
Location: drivers/thermal/thermal_helpers.c:222
Inline: False
Direct callers:
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/gov_step_wise.c:step_wise_throttle
```
**Symbols:**

```
ffffffff819422c0-ffffffff81942310: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:222
Inline: False
Direct callers:
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/gov_step_wise.c:step_wise_throttle
```
**Symbols:**

```
ffffffff81d26f39-ffffffff81d26f4e: thermal_cdev_update.cold (STB_LOCAL)
ffffffff819e6be0-ffffffff819e6c45: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:222
Inline: False
Direct callers:
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/gov_step_wise.c:step_wise_throttle
```
**Symbols:**

```
ffffffff81ef2d51-ffffffff81ef2d66: thermal_cdev_update.cold (STB_LOCAL)
ffffffff81b4c130-ffffffff81b4c1a5: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:248
Inline: False
Direct callers:
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/gov_step_wise.c:step_wise_throttle
```
**Symbols:**

```
ffffffff820a7acc-ffffffff820a7ae1: thermal_cdev_update.cold (STB_LOCAL)
ffffffff81ce3d20-ffffffff81ce3d95: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:188
Inline: False
Direct callers:
  - drivers/thermal/gov_step_wise.c:step_wise_throttle
```
**Symbols:**

```
ffffffff82128e96-ffffffff82128eab: thermal_cdev_update.cold (STB_LOCAL)
ffffffff81d4c350-ffffffff81d4c3c5: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:195
Inline: False
Direct callers:
  - drivers/thermal/gov_step_wise.c:step_wise_throttle
```
**Symbols:**

```
ffffffff8220a893-ffffffff8220a8a8: thermal_cdev_update.cold (STB_LOCAL)
ffffffff81e030d0-ffffffff81e03145: thermal_cdev_update (STB_GLOBAL)
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
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffff800010ad8748)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffff800010ad8748-ffff800010ad8910: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (c0bb8b9c)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
c0bb8b9c-c0bb8d50: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (c000000000bbf5e0)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
c000000000bbf5e0-c000000000bbf858: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffe0006d3118)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffe0006d3118-ffffffe0006d328c: thermal_cdev_update (STB_GLOBAL)
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
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff818309c0)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff818309c0-ffffffff81830b48: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff817f8050)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff817f8050-ffffffff817f81d8: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff8187fff0)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff8187fff0-ffffffff81880178: thermal_cdev_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff8189ba20)
Location: drivers/thermal/thermal_helpers.c:166
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:power_actor_set_power
  - drivers/thermal/fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:bang_bang_control
  - drivers/thermal/step_wise.c:step_wise_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff8189ba20-ffffffff8189bbc4: thermal_cdev_update (STB_GLOBAL)
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
