# Function: <code>__bind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816871b0)
Location: drivers/thermal/thermal_core.c:281
Inline: False
```
```
In drivers/md/dm.c (ffffffff816a439a)
Location: drivers/md/dm.c:2479
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff816871b0-ffffffff81687279: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e7e70)
Location: drivers/thermal/thermal_core.c:281
Inline: False
```
```
In drivers/md/dm.c (ffffffff8170454a)
Location: drivers/md/dm.c:1644
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff816e7e70-ffffffff816e7f31: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817167e0)
Location: drivers/thermal/thermal_core.c:828
Inline: False
```
```
In drivers/md/dm.c (ffffffff81736428)
Location: drivers/md/dm.c:1699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff817167e0-ffffffff817168a1: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172e550)
Location: drivers/thermal/thermal_core.c:865
Inline: False
```
```
In drivers/md/dm.c (ffffffff8174f802)
Location: drivers/md/dm.c:1906
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff8172e550-ffffffff8172e607: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179fb90)
Location: drivers/thermal/thermal_core.c:861
Inline: False
```
```
In drivers/md/dm.c (ffffffff817c1a0b)
Location: drivers/md/dm.c:1885
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff8179fb90-ffffffff8179fc47: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e7150)
Location: drivers/thermal/thermal_core.c:858
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffffffff8180a112)
Location: drivers/md/dm.c:2055
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff817e7150-ffffffff817e7209: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81812270)
Location: drivers/thermal/thermal_core.c:862
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffffffff81836112)
Location: drivers/md/dm.c:2095
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81812270-ffffffff81812329: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffffffff81878d34)
Location: drivers/md/dm.c:2126
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81855160-ffffffff818551ee: __bind (STB_LOCAL)
ffffffff81856e89-ffffffff81856eb3: __bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffffffff818aab74)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81886bc0-ffffffff81886c4e: __bind (STB_LOCAL)
ffffffff818888d9-ffffffff81888903: __bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:856
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
```
```
In drivers/md/dm.c (ffffffff81977220)
Location: drivers/md/dm.c:2127
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81954f70-ffffffff81955005: __bind (STB_LOCAL)
ffffffff8195730f-ffffffff81957329: __bind.cold (STB_LOCAL)
ffffffff81977220-ffffffff81977331: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:924
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
```
```
In drivers/md/dm.c (ffffffff8197bf00)
Location: drivers/md/dm.c:2000
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81959bf0-ffffffff81959c85: __bind (STB_LOCAL)
ffffffff81c25a90-ffffffff81c25aaa: __bind.cold (STB_LOCAL)
ffffffff8197bf00-ffffffff8197c027: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:858
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
```
```
In drivers/md/dm.c (ffffffff8195fda0)
Location: drivers/md/dm.c:2019
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff8193d810-ffffffff8193d8a5: __bind (STB_LOCAL)
ffffffff81c17c03-ffffffff81c17c1e: __bind.cold (STB_LOCAL)
ffffffff8195fda0-ffffffff8195ff83: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:805
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
```
```
In drivers/md/dm.c (ffffffff81a07d50)
Location: drivers/md/dm.c:1900
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff819e20c0-ffffffff819e215e: __bind (STB_LOCAL)
ffffffff81d26d24-ffffffff81d26d60: __bind.cold (STB_LOCAL)
ffffffff81a07d50-ffffffff81a07f35: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:807
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
```
```
In drivers/md/dm.c (ffffffff81b718b0)
Location: drivers/md/dm.c:2077
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81b477e0-ffffffff81b47890: __bind (STB_LOCAL)
ffffffff81ef2bb4-ffffffff81ef2be4: __bind.cold (STB_LOCAL)
ffffffff81b718b0-ffffffff81b71a17: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:794
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:bind_tz
  - drivers/thermal/thermal_core.c:bind_cdev
```
```
In drivers/md/dm.c (ffffffff81d0d090)
Location: drivers/md/dm.c:2158
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81cdee80-ffffffff81cdef62: __bind (STB_LOCAL)
ffffffff820a7a35-ffffffff820a7a4e: __bind.cold (STB_LOCAL)
ffffffff81d0d090-ffffffff81d0d1d9: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dm_table *__bind(struct mapped_device *md, struct dm_table *t, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d75e50)
Location: drivers/md/dm.c:2204
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81d75e50-ffffffff81d75f99: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dm_table *__bind(struct mapped_device *md, struct dm_table *t, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2d080)
Location: drivers/md/dm.c:2212
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81e2d080-ffffffff81e2d1c9: __bind (STB_LOCAL)
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
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad39d0)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffff800010b00ca8)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffff800010ad39d0-ffff800010ad3aa4: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb45b4)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (c0be058c)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
c0bb45b4-c0bb4674: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bba9c0)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (c000000000befe98)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
c000000000bba9c0-c000000000bbab2c: __bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006cffae)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/md/dm.c (ffffffe0006f0e2e)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffe0006cffae-ffffffe0006d0078: __bind (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffffffff818509f4)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff8182ca40-ffffffff8182cace: __bind (STB_LOCAL)
ffffffff8182e759-ffffffff8182e783: __bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffffffff81818004)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff817f40d0-ffffffff817f415e: __bind (STB_LOCAL)
ffffffff817f5de9-ffffffff817f5e13: __bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffffffff818a0024)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff8187c070-ffffffff8187c0fe: __bind (STB_LOCAL)
ffffffff8187dd89-ffffffff8187ddb3: __bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void __bind(struct thermal_zone_device *tz, int mask, struct thermal_cooling_device *cdev, long unsigned int *limits, unsigned int weight);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:868
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/dm.c (ffffffff818bc296)
Location: drivers/md/dm.c:2124
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81897aa0-ffffffff81897b2e: __bind (STB_LOCAL)
ffffffff818997b9-ffffffff818997e3: __bind.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mapped_device *md</code>
</li>
<li>
<b>Param added. </b>
<code>struct dm_table *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct thermal_zone_device *tz</code>
</li>
<li>
<b>Param removed. </b>
<code>int mask</code>
</li>
<li>
<b>Param removed. </b>
<code>struct thermal_cooling_device *cdev</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int weight</code>
</li>
<li>
<b>Param reordered. </b>
<code>tz, mask, cdev, limits, weight</code> ➡️ <code>md, t, limits</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int *limits</code> ➡️ <code>struct queue_limits *limits</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct dm_table *</code>
</li>
</ul>
</details>
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
