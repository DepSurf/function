# Function: <code>kobj_to_hstate</code>

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
In mm/hugetlb.c (ffffffff811da420)
Location: mm/hugetlb.c:2231
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffff811f8490)
Location: mm/hugetlb.c:2282
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffff81208e40)
Location: mm/hugetlb.c:2388
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffff81214720)
Location: mm/hugetlb.c:2366
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffff8122f2b0)
Location: mm/hugetlb.c:2374
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81251d04)
Location: mm/hugetlb.c:2376
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81251c30-ffffffff81251cd5: kobj_to_hstate.part.65 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81266104)
Location: mm/hugetlb.c:2370
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81266030-ffffffff812660d5: kobj_to_hstate.part.64 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff81280c51)
Location: mm/hugetlb.c:2447
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffff81290661)
Location: mm/hugetlb.c:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hstate *kobj_to_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c3220)
Location: mm/hugetlb.c:2847
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff812c3220-ffffffff812c329e: kobj_to_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hstate *kobj_to_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cef70)
Location: mm/hugetlb.c:2800
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff812cef70-ffffffff812cefee: kobj_to_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct hstate *kobj_to_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d5c00)
Location: mm/hugetlb.c:2965
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff812d5c00-ffffffff812d5c7e: kobj_to_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct hstate *kobj_to_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131ba00)
Location: mm/hugetlb.c:3250
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff8131ba00-ffffffff8131bac0: kobj_to_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct hstate *kobj_to_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff813873c0)
Location: mm/hugetlb.c:3522
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_size_show
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/hugetlb.c:nr_hugepages_show
```
**Symbols:**

```
ffffffff813873c0-ffffffff8138748c: kobj_to_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hstate *kobj_to_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81405600)
Location: mm/hugetlb.c:3690
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_size_show
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff81405600-ffffffff814056cc: kobj_to_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hstate *kobj_to_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81438b20)
Location: mm/hugetlb.c:3720
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_size_show
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff81438b20-ffffffff81438bec: kobj_to_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hstate *kobj_to_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814724b0)
Location: mm/hugetlb.c:3978
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_size_show
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/hugetlb.c:nr_hugepages_show
```
**Symbols:**

```
ffffffff814724b0-ffffffff8147257c: kobj_to_hstate (STB_LOCAL)
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
In mm/hugetlb.c (ffff80001032da68)
Location: mm/hugetlb.c:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
</details>
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
In mm/hugetlb.c (c000000000406260)
Location: mm/hugetlb.c:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffe00022be1a)
Location: mm/hugetlb.c:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store
  - mm/hugetlb.c:nr_hugepages_show
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
In mm/hugetlb.c (ffffffff81288c41)
Location: mm/hugetlb.c:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffff8127aae1)
Location: mm/hugetlb.c:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffff81286a51)
Location: mm/hugetlb.c:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffff81296f21)
Location: mm/hugetlb.c:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
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
