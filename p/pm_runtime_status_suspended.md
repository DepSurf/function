# Function: <code>pm_runtime_status_suspended</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:102
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:102
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:101
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:101
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:91
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
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
In drivers/base/power/runtime.c (ffffffff817c97c5)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/wakeirq.c (ffffffff817ca5d8)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff817cb9dc)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (ffffffff817d13d8)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/runtime.c (ffffffff817de2c5)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
```
```
In drivers/base/power/wakeirq.c (ffffffff817df088)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff817e044c)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (ffffffff817e58e8)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/runtime.c (ffffffff817c26c5)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
```
```
In drivers/base/power/wakeirq.c (ffffffff817c3488)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff817c4fac)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (ffffffff817c99d8)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/runtime.c (ffffffff8184c285)
Location: include/linux/pm_runtime.h:158
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
```
```
In drivers/base/power/wakeirq.c (ffffffff8184d7f8)
Location: include/linux/pm_runtime.h:158
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff8184f37c)
Location: include/linux/pm_runtime.h:158
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (ffffffff81853ef8)
Location: include/linux/pm_runtime.h:158
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/runtime.c (ffffffff81991c55)
Location: include/linux/pm_runtime.h:188
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/wakeirq.c (ffffffff81992d08)
Location: include/linux/pm_runtime.h:188
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff819943ae)
Location: include/linux/pm_runtime.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (ffffffff8199a488)
Location: include/linux/pm_runtime.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/runtime.c (ffffffff81b020c5)
Location: include/linux/pm_runtime.h:192
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/wakeirq.c (ffffffff81b032a8)
Location: include/linux/pm_runtime.h:192
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff81b04dce)
Location: include/linux/pm_runtime.h:192
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (ffffffff81b0b750)
Location: include/linux/pm_runtime.h:192
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/runtime.c (ffffffff81b501b5)
Location: include/linux/pm_runtime.h:192
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/main.c (ffffffff81b52689)
Location: include/linux/pm_runtime.h:192
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (ffffffff81b59790)
Location: include/linux/pm_runtime.h:192
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/pmdomain/core.c (ffffffff81aa1150)
Location: include/linux/pm_runtime.h:190
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_finish_resume
  - drivers/pmdomain/core.c:genpd_finish_suspend
```
```
In drivers/base/power/runtime.c (ffffffff81ba8735)
Location: include/linux/pm_runtime.h:190
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/main.c (ffffffff81baad39)
Location: include/linux/pm_runtime.h:190
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
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
In arch/arm/mach-omap2/omap_device.c (c033b0e8)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_device.c:_od_suspend_noirq
  - arch/arm/mach-omap2/omap_device.c:_omap_device_notifier_call
```
```
In drivers/bus/ti-sysc.c (c08287b4)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_child_suspend_noirq
```
```
In drivers/dma/tegra20-apb-dma.c (c0929ecc)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_remove
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/iommu/omap-iommu.c (c09c295c)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_prepare
```
```
In drivers/base/power/runtime.c (c09e8764)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/wakeirq.c (c09e937c)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (c09ead88)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (c09f2714)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfba0)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_suspend
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
In drivers/base/power/runtime.c (c000000000999934)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/wakeirq.c (c00000000099bf60)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (c00000000099e340)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/base/power/domain.c (c0000000009a75dc)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
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
In drivers/base/power/runtime.c (ffffffe00058bf2c)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/wakeirq.c (ffffffe00058d212)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
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
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_runtime.h:90
Inline: True
```
</details>
</li>
</ul>

## Differences
