# Function: <code>arch_gnttab_map_shared</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81023cf0)
Location: arch/x86/xen/grant-table.c:54
Inline: False
```
**Symbols:**

```
ffffffff81023cf0-ffffffff81023d86: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81022f90)
Location: arch/x86/xen/grant-table.c:54
Inline: False
```
**Symbols:**

```
ffffffff81022f90-ffffffff81023026: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff810236e0)
Location: arch/x86/xen/grant-table.c:54
Inline: False
```
**Symbols:**

```
ffffffff810236e0-ffffffff81023776: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101b3c0)
Location: arch/x86/xen/grant-table.c:54
Inline: False
```
**Symbols:**

```
ffffffff8101b3c0-ffffffff8101b456: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101bf80)
Location: arch/x86/xen/grant-table.c:54
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101bf80-ffffffff8101c01d: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101c950)
Location: arch/x86/xen/grant-table.c:54
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101c950-ffffffff8101ca04: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101c1e0)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101c1e0-ffffffff8101c294: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101dd40)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101dd40-ffffffff8101ddf8: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e6c0)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101e6c0-ffffffff8101e778: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81020c60)
Location: arch/x86/xen/grant-table.c:30
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff81020c60-ffffffff81020d0d: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81021500)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff81021500-ffffffff81021593: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff810238a0)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff810238a0-ffffffff81023930: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81027b40)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_map_frames_v1
```
**Symbols:**

```
ffffffff81027b40-ffffffff81027bd0: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8102bf80)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_map_frames_v1
```
**Symbols:**

```
ffffffff8102bf80-ffffffff8102c02d: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032ea0)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_map_frames_v1
```
**Symbols:**

```
ffffffff81032ea0-ffffffff81032f4d: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032e40)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_map_frames_v1
```
**Symbols:**

```
ffffffff81032e40-ffffffff81032eed: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81039190)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_map_frames_v1
```
**Symbols:**

```
ffffffff81039190-ffffffff81039230: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int arch_gnttab_map_shared(xen_pfn_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/xen/grant-table.c (ffff8000100f0320)
Location: arch/arm/xen/grant-table.c:36
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffff8000100f0320-ffff8000100f033c: arch_gnttab_map_shared (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e6d0)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101e6d0-ffffffff8101e788: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e680)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101e680-ffffffff8101e738: arch_gnttab_map_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_gnttab_map_shared(long unsigned int *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, void **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e8d0)
Location: arch/x86/xen/grant-table.c:31
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101e8d0-ffffffff8101e988: arch_gnttab_map_shared (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int *frames</code> ➡️ <code>xen_pfn_t *frames</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
