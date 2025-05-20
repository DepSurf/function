# Function: <code>elf_shdr_get_sh_size</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cda21)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:78
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819cae8b)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cd171)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819b0043)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819b2391)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81a5e6b3)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81a60b21)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81bce95a)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81bd10c3)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d798b8)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81d7c9f3)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de789e)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81deabb3)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9dafe)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81ea0e23)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:82
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
