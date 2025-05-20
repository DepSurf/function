# Function: <code>reusable_anon_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct anon_vma *reusable_anon_vma(struct vm_area_struct *old, struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c4060)
Location: mm/mmap.c:1164
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff811c4060-ffffffff811c4111: reusable_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct anon_vma *reusable_anon_vma(struct vm_area_struct *old, struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811dff20)
Location: mm/mmap.c:1066
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff811dff20-ffffffff811dffd5: reusable_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct anon_vma *reusable_anon_vma(struct vm_area_struct *old, struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811efe70)
Location: mm/mmap.c:1219
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff811efe70-ffffffff811eff25: reusable_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fc468)
Location: mm/mmap.c:1235
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812149a8)
Location: mm/mmap.c:1236
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812357e8)
Location: mm/mmap.c:1245
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81248fe8)
Location: mm/mmap.c:1269
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff8125b2aa)
Location: mm/mmap.c:1271
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff812699a8)
Location: mm/mmap.c:1272
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff8129a1d8)
Location: mm/mmap.c:1253
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff812a53e8)
Location: mm/mmap.c:1291
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff812aab88)
Location: mm/mmap.c:1295
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff812ec1a8)
Location: mm/mmap.c:1292
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff8134f088)
Location: mm/mmap.c:1304
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff813c85e5)
Location: mm/mmap.c:1121
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff813fc7c9)
Location: mm/mmap.c:1070
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff814291a0)
Location: mm/mmap.c:1098
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010300e18)
Location: mm/mmap.c:1272
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct anon_vma *reusable_anon_vma(struct vm_area_struct *old, struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051e4f8)
Location: mm/mmap.c:1272
Inline: True
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
c051e4f8-c051e598: reusable_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cd0d4)
Location: mm/mmap.c:1272
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct anon_vma *reusable_anon_vma(struct vm_area_struct *old, struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020d690)
Location: mm/mmap.c:1272
Inline: True
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffe00020d690-ffffffe00020d714: reusable_anon_vma (STB_LOCAL)
```
</details>
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
In mm/mmap.c (ffffffff81261ff8)
Location: mm/mmap.c:1272
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff81254418)
Location: mm/mmap.c:1272
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff8125fd98)
Location: mm/mmap.c:1272
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
In mm/mmap.c (ffffffff8126f768)
Location: mm/mmap.c:1272
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
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
</ul>
<b>Arch</b>
<ul>
</ul>
