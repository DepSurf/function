# Function: <code>__swap_duplicate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d3b60)
Location: mm/swapfile.c:2629
Inline: False
Direct callers:
  - mm/swapfile.c:swap_shmem_alloc
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
```
**Symbols:**

```
ffffffff811d3b60-ffffffff811d3cb5: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f1980)
Location: mm/swapfile.c:2615
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff811f1980-ffffffff811f1ad5: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81202370)
Location: mm/swapfile.c:2627
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff81202370-ffffffff812024c5: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120d710)
Location: mm/swapfile.c:3106
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff8120d710-ffffffff8120d8f0: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812276d0)
Location: mm/swapfile.c:3355
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff812276d0-ffffffff812278c8: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3379
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff81249c30-ffffffff81249e08: __swap_duplicate (STB_LOCAL)
ffffffff8124e6fc-ffffffff8124e71c: __swap_duplicate.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3357
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff8125e290-ffffffff8125e456: __swap_duplicate (STB_LOCAL)
ffffffff81262bdc-ffffffff81262bfc: __swap_duplicate.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81279420)
Location: mm/swapfile.c:3369
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff81279420-ffffffff812795c2: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81288f00)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff81288f00-ffffffff812890a2: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bbe60)
Location: mm/swapfile.c:3431
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff812bbe60-ffffffff812bc003: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c7980)
Location: mm/swapfile.c:3452
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff812c7980-ffffffff812c7b33: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ce2f0)
Location: mm/swapfile.c:3423
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff812ce2f0-ffffffff812ce490: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81313840)
Location: mm/swapfile.c:3424
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff81313840-ffffffff81313a16: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137ee70)
Location: mm/swapfile.c:3280
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff8137ee70-ffffffff8137f07b: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fd9c0)
Location: mm/swapfile.c:3282
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff813fd9c0-ffffffff813fdbcb: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142f490)
Location: mm/swapfile.c:3273
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff8142f490-ffffffff8142f673: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81468ae0)
Location: mm/swapfile.c:3271
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff81468ae0-ffffffff81468cc3: __swap_duplicate (STB_LOCAL)
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010323ff8)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffff800010323ff8-ffff800010324200: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053bde8)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
c053bde8-c053bf80: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f9da0)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
c0000000003f9da0-c0000000003fa038: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002247a6)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffe0002247a6-ffffffe00022497a: __swap_duplicate (STB_LOCAL)
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812814e0)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff812814e0-ffffffff81281682: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81273350)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff81273350-ffffffff812734f2: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127f2f0)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff8127f2f0-ffffffff8127f492: __swap_duplicate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128efc0)
Location: mm/swapfile.c:3377
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_prepare
  - mm/swapfile.c:swap_duplicate
  - mm/swapfile.c:swap_shmem_alloc
```
**Symbols:**

```
ffffffff8128efc0-ffffffff8128f16f: __swap_duplicate (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
