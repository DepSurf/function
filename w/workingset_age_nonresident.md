# Function: <code>workingset_age_nonresident</code>

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
void workingset_age_nonresident(struct lruvec *lruvec, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812869e0)
Location: mm/workingset.c:226
Inline: False
Direct callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
**Symbols:**

```
ffffffff812869e0-ffffffff81286a4b: workingset_age_nonresident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void workingset_age_nonresident(struct lruvec *lruvec, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81290c30)
Location: mm/workingset.c:227
Inline: False
Direct callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
**Symbols:**

```
ffffffff81290c30-ffffffff81290ca7: workingset_age_nonresident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void workingset_age_nonresident(struct lruvec *lruvec, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81296290)
Location: mm/workingset.c:227
Inline: False
Direct callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
**Symbols:**

```
ffffffff81296290-ffffffff81296307: workingset_age_nonresident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void workingset_age_nonresident(struct lruvec *lruvec, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812d6a20)
Location: mm/workingset.c:229
Inline: False
Direct callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
**Symbols:**

```
ffffffff812d6a20-ffffffff812d6a91: workingset_age_nonresident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void workingset_age_nonresident(struct lruvec *lruvec, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81336150)
Location: mm/workingset.c:229
Inline: False
Direct callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
**Symbols:**

```
ffffffff81336150-ffffffff813361c7: workingset_age_nonresident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void workingset_age_nonresident(struct lruvec *lruvec, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff813ad3d0)
Location: mm/workingset.c:325
Inline: False
Direct callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
**Symbols:**

```
ffffffff813ad3d0-ffffffff813ad447: workingset_age_nonresident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void workingset_age_nonresident(struct lruvec *lruvec, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff813e17c0)
Location: mm/workingset.c:355
Inline: False
Direct callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
**Symbols:**

```
ffffffff813e17c0-ffffffff813e1837: workingset_age_nonresident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void workingset_age_nonresident(struct lruvec *lruvec, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8140bf00)
Location: mm/workingset.c:355
Inline: False
Direct callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
**Symbols:**

```
ffffffff8140bf00-ffffffff8140bf77: workingset_age_nonresident (STB_GLOBAL)
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
