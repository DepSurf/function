# Function: <code>cpu_hotplug_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810815e4)
Location: kernel/cpu.c:164
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_up
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
**Symbols:**

```
ffffffff81081a70-ffffffff81081a92: cpu_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084826)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81084a90-ffffffff81084ab2: cpu_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810897bf)
Location: kernel/cpu.c:307
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81089a20-ffffffff81089a42: cpu_hotplug_done (STB_GLOBAL)
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
In drivers/acpi/acpi_processor.c (ffffffff815010e5)
Location: include/linux/cpu.h:125
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
In drivers/acpi/acpi_processor.c (ffffffff81543515)
Location: include/linux/cpu.h:123
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
In drivers/acpi/acpi_processor.c (ffffffff81579457)
Location: include/linux/cpu.h:127
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
In drivers/acpi/acpi_processor.c (ffffffff815910d7)
Location: include/linux/cpu.h:129
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
In drivers/acpi/acpi_processor.c (ffffffff815c1e86)
Location: include/linux/cpu.h:131
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
In drivers/acpi/acpi_processor.c (ffffffff815e3146)
Location: include/linux/cpu.h:136
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
In drivers/acpi/acpi_processor.c (ffffffff8168e598)
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff816ac378)
Location: include/linux/cpu.h:143
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
In drivers/acpi/acpi_processor.c (ffffffff8168ea28)
Location: include/linux/cpu.h:148
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
In drivers/acpi/acpi_processor.c (ffff80001076f890)
Location: include/linux/cpu.h:136
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
In drivers/acpi/acpi_processor.c (ffffffff815d5086)
Location: include/linux/cpu.h:136
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
In drivers/acpi/acpi_processor.c (ffffffff815bec46)
Location: include/linux/cpu.h:136
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
In drivers/acpi/acpi_processor.c (ffffffff815d7426)
Location: include/linux/cpu.h:136
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
In drivers/acpi/acpi_processor.c (ffffffff815f12e6)
Location: include/linux/cpu.h:136
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
