# Function: <code>early_acpi_process_madt</code>

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
In arch/x86/kernel/acpi/boot.c (ffffffff81f6e46a)
Location: arch/x86/kernel/acpi/boot.c:1187
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff81f9687d)
Location: arch/x86/kernel/acpi/boot.c:1203
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff81fd1db1)
Location: arch/x86/kernel/acpi/boot.c:1200
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff820b29b9)
Location: arch/x86/kernel/acpi/boot.c:1216
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff826b91f3)
Location: arch/x86/kernel/acpi/boot.c:1239
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff826e2f60)
Location: arch/x86/kernel/acpi/boot.c:1246
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff828998c6)
Location: arch/x86/kernel/acpi/boot.c:1248
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b15d4)
Location: arch/x86/kernel/acpi/boot.c:1234
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b4a23)
Location: arch/x86/kernel/acpi/boot.c:1234
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_acpi_process_madt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd8fb5)
Location: arch/x86/kernel/acpi/boot.c:1235
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
**Symbols:**

```
ffffffff82cd8fb5-ffffffff82cd9064: early_acpi_process_madt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_acpi_process_madt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc53d3)
Location: arch/x86/kernel/acpi/boot.c:1235
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
**Symbols:**

```
ffffffff82fc53d3-ffffffff82fc5482: early_acpi_process_madt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff831d099b)
Location: arch/x86/kernel/acpi/boot.c:1235
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff832b2ee6)
Location: arch/x86/kernel/acpi/boot.c:1221
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff8346448a)
Location: arch/x86/kernel/acpi/boot.c:1312
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff83e87387)
Location: arch/x86/kernel/acpi/boot.c:1325
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff836aa927)
Location: arch/x86/kernel/acpi/boot.c:1334
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff838db107)
Location: arch/x86/kernel/acpi/boot.c:1329
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828a2a42)
Location: arch/x86/kernel/acpi/boot.c:1234
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8289ab84)
Location: arch/x86/kernel/acpi/boot.c:1234
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b593f)
Location: arch/x86/kernel/acpi/boot.c:1234
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5a26)
Location: arch/x86/kernel/acpi/boot.c:1234
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
