# Function: <code>cpuidle_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff816bbf00)
Location: drivers/cpuidle/driver.c:285
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff816bbf00-ffffffff816bc051: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8171d7d0)
Location: drivers/cpuidle/driver.c:285
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff8171d7d0-ffffffff8171d965: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff817503c0)
Location: drivers/cpuidle/driver.c:286
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff817503c0-ffffffff81750555: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8176ee80)
Location: drivers/cpuidle/driver.c:287
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff8176ee80-ffffffff8176f012: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff817e4720)
Location: drivers/cpuidle/driver.c:255
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff817e4720-ffffffff817e4842: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8182d980)
Location: drivers/cpuidle/driver.c:255
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff8182d980-ffffffff8182daa3: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81859b80)
Location: drivers/cpuidle/driver.c:255
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff81859b80-ffffffff81859ca3: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8189d4c0)
Location: drivers/cpuidle/driver.c:255
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff8189d4c0-ffffffff8189d5cf: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818cf8c0)
Location: drivers/cpuidle/driver.c:254
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff818cf8c0-ffffffff818cfa53: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff819a1df0)
Location: drivers/cpuidle/driver.c:260
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff819a1df0-ffffffff819a1f8f: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff819a4dc0)
Location: drivers/cpuidle/driver.c:260
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff819a4dc0-ffffffff819a4f5f: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff819899d0)
Location: drivers/cpuidle/driver.c:264
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff819899d0-ffffffff81989b9d: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81a341a0)
Location: drivers/cpuidle/driver.c:264
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff81a341a0-ffffffff81a343a6: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81ba0a70)
Location: drivers/cpuidle/driver.c:264
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff81ba0a70-ffffffff81ba0cc1: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81d42710)
Location: drivers/cpuidle/driver.c:264
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff81d42710-ffffffff81d42961: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81dac8f0)
Location: drivers/cpuidle/driver.c:268
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff81dac8f0-ffffffff81dacb85: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81e64990)
Location: drivers/cpuidle/driver.c:268
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff81e64990-ffffffff81e64c25: cpuidle_register_driver (STB_GLOBAL)
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
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffff800010b27958)
Location: drivers/cpuidle/driver.c:254
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffff800010b27958-ffff800010b27bcc: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (c0c025b8)
Location: drivers/cpuidle/driver.c:254
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
c0c025b8-c0c027f0: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (c000000000c1ed50)
Location: drivers/cpuidle/driver.c:254
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
c000000000c1ed50-c000000000c1efcc: cpuidle_register_driver (STB_GLOBAL)
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
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81873360)
Location: drivers/cpuidle/driver.c:254
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff81873360-ffffffff818734f3: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8183d150)
Location: drivers/cpuidle/driver.c:254
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff8183d150-ffffffff8183d2e3: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818c4d70)
Location: drivers/cpuidle/driver.c:254
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff818c4d70-ffffffff818c4f03: cpuidle_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register_driver(struct cpuidle_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818e1070)
Location: drivers/cpuidle/driver.c:254
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/cpuidle/cpuidle.c:cpuidle_register
```
**Symbols:**

```
ffffffff818e1070-ffffffff818e124a: cpuidle_register_driver (STB_GLOBAL)
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
