# Function: <code>gnttab_try_end_foreign_access</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int gnttab_try_end_foreign_access(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8179102c)
Location: drivers/xen/grant-table.c:435
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
```
**Symbols:**

```
ffffffff8178f010-ffffffff8178f052: gnttab_try_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int gnttab_try_end_foreign_access(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c8b70)
Location: drivers/xen/grant-table.c:576
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
```
**Symbols:**

```
ffffffff818c8b70-ffffffff818c8bf0: gnttab_try_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int gnttab_try_end_foreign_access(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a19950)
Location: drivers/xen/grant-table.c:576
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
```
**Symbols:**

```
ffffffff81a19950-ffffffff81a199d0: gnttab_try_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int gnttab_try_end_foreign_access(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a629d0)
Location: drivers/xen/grant-table.c:594
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
```
**Symbols:**

```
ffffffff81a629d0-ffffffff81a62a50: gnttab_try_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int gnttab_try_end_foreign_access(grant_ref_t ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab5000)
Location: drivers/xen/grant-table.c:592
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
```
**Symbols:**

```
ffffffff81ab5000-ffffffff81ab5080: gnttab_try_end_foreign_access (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
