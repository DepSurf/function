# Function: <code>lru_gen_look_around</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void lru_gen_look_around(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4626
Inline: False
Direct callers:
  - mm/rmap.c:folio_referenced_one
```
**Symbols:**

```
ffffffff82062c67-ffffffff82062c88: lru_gen_look_around.cold (STB_LOCAL)
ffffffff813871e0-ffffffff813878b2: lru_gen_look_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void lru_gen_look_around(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4649
Inline: False
Direct callers:
  - mm/rmap.c:folio_referenced_one
```
**Symbols:**

```
ffffffff820e2330-ffffffff820e2353: lru_gen_look_around.cold (STB_LOCAL)
ffffffff813b7650-ffffffff813b7a92: lru_gen_look_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lru_gen_look_around(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813e04e0)
Location: mm/vmscan.c:3977
Inline: False
Direct callers:
  - mm/rmap.c:folio_referenced_one
```
**Symbols:**

```
ffffffff813e04e0-ffffffff813e0954: lru_gen_look_around (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
