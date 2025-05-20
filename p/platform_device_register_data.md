# Function: <code>platform_device_register_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/adp5520.c (ffffffff81593305)
Location: include/linux/platform_device.h:159
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/adp5520.c (ffffffff815e8145)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/adp5520.c (ffffffff81614f55)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
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
In drivers/mfd/adp5520.c (ffffffff81628f45)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff82106a1d)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
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
In drivers/mfd/adp5520.c (ffffffff8169185b)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8271037a)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
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
In drivers/acpi/acpi_apd.c (ffffffff815810dc)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff816cd991)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8273a618)
Location: include/linux/platform_device.h:160
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
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
In drivers/acpi/acpi_apd.c (ffffffff8159927c)
Location: include/linux/platform_device.h:161
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff816eef51)
Location: include/linux/platform_device.h:161
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff828f45f9)
Location: include/linux/platform_device.h:161
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_apd.c (ffffffff815ca620)
Location: include/linux/platform_device.h:164
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff817285e5)
Location: include/linux/platform_device.h:164
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8290fec1)
Location: include/linux/platform_device.h:164
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815ca620-ffffffff815ca684: platform_device_register_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113f844)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815eb830)
Location: include/linux/platform_device.h:170
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff8174c835)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff82919bd5)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815eb830-ffffffff815eb894: platform_device_register_data.constprop.0 (STB_LOCAL)
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
In kernel/time/alarmtimer.c (ffffffff8114e372)
Location: include/linux/platform_device.h:180
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81697390)
Location: include/linux/platform_device.h:180
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff8180a886)
Location: include/linux/platform_device.h:180
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff819c5c6b)
Location: include/linux/platform_device.h:180
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_setup_clks
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
In kernel/time/alarmtimer.c (ffffffff8114a602)
Location: include/linux/platform_device.h:189
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff816b4400)
Location: include/linux/platform_device.h:189
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff8181a1b6)
Location: include/linux/platform_device.h:189
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81c2d632)
Location: include/linux/platform_device.h:189
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_setup_clks
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
In kernel/time/alarmtimer.c (ffffffff8114babf)
Location: include/linux/platform_device.h:189
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81696630)
Location: include/linux/platform_device.h:189
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff817fd8d6)
Location: include/linux/platform_device.h:189
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81c1f9ca)
Location: include/linux/platform_device.h:189
Inline: True
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
In kernel/time/alarmtimer.c (ffffffff8116f7cf)
Location: include/linux/platform_device.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8170c3d0)
Location: include/linux/platform_device.h:186
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff81887676)
Location: include/linux/platform_device.h:186
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81d31246)
Location: include/linux/platform_device.h:186
Inline: True
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
In kernel/time/alarmtimer.c (ffffffff811a3d12)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8183aa53)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff819d0631)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81efd697)
Location: include/linux/platform_device.h:190
Inline: True
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
In kernel/time/alarmtimer.c (ffffffff811e3586)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff819700ba)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff81b49868)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81d713a9)
Location: include/linux/platform_device.h:190
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76c35)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/time/alarmtimer.c (ffffffff811f7bd6)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff819b6684)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff81b9ccb5)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81ddf05c)
Location: include/linux/platform_device.h:190
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4b75)
Location: include/linux/platform_device.h:190
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/time/alarmtimer.c (ffffffff8120dd76)
Location: include/linux/platform_device.h:218
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81a00c04)
Location: include/linux/platform_device.h:218
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff81bf0ca5)
Location: include/linux/platform_device.h:218
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81e94f9c)
Location: include/linux/platform_device.h:218
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ac65)
Location: include/linux/platform_device.h:218
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/time/alarmtimer.c (ffff8000101a9fd0)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/mfd/adp5520.c (ffff80001094ad0c)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (ffff8000114a1f60)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e9d4)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
```
```
In drivers/firmware/efi/arm-init.c (ffff8000114a7210)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:register_gop_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/alarmtimer.c (c03f4d54)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In fs/pstore/ram.c (c06d713c)
Location: include/linux/platform_device.h:170
Inline: True
Direct callers:
  - fs/pstore/ram.c:ramoops_init
```
```
In drivers/mfd/adp5520.c (c0a339a4)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (c15a3f84)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/cpufreq/ti-cpufreq.c (c0c01084)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_init
```
```
In drivers/firmware/efi/arm-init.c (c15a9cc4)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:register_gop_device
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc0a94)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
**Symbols:**

```
c06d713c-c06d71c8: platform_device_register_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/time.c (c000000001348b88)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:rtc_init
```
```
In kernel/time/alarmtimer.c (c00000000020ce90)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/mfd/adp5520.c (c0000000009f6664)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe000135230)
Location: include/linux/platform_device.h:170
Inline: True
```
```
In drivers/mfd/adp5520.c (ffffffe0005bc59c)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
</details>
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
In kernel/time/alarmtimer.c (ffffffff81137ff4)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff828fecde)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8112aa44)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815c6250)
Location: include/linux/platform_device.h:170
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff828f6841)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815c6250-ffffffff815c62b4: platform_device_register_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81135d14)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815dfb10)
Location: include/linux/platform_device.h:170
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff8173fcf5)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff82913f70)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815dfb10-ffffffff815dfb74: platform_device_register_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81142764)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815f99d0)
Location: include/linux/platform_device.h:170
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/mfd/adp5520.c (ffffffff8175b135)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8291ac37)
Location: include/linux/platform_device.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815f99d0-ffffffff815f9a34: platform_device_register_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
