# Function: <code>shmem_replace_entry</code>

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
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8121ff60)
Location: mm/shmem.c:336
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff8121ff60-ffffffff8121fff0: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122f710)
Location: mm/shmem.c:341
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff8122f710-ffffffff8122f7a0: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d8a0)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff8123d8a0-ffffffff8123d930: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126d3dd)
Location: mm/shmem.c:355
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81277bcd)
Location: mm/shmem.c:414
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127c92d)
Location: mm/shmem.c:414
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812baa8d)
Location: mm/shmem.c:411
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131813f)
Location: mm/shmem.c:409
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138ab88)
Location: mm/shmem.c:406
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bd0b5)
Location: mm/shmem.c:407
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e7f25)
Location: mm/shmem.c:473
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
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
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102cf258)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffff8000102cf258-ffff8000102cf300: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04f8868)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
c04f8868-c04f8910: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038cc00)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
c00000000038cc00-c00000000038ccd0: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ecb9a)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffe0001ecb9a-ffffffe0001ecc0c: shmem_replace_entry (STB_LOCAL)
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
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81235ef0)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff81235ef0-ffffffff81235f80: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81228f50)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff81228f50-ffffffff81228fe0: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81233c90)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff81233c90-ffffffff81233d20: shmem_replace_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81243260)
Location: mm/shmem.c:356
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff81243260-ffffffff812432f0: shmem_replace_entry (STB_LOCAL)
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
