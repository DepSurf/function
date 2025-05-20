# Function: <code>__get_user_pages_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int __get_user_pages_unlocked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811ba1c0)
Location: mm/gup.c:758
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
```
**Symbols:**

```
ffffffff811ba1c0-ffffffff811ba392: __get_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int __get_user_pages_unlocked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5be5)
Location: mm/gup.c:865
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
```
**Symbols:**

```
ffffffff811d4610-ffffffff811d47e2: __get_user_pages_unlocked (STB_GLOBAL)
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
In mm/gup.c (ffffffff811e5bcb)
Location: mm/gup.c:869
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
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
In mm/gup.c (ffffffff811f024b)
Location: mm/gup.c:950
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
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
In mm/gup.c (ffffffff8120768b)
Location: mm/gup.c:975
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
