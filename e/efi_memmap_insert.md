# Function: <code>efi_memmap_insert</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8202270a)
Location: drivers/firmware/efi/memmap.c:253
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff8202270a-ffffffff82022874: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82105411)
Location: drivers/firmware/efi/memmap.c:253
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff82105411-ffffffff82105563: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8270eada)
Location: drivers/firmware/efi/memmap.c:254
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff8270eada-ffffffff8270ec2c: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82738d94)
Location: drivers/firmware/efi/memmap.c:254
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff82738d94-ffffffff82738ee6: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828f2d4f)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff828f2d4f-ffffffff828f2ea1: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8290e657)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff8290e657-ffffffff8290e7b5: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82918032)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff82918032-ffffffff82918184: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82d2a360)
Location: drivers/firmware/efi/memmap.c:290
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff82d2a360-ffffffff82d2a4b0: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83018a77)
Location: drivers/firmware/efi/memmap.c:290
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff83018a77-ffffffff83018bc7: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83223a6a)
Location: drivers/firmware/efi/memmap.c:290
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff83223a6a-ffffffff83223bbf: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8330d870)
Location: drivers/firmware/efi/memmap.c:290
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff8330d870-ffffffff8330d9c5: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff834c75c2)
Location: drivers/firmware/efi/memmap.c:290
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff834c75c2-ffffffff834c7733: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff83ea16d0)
Location: arch/x86/platform/efi/memmap.c:151
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff83ea16d0-ffffffff83ea186e: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff836c5910)
Location: arch/x86/platform/efi/memmap.c:151
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff836c5910-ffffffff836c5ac4: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff838f6510)
Location: arch/x86/platform/efi/memmap.c:151
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff838f6510-ffffffff838f66c4: efi_memmap_insert (STB_GLOBAL)
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
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffff8000114a6a18)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
```
**Symbols:**

```
ffff8000114a6a18-ffff8000114a6bd0: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (c15a8e38)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
```
**Symbols:**

```
c15a8e38-c15a920c: efi_memmap_insert (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828fd438)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff828fd438-ffffffff828fd58a: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828f4cd4)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff828f4cd4-ffffffff828f4e26: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82912667)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff82912667-ffffffff829127b9: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void efi_memmap_insert(struct efi_memory_map *old_memmap, void *buf, struct efi_mem_range *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82919094)
Location: drivers/firmware/efi/memmap.c:257
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
```
**Symbols:**

```
ffffffff82919094-ffffffff829191e6: efi_memmap_insert (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
