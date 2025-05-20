# Function: <code>of_get_next_cpu_node</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct device_node *of_get_next_cpu_node(struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6afe0)
Location: drivers/of/base.c:808
Inline: False
Direct callers:
  - arch/arm64/kernel/smp.c:smp_init_cpus
  - arch/arm64/kernel/smp.c:smp_init_cpus
  - drivers/of/base.c:of_get_cpu_node
  - drivers/of/of_numa.c:of_numa_init
  - drivers/of/of_numa.c:of_numa_init
```
**Symbols:**

```
ffff800010b6afe0-ffff800010b6b138: of_get_next_cpu_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_get_next_cpu_node(struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4e464)
Location: drivers/of/base.c:808
Inline: False
Direct callers:
  - arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps
  - arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps
  - arch/arm/mach-shmobile/timer.c:shmobile_init_delay
  - arch/arm/mach-shmobile/timer.c:shmobile_init_delay
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_init_pm_domains
  - drivers/of/base.c:of_get_cpu_node
```
**Symbols:**

```
c0c4e464-c0c4e544: of_get_next_cpu_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_get_next_cpu_node(struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c44b10)
Location: drivers/of/base.c:808
Inline: False
Direct callers:
  - drivers/of/base.c:of_get_cpu_node
```
**Symbols:**

```
c000000000c44b10-c000000000c44c64: of_get_next_cpu_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_get_next_cpu_node(struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe0007205ea)
Location: drivers/of/base.c:808
Inline: False
Direct callers:
  - arch/riscv/kernel/cpufeature.c:riscv_fill_hwcap
  - arch/riscv/kernel/cpufeature.c:riscv_fill_hwcap
  - arch/riscv/kernel/smpboot.c:setup_smp
  - arch/riscv/kernel/smpboot.c:setup_smp
  - drivers/of/base.c:of_get_cpu_node
```
**Symbols:**

```
ffffffe0007205ea-ffffffe0007206c2: of_get_next_cpu_node (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
