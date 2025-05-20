# Function: <code>dax_unlock_entry</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130ceb0)
Location: fs/dax.c:273
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff8130ceb0-ffffffff8130cf12: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81334230)
Location: fs/dax.c:278
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff81334230-ffffffff81334295: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81347df0)
Location: fs/dax.c:279
Inline: True
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff81347df0-ffffffff81347e55: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138d380)
Location: fs/dax.c:279
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff8138d380-ffffffff8138d3e5: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139eb10)
Location: fs/dax.c:279
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff8139eb10-ffffffff8139eb75: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a5c00)
Location: fs/dax.c:290
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff813a5c00-ffffffff813a5c68: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f5670)
Location: fs/dax.c:290
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff813f5670-ffffffff813f56d8: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814684b0)
Location: fs/dax.c:290
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff814684b0-ffffffff8146851d: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f8f30)
Location: fs/dax.c:290
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_unlock_mapping_entry
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff814f8f30-ffffffff814f8f9d: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152f650)
Location: fs/dax.c:290
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_unlock_mapping_entry
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff8152f650-ffffffff8152f6bd: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81564530)
Location: fs/dax.c:276
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_unlock_mapping_entry
  - fs/dax.c:dax_unlock_folio
```
**Symbols:**

```
ffffffff81564530-ffffffff8156459d: dax_unlock_entry (STB_LOCAL)
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
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff8000104088c8)
Location: fs/dax.c:279
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffff8000104088c8-ffff800010408990: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000513cc0)
Location: fs/dax.c:279
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
c000000000513cc0-c000000000513da0: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b2bf8)
Location: fs/dax.c:279
Inline: True
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffe0002b2bf8-ffffffe0002b2c9e: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813403d0)
Location: fs/dax.c:279
Inline: True
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff813403d0-ffffffff81340435: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81331050)
Location: fs/dax.c:279
Inline: True
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff81331050-ffffffff813310af: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133dea0)
Location: fs/dax.c:279
Inline: True
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff8133dea0-ffffffff8133df05: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dax_unlock_entry(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81350ef0)
Location: fs/dax.c:279
Inline: True
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_unlock_page
```
**Symbols:**

```
ffffffff81350ef0-ffffffff81350f4e: dax_unlock_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
