# Function: <code>acpi_processor_setup_cpuidle_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fcadf)
Location: drivers/acpi/processor_idle.c:1311
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff814fcadf-ffffffff814fcb78: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8151f75b)
Location: drivers/acpi/processor_idle.c:1312
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff8151f75b-ffffffff8151f7f4: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81530c90)
Location: drivers/acpi/processor_idle.c:1312
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81530c90-ffffffff81530d42: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81591c90)
Location: drivers/acpi/processor_idle.c:1321
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81591c90-ffffffff81591d4a: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815c9020)
Location: drivers/acpi/processor_idle.c:1325
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff815c9020-ffffffff815c90d9: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815e25f0)
Location: drivers/acpi/processor_idle.c:1326
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff815e25f0-ffffffff815e26a9: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81614180)
Location: drivers/acpi/processor_idle.c:1321
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81614180-ffffffff81614234: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81635670)
Location: drivers/acpi/processor_idle.c:1321
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81635670-ffffffff81635724: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e2320)
Location: drivers/acpi/processor_idle.c:1181
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff816e2320-ffffffff816e23c1: acpi_processor_setup_cpuidle_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81700409)
Location: drivers/acpi/processor_idle.c:1201
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e1b20)
Location: drivers/acpi/processor_idle.c:1235
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff816e1b20-ffffffff816e1c4b: acpi_processor_setup_cpuidle_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8175a0f0)
Location: drivers/acpi/processor_idle.c:1236
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff8175a0f0-ffffffff8175a327: acpi_processor_setup_cpuidle_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8188d3e0)
Location: drivers/acpi/processor_idle.c:1245
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff8188d3e0-ffffffff8188d65b: acpi_processor_setup_cpuidle_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819d4d20)
Location: drivers/acpi/processor_idle.c:1264
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff819d4d20-ffffffff819d4f9b: acpi_processor_setup_cpuidle_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a1c660)
Location: drivers/acpi/processor_idle.c:1266
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81a1c660-ffffffff81a1c8d9: acpi_processor_setup_cpuidle_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a67940)
Location: drivers/acpi/processor_idle.c:1265
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81a67940-ffffffff81a67bb9: acpi_processor_setup_cpuidle_dev.isra.0 (STB_LOCAL)
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
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffff8000107a2b40)
Location: drivers/acpi/processor_idle.c:1321
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffff8000107a2b40-ffff8000107a2ba4: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81604e60)
Location: drivers/acpi/processor_idle.c:1321
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81604e60-ffffffff81604f14: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815eff10)
Location: drivers/acpi/processor_idle.c:1321
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff815eff10-ffffffff815effc4: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81629950)
Location: drivers/acpi/processor_idle.c:1321
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81629950-ffffffff81629a04: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_dev(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816437f0)
Location: drivers/acpi/processor_idle.c:1321
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff816437f0-ffffffff816438a4: acpi_processor_setup_cpuidle_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
