# Function: <code>x86_thermal_enabled</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool x86_thermal_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81947430)
Location: drivers/thermal/intel/therm_throt.c:619
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
```
**Symbols:**

```
ffffffff81947430-ffffffff81947446: x86_thermal_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool x86_thermal_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff819ec290)
Location: drivers/thermal/intel/therm_throt.c:624
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
```
**Symbols:**

```
ffffffff819ec290-ffffffff819ec2a6: x86_thermal_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool x86_thermal_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81b52280)
Location: drivers/thermal/intel/therm_throt.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
```
**Symbols:**

```
ffffffff81b52280-ffffffff81b5229a: x86_thermal_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool x86_thermal_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea430)
Location: drivers/thermal/intel/therm_throt.c:644
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
```
**Symbols:**

```
ffffffff81cea430-ffffffff81cea44a: x86_thermal_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool x86_thermal_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52f70)
Location: drivers/thermal/intel/therm_throt.c:700
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
```
**Symbols:**

```
ffffffff81d52f70-ffffffff81d52f8a: x86_thermal_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool x86_thermal_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09cd0)
Location: drivers/thermal/intel/therm_throt.c:700
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
```
**Symbols:**

```
ffffffff81e09cd0-ffffffff81e09cea: x86_thermal_enabled (STB_GLOBAL)
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
