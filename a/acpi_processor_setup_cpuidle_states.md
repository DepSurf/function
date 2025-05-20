# Function: <code>acpi_processor_setup_cpuidle_states</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_setup_cpuidle_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814accb8)
Location: drivers/acpi/processor_idle.c:905
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff814accb8-ffffffff814ace30: acpi_processor_setup_cpuidle_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_setup_cpuidle_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fc553)
Location: drivers/acpi/processor_idle.c:1284
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff814fc553-ffffffff814fc768: acpi_processor_setup_cpuidle_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_setup_cpuidle_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8151f1e7)
Location: drivers/acpi/processor_idle.c:1285
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff8151f1e7-ffffffff8151f3fc: acpi_processor_setup_cpuidle_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8153103d)
Location: drivers/acpi/processor_idle.c:1285
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff8152fa20-ffffffff8152fc74: acpi_processor_setup_cpuidle_states.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8159202d)
Location: drivers/acpi/processor_idle.c:1294
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff815906b0-ffffffff8159090f: acpi_processor_setup_cpuidle_states.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815c9412)
Location: drivers/acpi/processor_idle.c:1298
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff815c7a50-ffffffff815c7cab: acpi_processor_setup_cpuidle_states.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815e29e2)
Location: drivers/acpi/processor_idle.c:1299
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff815e1010-ffffffff815e126f: acpi_processor_setup_cpuidle_states.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81614577)
Location: drivers/acpi/processor_idle.c:1294
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff81612b90-ffffffff81612ddc: acpi_processor_setup_cpuidle_states.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81635a67)
Location: drivers/acpi/processor_idle.c:1294
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff81634090-ffffffff816342dc: acpi_processor_setup_cpuidle_states.part.0 (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff816e1d00)
Location: drivers/acpi/processor_idle.c:1154
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff816e1d00-ffffffff816e1d50: acpi_processor_setup_cpuidle_states.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816ffa0c)
Location: drivers/acpi/processor_idle.c:1174
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff816ff9d0-ffffffff816ffb0c: acpi_processor_setup_cpuidle_states.isra.0 (STB_LOCAL)
ffffffff81c02b01-ffffffff81c02b19: acpi_processor_setup_cpuidle_states.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff816e157c)
Location: drivers/acpi/processor_idle.c:1208
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff816e1540-ffffffff816e167c: acpi_processor_setup_cpuidle_states.isra.0 (STB_LOCAL)
ffffffff81bf4518-ffffffff81bf4530: acpi_processor_setup_cpuidle_states.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff81759a10)
Location: drivers/acpi/processor_idle.c:1209
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff81759a10-ffffffff81759ab6: acpi_processor_setup_cpuidle_states.isra.0 (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff8188cee0)
Location: drivers/acpi/processor_idle.c:1218
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff8188cee0-ffffffff8188cfab: acpi_processor_setup_cpuidle_states.isra.0 (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff819d47d0)
Location: drivers/acpi/processor_idle.c:1237
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff819d47d0-ffffffff819d489b: acpi_processor_setup_cpuidle_states.isra.0 (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff81a1c0f0)
Location: drivers/acpi/processor_idle.c:1239
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff81a1c0f0-ffffffff81a1c1b9: acpi_processor_setup_cpuidle_states.isra.0 (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff81a673d0)
Location: drivers/acpi/processor_idle.c:1238
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff81a673d0-ffffffff81a67499: acpi_processor_setup_cpuidle_states.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffff8000107a2ef0)
Location: drivers/acpi/processor_idle.c:1294
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffff8000107a24a8-ffff8000107a25cc: acpi_processor_setup_cpuidle_states.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81605257)
Location: drivers/acpi/processor_idle.c:1294
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff81603be0-ffffffff81603e2c: acpi_processor_setup_cpuidle_states.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815f0307)
Location: drivers/acpi/processor_idle.c:1294
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff815eec90-ffffffff815eeedc: acpi_processor_setup_cpuidle_states.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81629d47)
Location: drivers/acpi/processor_idle.c:1294
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff81628370-ffffffff816285bc: acpi_processor_setup_cpuidle_states.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81643be7)
Location: drivers/acpi/processor_idle.c:1294
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
```
**Symbols:**

```
ffffffff81642220-ffffffff8164246c: acpi_processor_setup_cpuidle_states.part.0 (STB_LOCAL)
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
</ul>
