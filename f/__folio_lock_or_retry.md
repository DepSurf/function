# Function: <code>__folio_lock_or_retry</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __folio_lock_or_retry(struct folio *folio, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f5ca0)
Location: mm/filemap.c:1739
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
```
**Symbols:**

```
ffffffff812f5ca0-ffffffff812f60f2: __folio_lock_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __folio_lock_or_retry(struct folio *folio, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135fc10)
Location: mm/filemap.c:1709
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
```
**Symbols:**

```
ffffffff8135fc10-ffffffff8135fce6: __folio_lock_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __folio_lock_or_retry(struct folio *folio, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390bd0)
Location: mm/filemap.c:1683
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
```
**Symbols:**

```
ffffffff81390bd0-ffffffff81390cac: __folio_lock_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t __folio_lock_or_retry(struct folio *folio, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba850)
Location: mm/filemap.c:1663
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
```
**Symbols:**

```
ffffffff813ba850-ffffffff813ba988: __folio_lock_or_retry (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
</li>
</ul>
