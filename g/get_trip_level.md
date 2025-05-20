# Function: <code>get_trip_level</code>

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
In drivers/thermal/fair_share.c (ffffffff81688ccb)
Location: drivers/thermal/fair_share.c:34
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff816e99ac)
Location: drivers/thermal/fair_share.c:34
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff8171a80c)
Location: drivers/thermal/fair_share.c:34
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff81732abc)
Location: drivers/thermal/fair_share.c:34
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff817a3c3c)
Location: drivers/thermal/fair_share.c:34
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff817eb722)
Location: drivers/thermal/fair_share.c:34
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff818175f2)
Location: drivers/thermal/fair_share.c:34
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff81859832)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff8188b342)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_fair_share.c (ffffffff81959e02)
Location: drivers/thermal/gov_fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
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
In drivers/thermal/gov_fair_share.c (ffffffff81960a32)
Location: drivers/thermal/gov_fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
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
In drivers/thermal/gov_fair_share.c (ffffffff81943f82)
Location: drivers/thermal/gov_fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
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
In drivers/thermal/gov_fair_share.c (ffffffff819e8942)
Location: drivers/thermal/gov_fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_trip_level(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_fair_share.c (ffffffff81b4e330)
Location: drivers/thermal/gov_fair_share.c:22
Inline: False
Direct callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
**Symbols:**

```
ffffffff81b4e330-ffffffff81b4e462: get_trip_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_trip_level(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_fair_share.c (ffffffff81ce6260)
Location: drivers/thermal/gov_fair_share.c:22
Inline: False
Direct callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
**Symbols:**

```
ffffffff81ce6260-ffffffff81ce6392: get_trip_level (STB_LOCAL)
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
In drivers/thermal/gov_fair_share.c (ffffffff81d4eacd)
Location: drivers/thermal/gov_fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
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
In drivers/thermal/gov_fair_share.c (ffffffff81e05545)
Location: drivers/thermal/gov_fair_share.c:18
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffff800010ad9e84)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (c0bba040)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (c000000000bc1608)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffe0006d4488)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff818311c2)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff817f8852)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff818807f2)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
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
In drivers/thermal/fair_share.c (ffffffff8189c242)
Location: drivers/thermal/fair_share.c:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
