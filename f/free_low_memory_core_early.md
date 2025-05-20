# Function: <code>free_low_memory_core_early</code>

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
In mm/nobootmem.c (ffffffff81f8ad76)
Location: mm/nobootmem.c:125
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/nobootmem.c (ffffffff81fb49b4)
Location: mm/nobootmem.c:126
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/nobootmem.c (ffffffff81ff139a)
Location: mm/nobootmem.c:129
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/nobootmem.c (ffffffff820d37d3)
Location: mm/nobootmem.c:129
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/nobootmem.c (ffffffff826dc1f3)
Location: mm/nobootmem.c:130
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/nobootmem.c (ffffffff827066ce)
Location: mm/nobootmem.c:130
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/memblock.c (ffffffff828be535)
Location: mm/memblock.c:1922
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828d7702)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828dfb73)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int free_low_memory_core_early();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfc85b)
Location: mm/memblock.c:1975
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff82cfc85b-ffffffff82cfc9db: free_low_memory_core_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int free_low_memory_core_early();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe927f)
Location: mm/memblock.c:2005
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff82fe927f-ffffffff82fe9404: free_low_memory_core_early (STB_LOCAL)
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
In mm/memblock.c (ffffffff831f420b)
Location: mm/memblock.c:2006
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff832da5a6)
Location: mm/memblock.c:2054
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff8348f6a9)
Location: mm/memblock.c:2061
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff83ec1d6e)
Location: mm/memblock.c:2079
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int free_low_memory_core_early();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e66c0)
Location: mm/memblock.c:2121
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff836e66c0-ffffffff836e6968: free_low_memory_core_early (STB_LOCAL)
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
In mm/memblock.c (ffffffff83919b6a)
Location: mm/memblock.c:2188
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffff800011458c98)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (c1532c04)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (c000000001382580)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffe0000172d2)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828c8a27)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828c114c)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828db7a7)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828e0bc8)
Location: mm/memblock.c:1923
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
