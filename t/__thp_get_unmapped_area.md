# Function: <code>__thp_get_unmapped_area</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file *filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81226670)
Location: mm/huge_memory.c:502
Inline: False
Direct callers:
  - mm/huge_memory.c:thp_get_unmapped_area
```
**Symbols:**

```
ffffffff81226670-ffffffff812266eb: __thp_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file *filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81232510)
Location: mm/huge_memory.c:504
Inline: False
Direct callers:
  - mm/huge_memory.c:thp_get_unmapped_area
```
**Symbols:**

```
ffffffff81232510-ffffffff8123258e: __thp_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file *filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124fbc0)
Location: mm/huge_memory.c:504
Inline: False
Direct callers:
  - mm/huge_memory.c:thp_get_unmapped_area
```
**Symbols:**

```
ffffffff8124fbc0-ffffffff8124fc44: __thp_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file *filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81274120)
Location: mm/huge_memory.c:501
Inline: False
Direct callers:
  - mm/huge_memory.c:thp_get_unmapped_area
```
**Symbols:**

```
ffffffff81274120-ffffffff812741a4: __thp_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file *filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81289150)
Location: mm/huge_memory.c:511
Inline: False
Direct callers:
  - mm/huge_memory.c:thp_get_unmapped_area
```
**Symbols:**

```
ffffffff81289150-ffffffff812891d4: __thp_get_unmapped_area (STB_GLOBAL)
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
In mm/huge_memory.c (ffffffff812a1ee8)
Location: mm/huge_memory.c:516
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff812b3289)
Location: mm/huge_memory.c:522
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff812e8639)
Location: mm/huge_memory.c:533
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff812f3949)
Location: mm/huge_memory.c:526
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff812f9cd9)
Location: mm/huge_memory.c:543
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff81343b29)
Location: mm/huge_memory.c:543
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff813b9242)
Location: mm/huge_memory.c:541
Inline: True
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
In mm/huge_memory.c (ffffffff8143b4e2)
Location: mm/huge_memory.c:602
Inline: True
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
In mm/huge_memory.c (ffffffff81470e32)
Location: mm/huge_memory.c:601
Inline: True
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
In mm/huge_memory.c (ffffffff814a04a6)
Location: mm/huge_memory.c:807
Inline: True
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043a67c)
Location: mm/huge_memory.c:522
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff812ab869)
Location: mm/huge_memory.c:522
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff8129d169)
Location: mm/huge_memory.c:522
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff812a9679)
Location: mm/huge_memory.c:522
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
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
In mm/huge_memory.c (ffffffff812b9c19)
Location: mm/huge_memory.c:522
Inline: True
Inline callers:
  - mm/huge_memory.c:thp_get_unmapped_area
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
