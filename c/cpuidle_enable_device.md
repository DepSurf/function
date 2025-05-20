# Function: <code>cpuidle_enable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff816bb450)
Location: drivers/cpuidle/cpuidle.c:359
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff816bb450-ffffffff816bb4d3: cpuidle_enable_device.part.6 (STB_LOCAL)
ffffffff816bb4e0-ffffffff816bb503: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8171ce87)
Location: drivers/cpuidle/cpuidle.c:359
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8171ccd0-ffffffff8171cd62: cpuidle_enable_device.part.6 (STB_LOCAL)
ffffffff8171cd70-ffffffff8171cd94: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8174fa37)
Location: drivers/cpuidle/cpuidle.c:376
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8174f880-ffffffff8174f912: cpuidle_enable_device.part.8 (STB_LOCAL)
ffffffff8174f920-ffffffff8174f944: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8176e4d8)
Location: drivers/cpuidle/cpuidle.c:379
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8176e310-ffffffff8176e3b3: cpuidle_enable_device.part.8 (STB_LOCAL)
ffffffff8176e3c0-ffffffff8176e3e4: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff817e3c20)
Location: drivers/cpuidle/cpuidle.c:380
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff817e3c20-ffffffff817e3ccb: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8182ce20)
Location: drivers/cpuidle/cpuidle.c:395
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8182ce20-ffffffff8182cecb: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81858e00)
Location: drivers/cpuidle/cpuidle.c:424
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff81858e00-ffffffff81858eab: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8189c740)
Location: drivers/cpuidle/cpuidle.c:438
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8189c740-ffffffff8189c7e2: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818cea60)
Location: drivers/cpuidle/cpuidle.c:469
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff818cea60-ffffffff818ceb02: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff819a0fa0)
Location: drivers/cpuidle/cpuidle.c:472
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff819a0fa0-ffffffff819a1042: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff819a3ff0)
Location: drivers/cpuidle/cpuidle.c:497
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff819a3ff0-ffffffff819a4092: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81988b70)
Location: drivers/cpuidle/cpuidle.c:497
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff81988b70-ffffffff81988c12: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81a32c10)
Location: drivers/cpuidle/cpuidle.c:497
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff81a32c10-ffffffff81a32cb2: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81b9f390)
Location: drivers/cpuidle/cpuidle.c:497
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/cpuidle/governor.c:cpuidle_switch_governor
```
**Symbols:**

```
ffffffff81b9f390-ffffffff81b9f441: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81d40d90)
Location: drivers/cpuidle/cpuidle.c:502
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/cpuidle/governor.c:cpuidle_switch_governor
```
**Symbols:**

```
ffffffff81d40d90-ffffffff81d40e41: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81dab760)
Location: drivers/cpuidle/cpuidle.c:534
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/cpuidle/governor.c:cpuidle_switch_governor
```
**Symbols:**

```
ffffffff81dab760-ffffffff81dab811: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81e63800)
Location: drivers/cpuidle/cpuidle.c:534
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/cpuidle/governor.c:cpuidle_switch_governor
```
**Symbols:**

```
ffffffff81e63800-ffffffff81e638b1: cpuidle_enable_device (STB_GLOBAL)
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
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffff800010b266e8)
Location: drivers/cpuidle/cpuidle.c:469
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffff800010b266e8-ffff800010b267dc: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c0c01470)
Location: drivers/cpuidle/cpuidle.c:469
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
c0c01470-c0c01548: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c000000000c1d5d0)
Location: drivers/cpuidle/cpuidle.c:469
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/cpuidle/cpuidle-pseries.c:pseries_cpuidle_cpu_online
  - drivers/cpuidle/cpuidle-powernv.c:powernv_cpuidle_cpu_online
```
**Symbols:**

```
c000000000c1d5d0-c000000000c1d760: cpuidle_enable_device (STB_GLOBAL)
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
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81872660)
Location: drivers/cpuidle/cpuidle.c:469
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff81872660-ffffffff81872702: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8183c300)
Location: drivers/cpuidle/cpuidle.c:469
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8183c300-ffffffff8183c3a2: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818c3f10)
Location: drivers/cpuidle/cpuidle.c:469
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff818c3f10-ffffffff818c3fb2: cpuidle_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_enable_device(struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818e0280)
Location: drivers/cpuidle/cpuidle.c:469
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff818e0280-ffffffff818e0322: cpuidle_enable_device (STB_GLOBAL)
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
