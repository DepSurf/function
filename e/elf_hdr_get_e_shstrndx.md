# Function: <code>elf_hdr_get_e_shstrndx</code>

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
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cd8df)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819ca9f9)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:elf_strtbl_add
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cd02f)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819afb89)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:elf_strtbl_add
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819b2234)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81a5e1d9)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:elf_strtbl_add
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81a609c4)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81bce419)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:elf_strtbl_add
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81bd0f54)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d79329)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:elf_strtbl_add
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81d7c814)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de7279)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:elf_strtbl_add
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81dea9d4)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9d4d9)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:elf_strtbl_add
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81ea0c44)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:62
Inline: True
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
