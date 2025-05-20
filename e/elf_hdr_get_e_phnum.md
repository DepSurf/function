# Function: <code>elf_hdr_get_e_phnum</code>

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
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb38f)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cd74d)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_sanity_check
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819cb499)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cce9d)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_sanity_check
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819b0648)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819b205c)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_sanity_check
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81a5ecb8)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81a607bc)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_sanity_check
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81bcef7d)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81bd0d1b)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_sanity_check
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d79f5e)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81d7c587)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_sanity_check
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de7fe6)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81dea747)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_sanity_check
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
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9e226)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81ea09b7)
Location: drivers/remoteproc/remoteproc_elf_helpers.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_sanity_check
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
