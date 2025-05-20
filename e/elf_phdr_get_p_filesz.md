# Function: <code>elf_phdr_get_p_filesz</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb4bb)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:71
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cd788)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:71
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819cb5b0)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cced8)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819b075f)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819b2097)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81a5edcf)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81a607f7)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81bcf08b)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81bd0d6a)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d7a06d)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81d7c5ca)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de8134)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81dea78a)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9e374)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81ea09fa)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:72
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
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
