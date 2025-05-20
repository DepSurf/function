# Function: <code>apply_to_existing_page_range</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apply_to_existing_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81293880)
Location: mm/memory.c:2378
Inline: False
```
**Symbols:**

```
ffffffff81293880-ffffffff81293893: apply_to_existing_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apply_to_existing_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e170)
Location: mm/memory.c:2557
Inline: False
```
**Symbols:**

```
ffffffff8129e170-ffffffff8129e183: apply_to_existing_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apply_to_existing_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a38a0)
Location: mm/memory.c:2618
Inline: False
```
**Symbols:**

```
ffffffff812a38a0-ffffffff812a38b3: apply_to_existing_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apply_to_existing_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e4ba0)
Location: mm/memory.c:2713
Inline: False
```
**Symbols:**

```
ffffffff812e4ba0-ffffffff812e4bb3: apply_to_existing_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apply_to_existing_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813464c0)
Location: mm/memory.c:2806
Inline: False
```
**Symbols:**

```
ffffffff813464c0-ffffffff813464e5: apply_to_existing_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apply_to_existing_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813be890)
Location: mm/memory.c:2777
Inline: False
```
**Symbols:**

```
ffffffff813be890-ffffffff813be8b5: apply_to_existing_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apply_to_existing_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f34e0)
Location: mm/memory.c:2777
Inline: False
```
**Symbols:**

```
ffffffff813f34e0-ffffffff813f3505: apply_to_existing_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apply_to_existing_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141e1d0)
Location: mm/memory.c:2800
Inline: False
```
**Symbols:**

```
ffffffff8141e1d0-ffffffff8141e1f5: apply_to_existing_page_range (STB_GLOBAL)
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
