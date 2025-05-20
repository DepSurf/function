# Function: <code>pte_alloc_one_map</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da393)
Location: mm/memory.c:2884
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff811e9eba)
Location: mm/memory.c:2892
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff811f4fb3)
Location: mm/memory.c:3079
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff8120d092)
Location: mm/memory.c:3248
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff8122dc57)
Location: mm/memory.c:3293
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff8124140a)
Location: mm/memory.c:3053
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff812538d1)
Location: mm/memory.c:3116
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff81261e31)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t pte_alloc_one_map(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128e040)
Location: mm/memory.c:3507
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff8128e040-ffffffff8128e2e0: pte_alloc_one_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t pte_alloc_one_map(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81298ce0)
Location: mm/memory.c:3666
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff81298ce0-ffffffff81298f7e: pte_alloc_one_map (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f91dc)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (c051b454)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (c0000000003c2d30)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffe000209060)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff8125a481)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff8124c89f)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff81258221)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff81267c5b)
Location: mm/memory.c:3141
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
</ul>
