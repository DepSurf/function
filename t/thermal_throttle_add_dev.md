# Function: <code>thermal_throttle_add_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049260)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback
```
**Symbols:**

```
ffffffff81049260-ffffffff81049316: thermal_throttle_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049410)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback
```
**Symbols:**

```
ffffffff81049410-ffffffff810494c3: thermal_throttle_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b8b1)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b0b1)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104eaa1)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051810)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104ee90)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81051f93)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052883)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810570d0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:407
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff810570d0-ffffffff810571f3: thermal_throttle_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81055e80)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:407
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81055e80-ffffffff81055fa3: thermal_throttle_add_dev (STB_LOCAL)
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
In drivers/thermal/intel/therm_throt.c (ffffffff81946a00)
Location: drivers/thermal/intel/therm_throt.c:407
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:407
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff819eb330-ffffffff819eb492: thermal_throttle_add_dev (STB_LOCAL)
ffffffff81d270f3-ffffffff81d2711c: thermal_throttle_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:408
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81b512c0-ffffffff81b51434: thermal_throttle_add_dev (STB_LOCAL)
ffffffff81ef2f2f-ffffffff81ef2f59: thermal_throttle_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:412
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81ce9300-ffffffff81ce9474: thermal_throttle_add_dev (STB_LOCAL)
ffffffff820a7b5c-ffffffff820a7b86: thermal_throttle_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:468
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81d51e40-ffffffff81d51fb4: thermal_throttle_add_dev (STB_LOCAL)
ffffffff82128f3a-ffffffff82128f64: thermal_throttle_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int thermal_throttle_add_dev(struct device *dev, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:468
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81e08bb0-ffffffff81e08d24: thermal_throttle_add_dev (STB_LOCAL)
ffffffff8220a923-ffffffff8220a94d: thermal_throttle_add_dev.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052983)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042373)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052833)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81053cb3)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
