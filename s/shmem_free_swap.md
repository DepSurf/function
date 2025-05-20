# Function: <code>shmem_free_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a8ca0)
Location: mm/shmem.c:352
Inline: True
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811a8ca0-ffffffff811a8d09: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bfb30)
Location: mm/shmem.c:619
Inline: True
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811bfb30-ffffffff811bfb9a: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d00b0)
Location: mm/shmem.c:625
Inline: True
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811d00b0-ffffffff811d011a: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d8800)
Location: mm/shmem.c:641
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811d8800-ffffffff811d8869: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811edd50)
Location: mm/shmem.c:664
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811edd50-ffffffff811eddb9: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120e750)
Location: mm/shmem.c:673
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8120e750-ffffffff8120e7b1: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81221750)
Location: mm/shmem.c:664
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81221750-ffffffff812217b5: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230fc0)
Location: mm/shmem.c:671
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81230fc0-ffffffff81231027: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123f1d0)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8123f1d0-ffffffff8123f237: shmem_free_swap (STB_LOCAL)
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
In mm/shmem.c (ffffffff8126ffb0)
Location: mm/shmem.c:702
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
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
In mm/shmem.c (ffffffff8127b18e)
Location: mm/shmem.c:761
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
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
In mm/shmem.c (ffffffff8128030d)
Location: mm/shmem.c:761
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
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
In mm/shmem.c (ffffffff812be665)
Location: mm/shmem.c:791
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
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
In mm/shmem.c (ffffffff81319e28)
Location: mm/shmem.c:788
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
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
In mm/shmem.c (ffffffff8138e023)
Location: mm/shmem.c:784
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
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
In mm/shmem.c (ffffffff813c0fa3)
Location: mm/shmem.c:784
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
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
In mm/shmem.c (ffffffff813ebbdd)
Location: mm/shmem.c:834
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d0e70)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffff8000102d0e70-ffff8000102d0f44: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa578)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
c04fa578-c04fa604: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038f3d0)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
c00000000038f3d0-c00000000038f4b8: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001edd16)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffe0001edd16-ffffffe0001eddc0: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81237820)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81237820-ffffffff81237887: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122a870)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8122a870-ffffffff8122a8d1: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812355c0)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff812355c0-ffffffff81235627: shmem_free_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_free_swap(struct address_space *mapping, long unsigned int index, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81245360)
Location: mm/shmem.c:686
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81245360-ffffffff812453be: shmem_free_swap (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
