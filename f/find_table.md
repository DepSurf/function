# Function: <code>find_table</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct elf32_shdr *find_table(struct device *dev, struct elf32_hdr *ehdr, size_t fw_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:204
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff818f7660-ffffffff818f7737: find_table (STB_LOCAL)
ffffffff818f791a-ffffffff818f7988: find_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:235
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff819cd8a0-ffffffff819cd9e1: find_table.isra.0 (STB_LOCAL)
ffffffff819cdc09-ffffffff819cdc7f: find_table.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:235
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff819ccff0-ffffffff819cd131: find_table.isra.0 (STB_LOCAL)
ffffffff81c2f057-ffffffff81c2f0cd: find_table.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:244
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff819b21f0-ffffffff819b2355: find_table.isra.0 (STB_LOCAL)
ffffffff81c21316-ffffffff81c21391: find_table.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:248
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff81a60980-ffffffff81a60ae5: find_table.isra.0 (STB_LOCAL)
ffffffff81d32d79-ffffffff81d32df4: find_table.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:248
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff81bd0f10-ffffffff81bd1083: find_table.isra.0 (STB_LOCAL)
ffffffff81eff1e2-ffffffff81eff24d: find_table.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81d7c7d0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:248
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff81d7c7d0-ffffffff81d7c9a1: find_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81dea990)
Location: drivers/remoteproc/remoteproc_elf_loader.c:248
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff81dea990-ffffffff81deab61: find_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81ea0c00)
Location: drivers/remoteproc/remoteproc_elf_loader.c:248
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff81ea0c00-ffffffff81ea0dd1: find_table.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct elf32_shdr *find_table(struct device *dev, struct elf32_hdr *ehdr, size_t fw_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (ffff800010b83a78)
Location: drivers/remoteproc/remoteproc_elf_loader.c:204
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffff800010b83a78-ffff800010b83c0c: find_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct elf32_shdr *find_table(struct device *dev, struct elf32_hdr *ehdr, size_t fw_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (c0c66cc4)
Location: drivers/remoteproc/remoteproc_elf_loader.c:204
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
c0c66cc4-c0c66e5c: find_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct elf32_shdr *find_table(struct device *dev, struct elf32_hdr *ehdr, size_t fw_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (c000000000c61080)
Location: drivers/remoteproc/remoteproc_elf_loader.c:204
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
c000000000c61080-c000000000c61434: find_table (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct elf32_shdr *find_table(struct device *dev, struct elf32_hdr *ehdr, size_t fw_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:204
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff81898990-ffffffff81898a67: find_table (STB_LOCAL)
ffffffff81898c4a-ffffffff81898cb8: find_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct elf32_shdr *find_table(struct device *dev, struct elf32_hdr *ehdr, size_t fw_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_elf_loader.c (0)
Location: drivers/remoteproc/remoteproc_elf_loader.c:204
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
```
**Symbols:**

```
ffffffff819090f0-ffffffff819091c7: find_table (STB_LOCAL)
ffffffff819093aa-ffffffff81909418: find_table.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
