# Function: <code>validate_apic_and_package_id</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff8104080d)
Location: arch/x86/kernel/cpu/common.c:989
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8103e78d)
Location: arch/x86/kernel/cpu/common.c:1050
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8104140d)
Location: arch/x86/kernel/cpu/common.c:1162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81042dad)
Location: arch/x86/kernel/cpu/common.c:1270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff810443cd)
Location: arch/x86/kernel/cpu/common.c:1276
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8104697d)
Location: arch/x86/kernel/cpu/common.c:1377
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff810470fd)
Location: arch/x86/kernel/cpu/common.c:1407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void validate_apic_and_package_id(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1415
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
**Symbols:**

```
ffffffff81049fb0-ffffffff8104a016: validate_apic_and_package_id (STB_LOCAL)
ffffffff8104b559-ffffffff8104b576: validate_apic_and_package_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void validate_apic_and_package_id(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1479
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
**Symbols:**

```
ffffffff81049450-ffffffff810494b6: validate_apic_and_package_id (STB_LOCAL)
ffffffff81bd4f27-ffffffff81bd4f44: validate_apic_and_package_id.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff8104bc7d)
Location: arch/x86/kernel/cpu/common.c:1480
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8105300d)
Location: arch/x86/kernel/cpu/common.c:1515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8105ea51)
Location: arch/x86/kernel/cpu/common.c:1748
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8106d05c)
Location: arch/x86/kernel/cpu/common.c:1774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8106e9bc)
Location: arch/x86/kernel/cpu/common.c:1781
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81075cac)
Location: arch/x86/kernel/cpu/common.c:1827
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8104727d)
Location: arch/x86/kernel/cpu/common.c:1407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8103636d)
Location: arch/x86/kernel/cpu/common.c:1407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff810470bd)
Location: arch/x86/kernel/cpu/common.c:1407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff810484bd)
Location: arch/x86/kernel/cpu/common.c:1407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
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
