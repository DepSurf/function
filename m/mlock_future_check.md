# Function: <code>mlock_future_check</code>

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
In mm/mmap.c (ffffffff811c69c5)
Location: mm/mmap.c:1246
Inline: True
Inline callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff811e2f96)
Location: mm/mmap.c:1130
Inline: True
Inline callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff811f2f76)
Location: mm/mmap.c:1283
Inline: True
Inline callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff811fdebd)
Location: mm/mmap.c:1299
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff8121646d)
Location: mm/mmap.c:1300
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff81237222)
Location: mm/mmap.c:1309
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff8124aad1)
Location: mm/mmap.c:1333
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff8125ce4c)
Location: mm/mmap.c:1335
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff8126b61c)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff8129b42c)
Location: mm/mmap.c:1313
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff812a660e)
Location: mm/mmap.c:1351
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff812ac601)
Location: mm/mmap.c:1355
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mlock_future_check(struct mm_struct *mm, long unsigned int flags, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812edd51)
Location: mm/mmap.c:1352
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
Direct callers:
  - mm/secretmem.c:secretmem_mmap
```
**Symbols:**

```
ffffffff812ec220-ffffffff812ec278: mlock_future_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mlock_future_check(struct mm_struct *mm, long unsigned int flags, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351156)
Location: mm/mmap.c:1364
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
Direct callers:
  - mm/mremap.c:vma_to_resize
  - mm/secretmem.c:secretmem_mmap
```
**Symbols:**

```
ffffffff8134f120-ffffffff8134f196: mlock_future_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mlock_future_check(struct mm_struct *mm, long unsigned int flags, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813cb2ad)
Location: mm/mmap.c:1187
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:check_brk_limits
Direct callers:
  - mm/mremap.c:vma_to_resize
  - mm/secretmem.c:secretmem_mmap
```
**Symbols:**

```
ffffffff813c8700-ffffffff813c8776: mlock_future_check (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010302dfc)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (c0521424)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (c0000000003cf62c)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffe00020fb06)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff81263c6c)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff8125608c)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff81261a0c)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
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
In mm/mmap.c (ffffffff812713cc)
Location: mm/mmap.c:1336
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
