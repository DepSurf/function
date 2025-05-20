# Function: <code>__unbind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816842c0)
Location: drivers/thermal/thermal_core.c:307
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
```
```
In drivers/md/dm.c (ffffffff816a1f81)
Location: drivers/md/dm.c:2524
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff816842c0-ffffffff8168431e: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e5900)
Location: drivers/thermal/thermal_core.c:307
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
```
```
In drivers/md/dm.c (ffffffff81702c0a)
Location: drivers/md/dm.c:1696
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff816e5900-ffffffff816e595e: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81715780)
Location: drivers/thermal/thermal_core.c:1014
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
```
```
In drivers/md/dm.c (ffffffff81734ad9)
Location: drivers/md/dm.c:1753
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81715780-ffffffff817157de: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172d300)
Location: drivers/thermal/thermal_core.c:1052
Inline: False
```
```
In drivers/md/dm.c (ffffffff8174de99)
Location: drivers/md/dm.c:1960
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8172d300-ffffffff8172d35f: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179e950)
Location: drivers/thermal/thermal_core.c:1048
Inline: False
```
```
In drivers/md/dm.c (ffffffff817bff19)
Location: drivers/md/dm.c:1939
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8179e950-ffffffff8179e9af: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e5f20)
Location: drivers/thermal/thermal_core.c:1045
Inline: False
```
```
In drivers/md/dm.c (ffffffff81809255)
Location: drivers/md/dm.c:2119
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff817e5f20-ffffffff817e5f7e: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81811dd0)
Location: drivers/thermal/thermal_core.c:1049
Inline: False
```
```
In drivers/md/dm.c (ffffffff81835383)
Location: drivers/md/dm.c:2159
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81811dd0-ffffffff81811e2e: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81853e10)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (ffffffff81877d59)
Location: drivers/md/dm.c:2190
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81853e10-ffffffff81853e6e: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81885870)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (ffffffff818a9b79)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81885870-ffffffff818858ce: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195473b)
Location: drivers/thermal/thermal_core.c:1092
Inline: True
```
```
In drivers/md/dm.c (ffffffff81979dd9)
Location: drivers/md/dm.c:2191
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195a02b)
Location: drivers/thermal/thermal_core.c:1160
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197e6e9)
Location: drivers/md/dm.c:2065
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193d1a4)
Location: drivers/thermal/thermal_core.c:1100
Inline: True
```
```
In drivers/md/dm.c (ffffffff81962539)
Location: drivers/md/dm.c:2084
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e1a44)
Location: drivers/thermal/thermal_core.c:1052
Inline: True
```
```
In drivers/md/dm.c (ffffffff81a096ec)
Location: drivers/md/dm.c:1970
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b46bca)
Location: drivers/thermal/thermal_core.c:1055
Inline: True
```
```
In drivers/md/dm.c (ffffffff81b71767)
Location: drivers/md/dm.c:2150
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cde25a)
Location: drivers/thermal/thermal_core.c:1055
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d0e5b7)
Location: drivers/md/dm.c:2228
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
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
In drivers/md/dm.c (ffffffff81d77bc1)
Location: drivers/md/dm.c:2274
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
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
In drivers/md/dm.c (ffffffff81e2edf1)
Location: drivers/md/dm.c:2282
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad2958)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (ffff800010afe150)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffff800010ad2958-ffff800010ad29d4: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb3200)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (c0bdf830)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
c0bb3200-c0bb3264: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb7550)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (c000000000beeff8)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
c000000000bb7550-c000000000bb7600: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006cf07c)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (ffffffe0006effee)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffe0006cf07c-ffffffe0006cf0ea: __unbind (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182b6f0)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (ffffffff8184f9f9)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8182b6f0-ffffffff8182b74e: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f2d80)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (ffffffff81817009)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff817f2d80-ffffffff817f2dde: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187ad20)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (ffffffff8189f029)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8187ad20-ffffffff8187ad7e: __unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void __unbind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81896720)
Location: drivers/thermal/thermal_core.c:1104
Inline: False
```
```
In drivers/md/dm.c (ffffffff818bb712)
Location: drivers/md/dm.c:2188
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81896720-ffffffff8189677e: __unbind (STB_LOCAL)
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
