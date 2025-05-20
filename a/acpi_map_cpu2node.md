# Function: <code>acpi_map_cpu2node</code>

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
In arch/x86/kernel/acpi/boot.c (ffffffff8104f894)
Location: arch/x86/kernel/acpi/boot.c:701
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff8104f9c9)
Location: arch/x86/kernel/acpi/boot.c:708
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_map_cpu2node(acpi_handle handle, int cpu, int physid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81052300)
Location: arch/x86/kernel/acpi/boot.c:712
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - drivers/acpi/processor_core.c:set_processor_node_mapping
```
**Symbols:**

```
ffffffff81052300-ffffffff81052335: acpi_map_cpu2node (STB_GLOBAL)
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
In arch/x86/kernel/acpi/boot.c (ffffffff81051d06)
Location: arch/x86/kernel/acpi/boot.c:727
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff81055976)
Location: arch/x86/kernel/acpi/boot.c:745
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff810587fa)
Location: arch/x86/kernel/acpi/boot.c:751
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff8105e41a)
Location: arch/x86/kernel/acpi/boot.c:752
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff8106182a)
Location: arch/x86/kernel/acpi/boot.c:735
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff810620ba)
Location: arch/x86/kernel/acpi/boot.c:735
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81067fea)
Location: arch/x86/kernel/acpi/boot.c:736
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81069cea)
Location: arch/x86/kernel/acpi/boot.c:736
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff8106a7ba)
Location: arch/x86/kernel/acpi/boot.c:736
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff8107502e)
Location: arch/x86/kernel/acpi/boot.c:734
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff81083cae)
Location: arch/x86/kernel/acpi/boot.c:802
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff81096a7a)
Location: arch/x86/kernel/acpi/boot.c:815
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff81099b9a)
Location: arch/x86/kernel/acpi/boot.c:824
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff810a13ca)
Location: arch/x86/kernel/acpi/boot.c:833
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff81061c3a)
Location: arch/x86/kernel/acpi/boot.c:735
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff8105200a)
Location: arch/x86/kernel/acpi/boot.c:735
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff8106205a)
Location: arch/x86/kernel/acpi/boot.c:735
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
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
In arch/x86/kernel/acpi/boot.c (ffffffff8106361a)
Location: arch/x86/kernel/acpi/boot.c:735
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
