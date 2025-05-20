# Function: <code>cpu_hotplug_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081440)
Location: kernel/cpu.c:146
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_up
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
**Symbols:**

```
ffffffff81081440-ffffffff810814f4: cpu_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084660)
Location: kernel/cpu.c:223
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81084660-ffffffff81084719: cpu_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089600)
Location: kernel/cpu.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81089600-ffffffff810896b9: cpu_hotplug_begin (STB_GLOBAL)
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
In drivers/acpi/acpi_processor.c (ffffffff815010d0)
Location: include/linux/cpu.h:124
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff81543500)
Location: include/linux/cpu.h:122
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff81579442)
Location: include/linux/cpu.h:126
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815910c2)
Location: include/linux/cpu.h:128
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815c1e6d)
Location: include/linux/cpu.h:130
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815e312d)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff8168e57f)
Location: include/linux/cpu.h:141
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff816ac35f)
Location: include/linux/cpu.h:142
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff8168ea0f)
Location: include/linux/cpu.h:147
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/acpi/acpi_processor.c (ffff80001076f87c)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
</details>
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
In drivers/acpi/acpi_processor.c (ffffffff815d506d)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815bec2d)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815d740d)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815f12cd)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
