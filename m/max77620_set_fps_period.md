# Function: <code>max77620_set_fps_period</code>

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
int max77620_set_fps_period(struct max77620_chip *chip, int fps_id, int time_period);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max77620.c (ffff8000109451d0)
Location: drivers/mfd/max77620.c:578
Inline: False
Direct callers:
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77620.c:max77620_i2c_suspend
```
**Symbols:**

```
ffff8000109451d0-ffff800010945298: max77620_set_fps_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int max77620_set_fps_period(struct max77620_chip *chip, int fps_id, int time_period);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max77620.c (c0a2e420)
Location: drivers/mfd/max77620.c:578
Inline: False
Direct callers:
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77620.c:max77620_i2c_suspend
```
**Symbols:**

```
c0a2e420-c0a2e4e0: max77620_set_fps_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int max77620_set_fps_period(struct max77620_chip *chip, int fps_id, int time_period);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/max77620.c (c0000000009ef1e0)
Location: drivers/mfd/max77620.c:578
Inline: False
Direct callers:
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77620.c:max77620_i2c_suspend
```
**Symbols:**

```
c0000000009ef1e0-c0000000009ef2e4: max77620_set_fps_period (STB_LOCAL)
```
</details>
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
