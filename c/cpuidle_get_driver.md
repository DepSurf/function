# Function: <code>cpuidle_get_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff816bbe90)
Location: drivers/cpuidle/driver.c:318
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff816bbe90-ffffffff816bbea2: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8171dad5)
Location: drivers/cpuidle/driver.c:318
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff8171d760-ffffffff8171d772: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81750645)
Location: drivers/cpuidle/driver.c:319
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81750350-ffffffff81750362: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8176f0f5)
Location: drivers/cpuidle/driver.c:320
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff8176ee10-ffffffff8176ee22: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff817e4955)
Location: drivers/cpuidle/driver.c:288
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff817e46e0-ffffffff817e46f2: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8182db85)
Location: drivers/cpuidle/driver.c:288
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff8182d910-ffffffff8182d922: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81859d05)
Location: drivers/cpuidle/driver.c:288
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81859a90-ffffffff81859aa9: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8189d625)
Location: drivers/cpuidle/driver.c:288
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff8189d3d0-ffffffff8189d3e2: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818cfab5)
Location: drivers/cpuidle/driver.c:312
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff818cf780-ffffffff818cf792: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff819a1d80)
Location: drivers/cpuidle/driver.c:318
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff819a1d80-ffffffff819a1d92: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff819a4d50)
Location: drivers/cpuidle/driver.c:318
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff819a4d50-ffffffff819a4d62: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81989960)
Location: drivers/cpuidle/driver.c:322
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81989960-ffffffff81989972: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81a34130)
Location: drivers/cpuidle/driver.c:322
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81a34130-ffffffff81a34142: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81ba0910)
Location: drivers/cpuidle/driver.c:322
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81ba0910-ffffffff81ba0940: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81d42580)
Location: drivers/cpuidle/driver.c:322
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81d42580-ffffffff81d425b0: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81dac760)
Location: drivers/cpuidle/driver.c:326
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81dac760-ffffffff81dac790: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81e64800)
Location: drivers/cpuidle/driver.c:326
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81e64800-ffffffff81e64830: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffff800010b276e0)
Location: drivers/cpuidle/driver.c:312
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
  - drivers/cpuidle/sysfs.c:show_current_driver
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffff800010b276e0-ffff800010b27720: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (c0c029d8)
Location: drivers/cpuidle/driver.c:312
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
c0c02518-c0c02558: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (c000000000c1f0cc)
Location: drivers/cpuidle/driver.c:312
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/cpuidle/sysfs.c:show_current_driver
  - drivers/cpuidle/cpuidle-pseries.c:pseries_cpuidle_cpu_dead
  - drivers/cpuidle/cpuidle-pseries.c:pseries_cpuidle_cpu_online
  - drivers/cpuidle/cpuidle-powernv.c:powernv_cpuidle_cpu_dead
  - drivers/cpuidle/cpuidle-powernv.c:powernv_cpuidle_cpu_online
```
**Symbols:**

```
c000000000c1eae0-c000000000c1eafc: cpuidle_get_driver (STB_GLOBAL)
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
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff81873555)
Location: drivers/cpuidle/driver.c:312
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff81873220-ffffffff81873232: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff8183d345)
Location: drivers/cpuidle/driver.c:312
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff8183d010-ffffffff8183d022: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818c4f65)
Location: drivers/cpuidle/driver.c:312
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff818c4c30-ffffffff818c4c42: cpuidle_get_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_driver *cpuidle_get_driver();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (ffffffff818e13b5)
Location: drivers/cpuidle/driver.c:312
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/cpuidle/sysfs.c:show_current_driver
```
**Symbols:**

```
ffffffff818e1040-ffffffff818e1068: cpuidle_get_driver (STB_GLOBAL)
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
