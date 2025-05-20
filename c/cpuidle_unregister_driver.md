# Function: <code>cpuidle_unregister_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff816bc0e0)
Location: drivers/cpuidle/driver.c:305
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff816bc0e0-ffffffff816bc16b: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8171d9f0)
Location: drivers/cpuidle/driver.c:305
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff8171d9f0-ffffffff8171da7b: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81750560)
Location: drivers/cpuidle/driver.c:306
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81750560-ffffffff817505eb: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8176f020)
Location: drivers/cpuidle/driver.c:307
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff8176f020-ffffffff8176f093: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff817e4880)
Location: drivers/cpuidle/driver.c:275
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff817e4880-ffffffff817e48f3: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8182dab0)
Location: drivers/cpuidle/driver.c:275
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff8182dab0-ffffffff8182db2c: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81859b00)
Location: drivers/cpuidle/driver.c:275
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81859b00-ffffffff81859b7c: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/driver.c (0)
Location: drivers/cpuidle/driver.c:275
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff8189d652-ffffffff8189d665: cpuidle_unregister_driver.cold (STB_LOCAL)
ffffffff8189d440-ffffffff8189d4bc: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818cf7f0)
Location: drivers/cpuidle/driver.c:287
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff818cf7f0-ffffffff818cf8c0: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff819a1f90)
Location: drivers/cpuidle/driver.c:293
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff819a1f90-ffffffff819a204e: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff819a4f60)
Location: drivers/cpuidle/driver.c:293
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff819a4f60-ffffffff819a501e: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81989ba0)
Location: drivers/cpuidle/driver.c:297
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81989ba0-ffffffff81989c60: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81a343b0)
Location: drivers/cpuidle/driver.c:297
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81a343b0-ffffffff81a34470: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81ba0970)
Location: drivers/cpuidle/driver.c:297
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81ba0970-ffffffff81ba0a6e: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81d42600)
Location: drivers/cpuidle/driver.c:297
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81d42600-ffffffff81d426fe: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81dac7e0)
Location: drivers/cpuidle/driver.c:301
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81dac7e0-ffffffff81dac8de: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81e64880)
Location: drivers/cpuidle/driver.c:301
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81e64880-ffffffff81e6497e: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffff800010b277b8)
Location: drivers/cpuidle/driver.c:287
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffff800010b277b8-ffff800010b27958: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (c0c027f0)
Location: drivers/cpuidle/driver.c:287
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
c0c027f0-c0c0293c: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (c000000000c1eba0)
Location: drivers/cpuidle/driver.c:287
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
c000000000c1eba0-c000000000c1ed50: cpuidle_unregister_driver (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81873290)
Location: drivers/cpuidle/driver.c:287
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff81873290-ffffffff81873360: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8183d080)
Location: drivers/cpuidle/driver.c:287
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff8183d080-ffffffff8183d150: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818c4ca0)
Location: drivers/cpuidle/driver.c:287
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff818c4ca0-ffffffff818c4d70: cpuidle_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpuidle_unregister_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818e1250)
Location: drivers/cpuidle/driver.c:287
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
```
**Symbols:**

```
ffffffff818e1250-ffffffff818e133c: cpuidle_unregister_driver (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
