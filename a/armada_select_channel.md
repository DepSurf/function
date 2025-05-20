# Function: <code>armada_select_channel</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int armada_select_channel(struct armada_thermal_priv *priv, int channel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/armada_thermal.c (ffff800010addd70)
Location: drivers/thermal/armada_thermal.c:322
Inline: False
Direct callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_get_temp
  - drivers/thermal/armada_thermal.c:armada_get_temp
```
**Symbols:**

```
ffff800010addd70-ffff800010adde98: armada_select_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int armada_select_channel(struct armada_thermal_priv *priv, int channel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/armada_thermal.c (c0bbf978)
Location: drivers/thermal/armada_thermal.c:322
Inline: False
Direct callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_get_temp
  - drivers/thermal/armada_thermal.c:armada_get_temp
```
**Symbols:**

```
c0bbf978-c0bbfa98: armada_select_channel (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
