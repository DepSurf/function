# Function: <code>cpufreq_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816b1430)
Location: drivers/cpufreq/cpufreq.c:2418
Inline: True
Direct callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff816b1430-ffffffff816b167f: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81712940)
Location: drivers/cpufreq/cpufreq.c:2483
Inline: True
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
```
**Symbols:**

```
ffffffff81712940-ffffffff81712b72: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817439c0)
Location: drivers/cpufreq/cpufreq.c:2432
Inline: True
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
```
**Symbols:**

```
ffffffff817439c0-ffffffff81743c26: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81761fb0)
Location: drivers/cpufreq/cpufreq.c:2449
Inline: False
Direct callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81761fb0-ffffffff81762213: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d7f90)
Location: drivers/cpufreq/cpufreq.c:2482
Inline: False
Direct callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff817d7f90-ffffffff817d81f3: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818208e0)
Location: drivers/cpufreq/cpufreq.c:2480
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff818208e0-ffffffff81820b44: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184c790)
Location: drivers/cpufreq/cpufreq.c:2483
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff8184c790-ffffffff8184c9f4: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188f870)
Location: drivers/cpufreq/cpufreq.c:2650
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff8188f870-ffffffff8188fb0f: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c1a50)
Location: drivers/cpufreq/cpufreq.c:2644
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff818c1a50-ffffffff818c1d10: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2690
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff819966ba-ffffffff819966d2: cpufreq_register_driver.cold (STB_LOCAL)
ffffffff81993370-ffffffff81993644: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2767
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81c29724-ffffffff81c2973c: cpufreq_register_driver.cold (STB_LOCAL)
ffffffff81996520-ffffffff8199683c: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2773
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81c1bacb-ffffffff81c1bae3: cpufreq_register_driver.cold (STB_LOCAL)
ffffffff8197b2f0-ffffffff8197b5ff: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2782
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81d2bdcc-ffffffff81d2bde4: cpufreq_register_driver.cold (STB_LOCAL)
ffffffff81a24290-ffffffff81a24599: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2822
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81ef801c-ffffffff81ef8034: cpufreq_register_driver.cold (STB_LOCAL)
ffffffff81b8d9b0-ffffffff81b8dcbe: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d340)
Location: drivers/cpufreq/cpufreq.c:2819
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81d2d340-ffffffff81d2d65e: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d965b0)
Location: drivers/cpufreq/cpufreq.c:2826
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_register_driver
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81d965b0-ffffffff81d968e0: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e210)
Location: drivers/cpufreq/cpufreq.c:2868
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_register_driver
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81e4e210-ffffffff81e4e540: cpufreq_register_driver (STB_GLOBAL)
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
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b204d8)
Location: drivers/cpufreq/cpufreq.c:2644
Inline: False
```
**Symbols:**

```
ffff800010b204d8-ffff800010b20848: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfa4e0)
Location: drivers/cpufreq/cpufreq.c:2644
Inline: False
Direct callers:
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe
```
**Symbols:**

```
c0bfa4e0-c0bfa7c0: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c13780)
Location: drivers/cpufreq/cpufreq.c:2644
Inline: False
Direct callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
**Symbols:**

```
c000000000c13780-c000000000c13cb8: cpufreq_register_driver (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81866170)
Location: drivers/cpufreq/cpufreq.c:2644
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff81866170-ffffffff81866430: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182ee20)
Location: drivers/cpufreq/cpufreq.c:2644
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff8182ee20-ffffffff8182f0e0: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b6f00)
Location: drivers/cpufreq/cpufreq.c:2644
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff818b6f00-ffffffff818b71c0: cpufreq_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d3af0)
Location: drivers/cpufreq/cpufreq.c:2644
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
**Symbols:**

```
ffffffff818d3af0-ffffffff818d3db0: cpufreq_register_driver (STB_GLOBAL)
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
