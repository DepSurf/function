# Function: <code>__free_cluster</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120cfb0)
Location: mm/swapfile.c:382
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff8120cfb0-ffffffff8120d00c: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81226e60)
Location: mm/swapfile.c:394
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff81226e60-ffffffff81226ece: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81248e60)
Location: mm/swapfile.c:394
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff81248e60-ffffffff81248ece: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125d500)
Location: mm/swapfile.c:422
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff8125d500-ffffffff8125d553: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812787c0)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff812787c0-ffffffff81278810: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812882b0)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff812882b0-ffffffff81288300: __free_cluster (STB_LOCAL)
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
In mm/swapfile.c (ffffffff812bc474)
Location: mm/swapfile.c:456
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812c7f94)
Location: mm/swapfile.c:469
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812cea18)
Location: mm/swapfile.c:468
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81313fab)
Location: mm/swapfile.c:468
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8137f638)
Location: mm/swapfile.c:470
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff813fe178)
Location: mm/swapfile.c:474
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81431154)
Location: mm/swapfile.c:475
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8146a574)
Location: mm/swapfile.c:477
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff8000103231c0)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffff8000103231c0-ffff80001032323c: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053b674)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
c053b674-c053b6e0: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f94a0)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
c0000000003f94a0-c0000000003f9510: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000223d36)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffe000223d36-ffffffe000223dc0: __free_cluster (STB_LOCAL)
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
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280890)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff81280890-ffffffff812808e0: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272700)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff81272700-ffffffff81272750: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127e6a0)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff8127e6a0-ffffffff8127e6f0: __free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128e5d0)
Location: mm/swapfile.c:457
Inline: False
Direct callers:
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff8128e5d0-ffffffff8128e620: __free_cluster (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
