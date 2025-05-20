# Function: <code>handle_thermal_trip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816850d0)
Location: drivers/thermal/thermal_core.c:453
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff816850d0-ffffffff81685295: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e64d0)
Location: drivers/thermal/thermal_core.c:453
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff816e64d0-ffffffff816e6686: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81715a90)
Location: drivers/thermal/thermal_core.c:350
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff81715a90-ffffffff81715c46: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172d5d0)
Location: drivers/thermal/thermal_core.c:409
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff8172d5d0-ffffffff8172d7b2: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179ec20)
Location: drivers/thermal/thermal_core.c:409
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff8179ec20-ffffffff8179ee1a: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e61d0)
Location: drivers/thermal/thermal_core.c:406
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff817e61d0-ffffffff817e63d3: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81812650)
Location: drivers/thermal/thermal_core.c:406
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff81812650-ffffffff81812853: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81854621)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff818545e0-ffffffff8185479f: handle_thermal_trip (STB_LOCAL)
ffffffff81856e17-ffffffff81856e71: handle_thermal_trip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81886081)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff81886040-ffffffff818861ff: handle_thermal_trip (STB_LOCAL)
ffffffff81888867-ffffffff818888c1: handle_thermal_trip.cold (STB_LOCAL)
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
In drivers/thermal/thermal_core.c (ffffffff819552c5)
Location: drivers/thermal/thermal_core.c:406
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff81954a20-ffffffff81954b17: handle_thermal_trip.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195a240)
Location: drivers/thermal/thermal_core.c:421
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff8195a240-ffffffff8195a425: handle_thermal_trip (STB_LOCAL)
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
In drivers/thermal/thermal_core.c (ffffffff8193dc6f)
Location: drivers/thermal/thermal_core.c:416
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
In drivers/thermal/thermal_core.c (ffffffff819e251f)
Location: drivers/thermal/thermal_core.c:361
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b47b60)
Location: drivers/thermal/thermal_core.c:361
Inline: False
```
**Symbols:**

```
ffffffff81b47b60-ffffffff81b47e12: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cddb10)
Location: drivers/thermal/thermal_core.c:347
Inline: False
```
**Symbols:**

```
ffffffff81cddb10-ffffffff81cddd04: handle_thermal_trip (STB_LOCAL)
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
In drivers/thermal/thermal_core.c (ffffffff81d47450)
Location: drivers/thermal/thermal_core.c:346
Inline: True
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
In drivers/thermal/thermal_core.c (ffffffff81dfda54)
Location: drivers/thermal/thermal_core.c:364
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad30e8)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffff800010ad30e8-ffff800010ad332c: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb37dc)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
c0bb37dc-c0bb3a3c: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb7aa0)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
c000000000bb7aa0-c000000000bb7d94: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006cf5e6)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffe0006cf5e6-ffffffe0006cf7aa: handle_thermal_trip (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182bf01)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff8182bec0-ffffffff8182c07f: handle_thermal_trip (STB_LOCAL)
ffffffff8182e6e7-ffffffff8182e741: handle_thermal_trip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f3591)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff817f3550-ffffffff817f370f: handle_thermal_trip (STB_LOCAL)
ffffffff817f5d77-ffffffff817f5dd1: handle_thermal_trip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187b531)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff8187b4f0-ffffffff8187b6af: handle_thermal_trip (STB_LOCAL)
ffffffff8187dd17-ffffffff8187dd71: handle_thermal_trip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void handle_thermal_trip(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81896f31)
Location: drivers/thermal/thermal_core.c:412
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_notify_framework
```
**Symbols:**

```
ffffffff81896ef0-ffffffff818970c8: handle_thermal_trip (STB_LOCAL)
ffffffff81899747-ffffffff818997a1: handle_thermal_trip.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
