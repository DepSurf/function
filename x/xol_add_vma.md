# Function: <code>xol_add_vma</code>

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
In kernel/events/uprobes.c (ffffffff811871ca)
Location: kernel/events/uprobes.c:1127
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff811996ee)
Location: kernel/events/uprobes.c:1129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff811aa71e)
Location: kernel/events/uprobes.c:1130
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff811b1c6e)
Location: kernel/events/uprobes.c:1138
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff811c587e)
Location: kernel/events/uprobes.c:1138
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff811e5dd6)
Location: kernel/events/uprobes.c:1137
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff811f6926)
Location: kernel/events/uprobes.c:1403
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff8120e6e3)
Location: kernel/events/uprobes.c:1391
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff8121bd23)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xol_add_vma(struct mm_struct *mm, struct xol_area *area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81245920)
Location: kernel/events/uprobes.c:1442
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__create_xol_area
```
**Symbols:**

```
ffffffff81245920-ffffffff81245a31: xol_add_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xol_add_vma(struct mm_struct *mm, struct xol_area *area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81250210)
Location: kernel/events/uprobes.c:1442
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__create_xol_area
```
**Symbols:**

```
ffffffff81250210-ffffffff81250375: xol_add_vma (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff81256b71)
Location: kernel/events/uprobes.c:1440
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff81292911)
Location: kernel/events/uprobes.c:1441
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff812e8305)
Location: kernel/events/uprobes.c:1436
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xol_add_vma(struct mm_struct *mm, struct xol_area *area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134efb0)
Location: kernel/events/uprobes.c:1440
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__create_xol_area
```
**Symbols:**

```
ffffffff8134efb0-ffffffff8134f0f2: xol_add_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xol_add_vma(struct mm_struct *mm, struct xol_area *area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81380170)
Location: kernel/events/uprobes.c:1437
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__create_xol_area
```
**Symbols:**

```
ffffffff81380170-ffffffff813802ca: xol_add_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xol_add_vma(struct mm_struct *mm, struct xol_area *area);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813a9520)
Location: kernel/events/uprobes.c:1437
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__create_xol_area
```
**Symbols:**

```
ffffffff813a9520-ffffffff813a967a: xol_add_vma (STB_LOCAL)
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
In kernel/events/uprobes.c (ffff8000102a765c)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (c04d6718)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (c00000000035ab54)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
</details>
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
In kernel/events/uprobes.c (ffffffff81214373)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff812070e3)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff81212113)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
In kernel/events/uprobes.c (ffffffff81221093)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
