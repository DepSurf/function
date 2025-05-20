# Function: <code>of_reconfig_notifier_register</code>

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
int of_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b70300)
Location: drivers/of/dynamic.c:54
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/of/platform.c:of_platform_register_reconfig_notifier
```
**Symbols:**

```
ffff800010b70300-ffff800010b70334: of_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c0c52bbc)
Location: drivers/of/dynamic.c:54
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/of/platform.c:of_platform_register_reconfig_notifier
```
**Symbols:**

```
c0c52bbc-c0c52be4: of_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c000000000c4b700)
Location: drivers/of/dynamic.c:54
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/iommu.c:iommu_init_early_pSeries
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:__machine_initcall_pseries_pseries_cpu_hotplug_init
  - arch/powerpc/platforms/pseries/hotplug-memory.c:__machine_initcall_pseries_pseries_memory_hotplug_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/of/platform.c:of_platform_register_reconfig_notifier
```
**Symbols:**

```
c000000000c4b700-c000000000c4b740: of_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffffffe00072454e)
Location: drivers/of/dynamic.c:54
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/of/platform.c:of_platform_register_reconfig_notifier
```
**Symbols:**

```
ffffffe00072454e-ffffffe000724580: of_reconfig_notifier_register (STB_GLOBAL)
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
