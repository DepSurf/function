# Function: <code>for_each_thermal_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int for_each_thermal_zone(int (*cb)(struct thermal_zone_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195c930)
Location: drivers/thermal/thermal_core.c:655
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
**Symbols:**

```
ffffffff8195c930-ffffffff8195c9b2: for_each_thermal_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int for_each_thermal_zone(int (*cb)(struct thermal_zone_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819400b0)
Location: drivers/thermal/thermal_core.c:606
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
**Symbols:**

```
ffffffff819400b0-ffffffff81940132: for_each_thermal_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int for_each_thermal_zone(int (*cb)(struct thermal_zone_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e49d0)
Location: drivers/thermal/thermal_core.c:553
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
**Symbols:**

```
ffffffff819e49d0-ffffffff819e4a52: for_each_thermal_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int for_each_thermal_zone(int (*cb)(struct thermal_zone_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b49bd0)
Location: drivers/thermal/thermal_core.c:555
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
**Symbols:**

```
ffffffff81b49bd0-ffffffff81b49c5e: for_each_thermal_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int for_each_thermal_zone(int (*cb)(struct thermal_zone_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce1350)
Location: drivers/thermal/thermal_core.c:546
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
**Symbols:**

```
ffffffff81ce1350-ffffffff81ce13de: for_each_thermal_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int for_each_thermal_zone(int (*cb)(struct thermal_zone_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d495c0)
Location: drivers/thermal/thermal_core.c:541
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
**Symbols:**

```
ffffffff81d495c0-ffffffff81d4964e: for_each_thermal_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int for_each_thermal_zone(int (*cb)(struct thermal_zone_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81e003d0)
Location: drivers/thermal/thermal_core.c:582
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
**Symbols:**

```
ffffffff81e003d0-ffffffff81e0045e: for_each_thermal_zone (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
