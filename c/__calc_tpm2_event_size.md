# Function: <code>__calc_tpm2_event_size</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff816b1b8f)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff8290e1b7)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff816d486f)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff82917baa)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81788c17)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff819bcb5f)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Direct callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81788930-ffffffff81788a4b: __calc_tpm2_event_size.constprop.0 (STB_LOCAL)
ffffffff819bcb5f-ffffffff819bcd11: __calc_tpm2_event_size.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff8179fb17)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff81c2b95a)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Direct callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff8179f830-ffffffff8179f94b: __calc_tpm2_event_size.constprop.0 (STB_LOCAL)
ffffffff81c2b95a-ffffffff81c2bb0c: __calc_tpm2_event_size.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff817827c0)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff81c1dcdc)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Direct callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff817824e0-ffffffff817825fe: __calc_tpm2_event_size.constprop.0 (STB_LOCAL)
ffffffff81c1dcdc-ffffffff81c1de8b: __calc_tpm2_event_size.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81809180)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
Direct callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff81d2f180)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Direct callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81808ea0-ffffffff81808fbe: __calc_tpm2_event_size.constprop.0 (STB_LOCAL)
ffffffff81d2f180-ffffffff81d2f32f: __calc_tpm2_event_size.constprop.0 (STB_LOCAL)
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81948e75)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:calc_tpm2_event_size
```
```
In drivers/firmware/efi/tpm.c (ffffffff834c70df)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81aac3b5)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:calc_tpm2_event_size
```
```
In drivers/firmware/efi/tpm.c (ffffffff83f0840f)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81af7c15)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:calc_tpm2_event_size
```
```
In drivers/firmware/efi/tpm.c (ffffffff8372e555)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81b4b235)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:calc_tpm2_event_size
```
```
In drivers/firmware/efi/tpm.c (ffffffff83962955)
Location: include/linux/tpm_eventlog.h:160
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
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
In drivers/firmware/efi/libstub/tpm.c (ffff80001144176c)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/libstub/tpm.c:efi_retrieve_tpm2_eventlog
  - drivers/firmware/efi/libstub/tpm.c:efi_retrieve_tpm2_eventlog
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffff8000108bf5a4)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffff8000114a649c)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/char/tpm/eventlog/tpm2.c (c09b89b4)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (c15a886c)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/char/tpm/eventlog/tpm2.c (c000000000961e18)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffe000571b04)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff8169a2bf)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff828fcfb0)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81677caf)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff828f484c)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff816c852f)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff829121df)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/char/tpm/eventlog/tpm2.c (ffffffff816e2a0f)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/firmware/efi/tpm.c (ffffffff82918c0c)
Location: include/linux/tpm_eventlog.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
</details>
</li>
</ul>

## Differences
