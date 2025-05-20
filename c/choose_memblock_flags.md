# Function: <code>choose_memblock_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ulong choose_memblock_flags();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181db90)
Location: mm/memblock.c:62
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_find_in_range
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_nid
```
**Symbols:**

```
ffffffff8181db90-ffffffff8181dba6: choose_memblock_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ulong choose_memblock_flags();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81897fc3)
Location: mm/memblock.c:62
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81897fc3-ffffffff81897fd8: choose_memblock_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ulong choose_memblock_flags();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cc665)
Location: mm/memblock.c:62
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff818cc665-ffffffff818cc67a: choose_memblock_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ulong choose_memblock_flags();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81903bc4)
Location: mm/memblock.c:62
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81903bc4-ffffffff81903bda: choose_memblock_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ulong choose_memblock_flags();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198dbcf)
Location: mm/memblock.c:62
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff8198dbcf-ffffffff8198dbe5: choose_memblock_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ulong choose_memblock_flags();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819ea484)
Location: mm/memblock.c:64
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff819ea484-ffffffff819ea495: choose_memblock_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum memblock_flags choose_memblock_flags();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a256f8)
Location: mm/memblock.c:135
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81a256f8-ffffffff81a25707: choose_memblock_flags (STB_GLOBAL)
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
In mm/memblock.c (ffffffff828d7064)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffff828df4d5)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffff82cfc9e0)
Location: mm/memblock.c:138
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffff82fe9409)
Location: mm/memblock.c:160
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffff831f3ab6)
Location: mm/memblock.c:160
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum memblock_flags choose_memblock_flags();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d4fa6c)
Location: mm/memblock.c:160
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
```
**Symbols:**

```
ffffffff81d4fa6c-ffffffff81d4fa94: choose_memblock_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum memblock_flags choose_memblock_flags();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f1fa45)
Location: mm/memblock.c:160
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
```
**Symbols:**

```
ffffffff81f1fa45-ffffffff81f1fa75: choose_memblock_flags (STB_LOCAL)
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
In mm/memblock.c (ffffffff83ec1185)
Location: mm/memblock.c:164
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
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
In mm/memblock.c (ffffffff836e6985)
Location: mm/memblock.c:164
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
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
In mm/memblock.c (ffffffff83918f35)
Location: mm/memblock.c:169
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
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
In mm/memblock.c (ffff80001145847c)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (c15323b8)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (c000000001381c60)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffe000016bc2)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffff828c8389)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffff828c0aae)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffff828db109)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
In mm/memblock.c (ffffffff828e052a)
Location: mm/memblock.c:142
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>ulong</code> ➡️ <code>enum memblock_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
