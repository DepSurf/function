# Function: <code>pm_suspend_via_firmware</code>

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
In drivers/input/serio/i8042.c (ffffffff81665943)
Location: include/linux/suspend.h:225
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/input/serio/i8042.c (ffffffff816c5bb8)
Location: include/linux/suspend.h:224
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
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
In drivers/input/serio/i8042.c (ffffffff816f3bd8)
Location: include/linux/suspend.h:224
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81709728)
Location: include/linux/suspend.h:226
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8177a8d8)
Location: include/linux/suspend.h:230
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817bb168)
Location: include/linux/suspend.h:230
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817e25d8)
Location: include/linux/suspend.h:230
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
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
In drivers/input/serio/i8042.c (ffffffff81822f73)
Location: include/linux/suspend.h:256
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bcc6e)
Location: include/linux/suspend.h:256
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
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
In drivers/input/serio/i8042.c (ffffffff81854413)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818ef78e)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
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
In drivers/char/tpm/tpm-interface.c (ffffffff81783dd6)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff81926b83)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c49ee)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
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
In drivers/char/tpm/tpm-interface.c (ffffffff8179b326)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff8192e6f3)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c4cde)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
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
In drivers/pci/quirks.c (ffffffff8164c4f6)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8177de66)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff81911ab3)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a9c9e)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
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
In drivers/pci/quirks.c (ffffffff816be587)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81804056)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff819b330a)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a572c1)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
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
In drivers/pci/quirks.c (ffffffff817e44b7)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81943973)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff81b1243a)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc6d0f)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
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
In drivers/pci/quirks.c (ffffffff81908b57)
Location: include/linux/suspend.h:258
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa647c)
Location: include/linux/suspend.h:258
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff81ca2eea)
Location: include/linux/suspend.h:258
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6ef9f)
Location: include/linux/suspend.h:258
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
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
In drivers/pci/quirks.c (ffffffff8194c1a7)
Location: include/linux/suspend.h:262
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81af1c9c)
Location: include/linux/suspend.h:262
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff81d0a5aa)
Location: include/linux/suspend.h:262
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddc811)
Location: include/linux/suspend.h:262
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume_common
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
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
In drivers/pci/quirks.c (ffffffff81995477)
Location: include/linux/suspend.h:262
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81b4522c)
Location: include/linux/suspend.h:262
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff81dc023a)
Location: include/linux/suspend.h:262
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c000000000b72330)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/pci.c (0)
Location: include/linux/suspend.h:338
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/suspend.h:338
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (0)
Location: include/linux/suspend.h:338
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
In drivers/nvme/host/pci.c (ffffffff8172ff2b)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff817d0bd3)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8184abb4)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
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
In drivers/input/serio/i8042.c (ffffffff818485a3)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e45be)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
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
In drivers/input/serio/i8042.c (ffffffff81863823)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8190121e)
Location: include/linux/suspend.h:257
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
</details>
</li>
</ul>

## Differences
