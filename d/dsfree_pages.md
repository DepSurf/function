# Function: <code>dsfree_pages</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100de78)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100dd60-ffffffff8100dd8b: dsfree_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e638)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100e520-ffffffff8100e54a: dsfree_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100eb08)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
**Symbols:**

```
ffffffff8100e9f0-ffffffff8100ea1a: dsfree_pages (STB_LOCAL)
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
In arch/x86/events/intel/ds.c (ffffffff81010e47)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
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
In arch/x86/events/intel/ds.c (ffffffff81011527)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
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
In arch/x86/events/intel/ds.c (ffffffff81012822)
Location: arch/x86/events/intel/ds.c:329
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff810110d0-ffffffff810110f6: dsfree_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011442)
Location: arch/x86/events/intel/ds.c:329
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff810102d0-ffffffff810102fa: dsfree_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810124b2)
Location: arch/x86/events/intel/ds.c:394
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81011260-ffffffff8101128a: dsfree_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810133f5)
Location: arch/x86/events/intel/ds.c:394
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81011fe0-ffffffff8101200a: dsfree_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81013946)
Location: arch/x86/events/intel/ds.c:443
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81013990-ffffffff810139ce: dsfree_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017a26)
Location: arch/x86/events/intel/ds.c:450
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81017a80-ffffffff81017abe: dsfree_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810173c6)
Location: arch/x86/events/intel/ds.c:498
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81017420-ffffffff8101745e: dsfree_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dsfree_pages(const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101cf06)
Location: arch/x86/events/intel/ds.c:503
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
Direct callers:
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff8101cf60-ffffffff8101cf9e: dsfree_pages (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011527)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
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
In arch/x86/events/intel/ds.c (ffffffff810102c7)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
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
In arch/x86/events/intel/ds.c (ffffffff810114e7)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
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
In arch/x86/events/intel/ds.c (ffffffff810116f7)
Location: arch/x86/events/intel/ds.c:328
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
