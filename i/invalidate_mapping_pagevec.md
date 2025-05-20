# Function: <code>invalidate_mapping_pagevec</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void invalidate_mapping_pagevec(struct address_space *mapping, long unsigned int start, long unsigned int end, long unsigned int *nr_pagevec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126c620)
Location: mm/truncate.c:650
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff8126c620-ffffffff8126c630: invalidate_mapping_pagevec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void invalidate_mapping_pagevec(struct address_space *mapping, long unsigned int start, long unsigned int end, long unsigned int *nr_pagevec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81271380)
Location: mm/truncate.c:547
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff81271380-ffffffff81271390: invalidate_mapping_pagevec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void invalidate_mapping_pagevec(struct address_space *mapping, long unsigned int start, long unsigned int end, long unsigned int *nr_pagevec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ae900)
Location: mm/truncate.c:548
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff812ae900-ffffffff812ae910: invalidate_mapping_pagevec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pagevec(struct address_space *mapping, long unsigned int start, long unsigned int end, long unsigned int *nr_pagevec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81308c70)
Location: mm/truncate.c:502
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/truncate.c:invalidate_mapping_pages
```
**Symbols:**

```
ffffffff81308c70-ffffffff81308ebd: invalidate_mapping_pagevec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pagevec(struct address_space *mapping, long unsigned int start, long unsigned int end, long unsigned int *nr_pagevec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81372ac0)
Location: mm/truncate.c:498
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/truncate.c:invalidate_mapping_pages
```
**Symbols:**

```
ffffffff81372ac0-ffffffff81372ca6: invalidate_mapping_pagevec (STB_GLOBAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
