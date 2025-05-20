# Function: <code>notify_hwp_interrupt</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void notify_hwp_interrupt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebd50)
Location: drivers/thermal/intel/therm_throt.c:572
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff819ebd50-ffffffff819ebd6c: notify_hwp_interrupt (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void notify_hwp_interrupt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81b51e10)
Location: drivers/thermal/intel/therm_throt.c:584
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81b9f0d0-ffffffff81b9f1f0: notify_hwp_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void notify_hwp_interrupt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9f90)
Location: drivers/thermal/intel/therm_throt.c:588
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81d40ab0-ffffffff81d40bd0: notify_hwp_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void notify_hwp_interrupt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52ad0)
Location: drivers/thermal/intel/therm_throt.c:644
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81dab630-ffffffff81dab750: notify_hwp_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void notify_hwp_interrupt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09830)
Location: drivers/thermal/intel/therm_throt.c:644
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81e636d0-ffffffff81e637f0: notify_hwp_interrupt (STB_GLOBAL)
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
