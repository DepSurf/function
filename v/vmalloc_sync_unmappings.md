# Function: <code>vmalloc_sync_unmappings</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81081170)
Location: arch/x86/mm/fault.c:340
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81081170-ffffffff8108117b: vmalloc_sync_unmappings (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3065
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffff80001030db40-ffff80001030db58: vmalloc_sync_unmappings (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3065
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
c05295a0-c05295b8: vmalloc_sync_unmappings (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003de740)
Location: mm/vmalloc.c:3065
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
c0000000003de740-c0000000003de74c: vmalloc_sync_unmappings (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3065
Inline: False
```
**Symbols:**

```
ffffffe000216832-ffffffe00021684c: vmalloc_sync_unmappings (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080170)
Location: arch/x86/mm/fault.c:340
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81080170-ffffffff8108017b: vmalloc_sync_unmappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106ef30)
Location: arch/x86/mm/fault.c:340
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8106ef30-ffffffff8106ef3b: vmalloc_sync_unmappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080120)
Location: arch/x86/mm/fault.c:340
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81080120-ffffffff8108012b: vmalloc_sync_unmappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vmalloc_sync_unmappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81082240)
Location: arch/x86/mm/fault.c:340
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81082240-ffffffff8108224b: vmalloc_sync_unmappings (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
