# Function: <code>intel_msic_reg_update</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_msic_reg_update(short unsigned int reg, u8 val, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/intel_msic.c (ffffffff8180c300)
Location: drivers/mfd/intel_msic.c:207
Inline: False
Direct callers:
  - drivers/gpio/gpio-msic.c:msic_bus_sync_unlock
  - drivers/gpio/gpio-msic.c:msic_gpio_set
  - drivers/gpio/gpio-msic.c:msic_gpio_direction_output
  - drivers/gpio/gpio-msic.c:msic_gpio_direction_input
```
**Symbols:**

```
ffffffff8180c300-ffffffff8180c31c: intel_msic_reg_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_msic_reg_update(short unsigned int reg, u8 val, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/intel_msic.c (ffffffff8181b560)
Location: drivers/mfd/intel_msic.c:207
Inline: False
Direct callers:
  - drivers/gpio/gpio-msic.c:msic_bus_sync_unlock
  - drivers/gpio/gpio-msic.c:msic_gpio_set
  - drivers/gpio/gpio-msic.c:msic_gpio_direction_output
  - drivers/gpio/gpio-msic.c:msic_gpio_direction_input
```
**Symbols:**

```
ffffffff8181b560-ffffffff8181b57c: intel_msic_reg_update (STB_GLOBAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
