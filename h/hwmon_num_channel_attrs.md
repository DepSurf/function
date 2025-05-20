# Function: <code>hwmon_num_channel_attrs</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8171401b)
Location: drivers/hwmon/hwmon.c:460
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffff8172c4c0)
Location: drivers/hwmon/hwmon.c:460
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
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
In drivers/hwmon/hwmon.c (ffffffff8179dc8d)
Location: drivers/hwmon/hwmon.c:467
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
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
In drivers/hwmon/hwmon.c (ffffffff817e523a)
Location: drivers/hwmon/hwmon.c:467
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
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
In drivers/hwmon/hwmon.c (ffffffff81810ccd)
Location: drivers/hwmon/hwmon.c:485
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
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
In drivers/hwmon/hwmon.c (ffffffff81852b74)
Location: drivers/hwmon/hwmon.c:485
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffff8188474e)
Location: drivers/hwmon/hwmon.c:501
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffff81952f70)
Location: drivers/hwmon/hwmon.c:606
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
**Symbols:**

```
ffffffff81952f70-ffffffff81952fa9: hwmon_num_channel_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81957de0)
Location: drivers/hwmon/hwmon.c:616
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
**Symbols:**

```
ffffffff81957de0-ffffffff81957e19: hwmon_num_channel_attrs.isra.0 (STB_LOCAL)
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
In drivers/hwmon/hwmon.c (ffffffff8193ba20)
Location: drivers/hwmon/hwmon.c:616
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff8193ba20-ffffffff8193ba59: hwmon_num_channel_attrs.isra.0 (STB_LOCAL)
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
In drivers/hwmon/hwmon.c (ffffffff819e0250)
Location: drivers/hwmon/hwmon.c:654
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff819e0250-ffffffff819e0289: hwmon_num_channel_attrs.isra.0 (STB_LOCAL)
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
In drivers/hwmon/hwmon.c (ffffffff81b44f30)
Location: drivers/hwmon/hwmon.c:673
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81b44f30-ffffffff81b44f7c: hwmon_num_channel_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdc0a0)
Location: drivers/hwmon/hwmon.c:674
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81cdc0a0-ffffffff81cdc0ec: hwmon_num_channel_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d440c0)
Location: drivers/hwmon/hwmon.c:678
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81d440c0-ffffffff81d4410c: hwmon_num_channel_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfaa90)
Location: drivers/hwmon/hwmon.c:678
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
**Symbols:**

```
ffffffff81dfaa90-ffffffff81dfaadc: hwmon_num_channel_attrs.isra.0 (STB_LOCAL)
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
In drivers/hwmon/hwmon.c (ffff800010ad1428)
Location: drivers/hwmon/hwmon.c:501
Inline: True
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
In drivers/hwmon/hwmon.c (c0bb2178)
Location: drivers/hwmon/hwmon.c:501
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
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
In drivers/hwmon/hwmon.c (c000000000bb5ea0)
Location: drivers/hwmon/hwmon.c:501
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffe0006cde36)
Location: drivers/hwmon/hwmon.c:501
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffff8182a5ce)
Location: drivers/hwmon/hwmon.c:501
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffff817f1c5e)
Location: drivers/hwmon/hwmon.c:501
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffff81879bfe)
Location: drivers/hwmon/hwmon.c:501
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffff818955fe)
Location: drivers/hwmon/hwmon.c:501
Inline: True
```
</details>
</li>
</ul>

## Differences
