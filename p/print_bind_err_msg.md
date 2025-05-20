# Function: <code>print_bind_err_msg</code>

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
In drivers/thermal/thermal_core.c (ffffffff816871b6)
Location: drivers/thermal/thermal_core.c:274
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff816e7e76)
Location: drivers/thermal/thermal_core.c:274
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff817167e6)
Location: drivers/thermal/thermal_core.c:821
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff8172e5c4)
Location: drivers/thermal/thermal_core.c:858
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff8179fc04)
Location: drivers/thermal/thermal_core.c:854
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff817e7b63)
Location: drivers/thermal/thermal_core.c:851
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff81813406)
Location: drivers/thermal/thermal_core.c:855
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff81856eb3)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff8188893b)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_bind_err_msg(struct thermal_zone_device *tz, struct thermal_cooling_device *cdev, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81957297)
Location: drivers/thermal/thermal_core.c:849
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff81957297-ffffffff819572b8: print_bind_err_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_bind_err_msg(struct thermal_zone_device *tz, struct thermal_cooling_device *cdev, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81c25a06)
Location: drivers/thermal/thermal_core.c:917
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff81c25a06-ffffffff81c25a27: print_bind_err_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81c17be3)
Location: drivers/thermal/thermal_core.c:851
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff81c17be3-ffffffff81c17c03: print_bind_err_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d26d04)
Location: drivers/thermal/thermal_core.c:798
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff81d26d04-ffffffff81d26d24: print_bind_err_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ef2b85)
Location: drivers/thermal/thermal_core.c:800
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff81ef2b85-ffffffff81ef2bb4: print_bind_err_msg.isra.0 (STB_LOCAL)
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
In drivers/thermal/thermal_core.c (ffffffff81cdf184)
Location: drivers/thermal/thermal_core.c:787
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff81d48ed7)
Location: drivers/thermal/thermal_core.c:790
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In drivers/thermal/thermal_core.c (ffffffff81dff2f2)
Location: drivers/thermal/thermal_core.c:857
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In drivers/thermal/thermal_core.c (ffff800010ad5978)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (c0bb4c28)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (c000000000bbb8d0)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffe0006d095a)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff8182e7bb)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff817f5e4b)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff8187ddeb)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
In drivers/thermal/thermal_core.c (ffffffff8189981b)
Location: drivers/thermal/thermal_core.c:861
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:__bind
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
