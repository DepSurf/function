# Function: <code>get_gate_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811bab42)
Location: mm/gup.c:246
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d53b2)
Location: mm/gup.c:305
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e53d6)
Location: mm/gup.c:316
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff811efa98)
Location: mm/gup.c:403
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff81206f15)
Location: mm/gup.c:421
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff81227e34)
Location: mm/gup.c:437
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff8123b6ac)
Location: mm/gup.c:454
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff8124cb95)
Location: mm/gup.c:571
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff8125b0c5)
Location: mm/gup.c:570
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_gate_page(struct mm_struct *mm, long unsigned int address, unsigned int gup_flags, struct vm_area_struct **vma, struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812891f0)
Location: mm/gup.c:804
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff812891f0-ffffffff812894f1: get_gate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_gate_page(struct mm_struct *mm, long unsigned int address, unsigned int gup_flags, struct vm_area_struct **vma, struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81292ed0)
Location: mm/gup.c:768
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81292ed0-ffffffff812931d1: get_gate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_gate_page(struct mm_struct *mm, long unsigned int address, unsigned int gup_flags, struct vm_area_struct **vma, struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812988c0)
Location: mm/gup.c:853
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff812988c0-ffffffff81298b70: get_gate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_gate_page(struct mm_struct *mm, long unsigned int address, unsigned int gup_flags, struct vm_area_struct **vma, struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:879
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff812d9320-ffffffff812d95ee: get_gate_page (STB_LOCAL)
ffffffff81cbc109-ffffffff81cbc141: get_gate_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_gate_page(struct mm_struct *mm, long unsigned int address, unsigned int gup_flags, struct vm_area_struct **vma, struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:903
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81339300-ffffffff813395e7: get_gate_page (STB_LOCAL)
ffffffff81e6dc81-ffffffff81e6dcb9: get_gate_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_gate_page(struct mm_struct *mm, long unsigned int address, unsigned int gup_flags, struct vm_area_struct **vma, struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:830
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff813b0c10-ffffffff813b0ef0: get_gate_page (STB_LOCAL)
ffffffff82063d32-ffffffff82063d6a: get_gate_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_gate_page(struct mm_struct *mm, long unsigned int address, unsigned int gup_flags, struct vm_area_struct **vma, struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:864
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff813e5040-ffffffff813e52e2: get_gate_page (STB_LOCAL)
ffffffff820e3436-ffffffff820e346e: get_gate_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_gate_page(struct mm_struct *mm, long unsigned int address, unsigned int gup_flags, struct vm_area_struct **vma, struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:859
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff8140f8d0-ffffffff8140fb73: get_gate_page (STB_LOCAL)
ffffffff821bfe8a-ffffffff821bfec2: get_gate_page.cold (STB_LOCAL)
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
In mm/gup.c (0)
Location: mm/gup.c:570
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0514960)
Location: mm/gup.c:570
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (0)
Location: mm/gup.c:570
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:570
Inline: False
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
In mm/gup.c (ffffffff81253715)
Location: mm/gup.c:570
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff812463e4)
Location: mm/gup.c:570
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff812514b5)
Location: mm/gup.c:570
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff81260e4e)
Location: mm/gup.c:570
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
