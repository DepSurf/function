# Function: <code>kstrtou32_from_user</code>

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
In fs/proc/base.c (ffffffff8127a580)
Location: include/linux/kernel.h:381
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
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
In fs/proc/base.c (ffffffff812a7270)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
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
In fs/proc/base.c (ffffffff812bcba0)
Location: include/linux/kernel.h:392
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8177a77a)
Location: include/linux/kernel.h:392
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff812c9f50)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81798bea)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff812ee7e0)
Location: include/linux/kernel.h:442
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8180f663)
Location: include/linux/kernel.h:442
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff8131b7f4)
Location: include/linux/kernel.h:458
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818594fa)
Location: include/linux/kernel.h:458
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff81332884)
Location: include/linux/kernel.h:491
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8187875a)
Location: include/linux/kernel.h:491
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff8135a809)
Location: include/linux/kernel.h:450
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bd5fa)
Location: include/linux/kernel.h:450
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff81372a19)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818f011a)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff813bad67)
Location: include/linux/kernel.h:443
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c4175)
Location: include/linux/kernel.h:443
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff813cc8a6)
Location: include/linux/kernel.h:295
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c44d5)
Location: include/linux/kernel.h:295
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff813d3866)
Location: include/linux/kernel.h:305
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a9bcb)
Location: include/linux/kernel.h:305
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff81424e16)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a56b65)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff8149db85)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc62d3)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff81532805)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6f123)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff8156a9f8)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddc6b3)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a33d8)
Location: include/linux/kstrtox.h:122
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043d07c)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0602f04)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000550f28)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d5936)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
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
In fs/proc/base.c (ffffffff8136aff9)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8189144a)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff8135ba89)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8184a70a)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff81368ac9)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e4f4a)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
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
In fs/proc/base.c (ffffffff8137c148)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - fs/proc/base.c:proc_loginuid_write
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81901baa)
Location: include/linux/kernel.h:454
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
```
</details>
</li>
</ul>

## Differences
