# Function: <code>cpuhp_remove_state_nocalls</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff820e6ec9)
Location: include/linux/cpuhotplug.h:162
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff810829d0)
Location: include/linux/cpuhotplug.h:270
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In mm/zswap.c (ffffffff81ff1f91)
Location: include/linux/cpuhotplug.h:270
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In drivers/acpi/processor_driver.c (ffffffff821cd536)
Location: include/linux/cpuhotplug.h:270
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8174397d)
Location: include/linux/cpuhotplug.h:270
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff821ce651)
Location: include/linux/cpuhotplug.h:270
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff810198bd)
Location: include/linux/cpuhotplug.h:302
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff822c26e9)
Location: include/linux/cpuhotplug.h:302
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff822c3896)
Location: include/linux/cpuhotplug.h:302
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101a19d)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff828d58cf)
Location: include/linux/cpuhotplug.h:330
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828d6adb)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ab87)
Location: include/linux/cpuhotplug.h:329
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff8290718e)
Location: include/linux/cpuhotplug.h:329
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82908441)
Location: include/linux/cpuhotplug.h:329
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b357)
Location: include/linux/cpuhotplug.h:335
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff82adef30)
Location: include/linux/cpuhotplug.h:335
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82ae026f)
Location: include/linux/cpuhotplug.h:335
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ce6f)
Location: include/linux/cpuhotplug.h:340
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff82b04071)
Location: include/linux/cpuhotplug.h:340
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82b052a5)
Location: include/linux/cpuhotplug.h:340
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d7ef)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff82b12f4c)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82b14211)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101fc62)
Location: include/linux/cpuhotplug.h:347
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff82f249d3)
Location: include/linux/cpuhotplug.h:347
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199af82)
Location: include/linux/cpuhotplug.h:347
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81020702)
Location: include/linux/cpuhotplug.h:352
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff8321cf73)
Location: include/linux/cpuhotplug.h:352
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81c29a04)
Location: include/linux/cpuhotplug.h:352
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81022a9f)
Location: include/linux/cpuhotplug.h:360
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff83450f34)
Location: include/linux/cpuhotplug.h:360
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81c1bdd8)
Location: include/linux/cpuhotplug.h:360
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8102693f)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff835444fc)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d2c27f)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8102aaf1)
Location: include/linux/cpuhotplug.h:451
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff837226d3)
Location: include/linux/cpuhotplug.h:451
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81ef8520)
Location: include/linux/cpuhotplug.h:451
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031711)
Location: include/linux/cpuhotplug.h:455
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff842b0920)
Location: include/linux/cpuhotplug.h:455
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031711)
Location: include/linux/cpuhotplug.h:453
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff83af3510)
Location: include/linux/cpuhotplug.h:453
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81037a01)
Location: include/linux/cpuhotplug.h:438
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff83d4f240)
Location: include/linux/cpuhotplug.h:438
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100b62ac)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_exit
  - virt/kvm/kvm_main.c:kvm_init
```
```
In drivers/acpi/processor_driver.c (ffff8000114b93d0)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/cache-l2x0-pmu.c (c150b2a8)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
```
```
In arch/arm/common/bL_switcher.c (c150be60)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_init
```
```
In drivers/cpuidle/coupled.c (c15a4534)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_coupled_init
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d7ef)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff82af3112)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82af40dd)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff82ac3504)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82ac44b8)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d7af)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff82b0e238)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82b0f54b)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d9ff)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff82b02d84)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82b04049)
Location: include/linux/cpuhotplug.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
</ul>

## Differences
