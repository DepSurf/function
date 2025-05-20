# Function: <code>ktime_ms_delta</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815253bf)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8103ee7a)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537d07)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81041f2e)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159956d)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81043e38)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d0dec)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81045838)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea41c)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048008)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c1db)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810488b8)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163dc2b)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104cb28)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eaffc)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104bd1e)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8170875c)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104d84e)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9d5c)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81054f6b)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817635dd)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8189753f)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff819df344)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a27054)
Location: include/linux/ktime.h:174
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In mm/ksm.c (ffffffff8148cef6)
Location: include/linux/ktime.h:172
Inline: True
Inline callers:
  - mm/ksm.c:scan_time_advisor
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a72064)
Location: include/linux/ktime.h:172
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3afe)
Location: include/linux/ktime.h:172
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:commit_tail
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
In drivers/acpi/cppc_acpi.c (ffff8000107a8b20)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
</details>
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
In arch/powerpc/platforms/pseries/lpar.c (c0000000000e9080)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048a28)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160965b)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81037cf8)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb29b)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048868)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81631a6b)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81049c78)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164bd9b)
Location: include/linux/ktime.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
</details>
</li>
</ul>

## Differences
