# Function: <code>vma_permits_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool vma_permits_fault(struct vm_area_struct *vma, unsigned int fault_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5e70)
Location: mm/gup.c:626
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
```
**Symbols:**

```
ffffffff811d5e70-ffffffff811d5f03: vma_permits_fault (STB_GLOBAL)
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
In mm/gup.c (ffffffff811e46d4)
Location: mm/gup.c:636
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff811eeb34)
Location: mm/gup.c:719
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff8120502c)
Location: mm/gup.c:744
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff81225fe6)
Location: mm/gup.c:763
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff81239756)
Location: mm/gup.c:788
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff8124a7e5)
Location: mm/gup.c:904
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff81258cb5)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff812877c5)
Location: mm/gup.c:1163
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff8129160d)
Location: mm/gup.c:1119
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff81296b2a)
Location: mm/gup.c:1204
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff812d751f)
Location: mm/gup.c:1232
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff813371bb)
Location: mm/gup.c:1256
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff813aeb54)
Location: mm/gup.c:1209
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff813e2c09)
Location: mm/gup.c:1314
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff8140d449)
Location: mm/gup.c:1329
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffff8000102f0b78)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (c0513fd0)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (c0000000003b568c)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffe0002042aa)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff81251305)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff812441f5)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff8124f0a5)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
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
In mm/gup.c (ffffffff8125ea15)
Location: mm/gup.c:905
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
