# Function: <code>workingset_eviction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *workingset_eviction(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811b9e10)
Location: mm/workingset.c:213
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff811b9e10-ffffffff811b9e8d: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *workingset_eviction(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811d41d0)
Location: mm/workingset.c:205
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff811d41d0-ffffffff811d4260: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *workingset_eviction(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811e4210)
Location: mm/workingset.c:206
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff811e4210-ffffffff811e42a0: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *workingset_eviction(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811ee5e0)
Location: mm/workingset.c:207
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff811ee5e0-ffffffff811ee679: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *workingset_eviction(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81204a50)
Location: mm/workingset.c:208
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81204a50-ffffffff81204ae9: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *workingset_eviction(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81225800)
Location: mm/workingset.c:208
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81225800-ffffffff81225899: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *workingset_eviction(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81238d80)
Location: mm/workingset.c:224
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81238d80-ffffffff81238e54: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff8124a25c-ffffffff8124a26f: workingset_eviction.cold (STB_LOCAL)
ffffffff81249f80-ffffffff8124a05e: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812583d0)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff812583d0-ffffffff812584ae: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page, struct mem_cgroup *target_memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81286a50)
Location: mm/workingset.c:252
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81286a50-ffffffff81286b6c: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page, struct mem_cgroup *target_memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81290cb0)
Location: mm/workingset.c:253
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81290cb0-ffffffff81290dd6: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page, struct mem_cgroup *target_memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81296310)
Location: mm/workingset.c:253
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81296310-ffffffff81296438: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *workingset_eviction(struct page *page, struct mem_cgroup *target_memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:255
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81cbbd05-ffffffff81cbbd29: workingset_eviction.cold (STB_LOCAL)
ffffffff812d6aa0-ffffffff812d6bcd: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *workingset_eviction(struct folio *folio, struct mem_cgroup *target_memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:255
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81e6d9ae-ffffffff81e6d9d2: workingset_eviction.cold (STB_LOCAL)
ffffffff813361d0-ffffffff8133633d: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *workingset_eviction(struct folio *folio, struct mem_cgroup *target_memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:351
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff82063cc9-ffffffff82063ce5: workingset_eviction.cold (STB_LOCAL)
ffffffff813ad460-ffffffff813ad5a4: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *workingset_eviction(struct folio *folio, struct mem_cgroup *target_memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:381
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff820e33c0-ffffffff820e33dc: workingset_eviction.cold (STB_LOCAL)
ffffffff813e1850-ffffffff813e1991: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *workingset_eviction(struct folio *folio, struct mem_cgroup *target_memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:381
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff821bfe20-ffffffff821bfe3c: workingset_eviction.cold (STB_LOCAL)
ffffffff8140bf90-ffffffff8140c0ce: workingset_eviction (STB_GLOBAL)
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
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffff8000102f01a0)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffff8000102f01a0-ffff8000102f02a0: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (c05138b0)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
c05138b0-c05139a8: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (c0000000003b4b50)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
c0000000003b4b50-c0000000003b4c68: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffe000203bb4)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffe000203bb4-ffffffe000203cb8: workingset_eviction (STB_GLOBAL)
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
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81250a20)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff81250a20-ffffffff81250afe: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812439a0)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff812439a0-ffffffff81243a7e: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8124e7c0)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff8124e7c0-ffffffff8124e89e: workingset_eviction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *workingset_eviction(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8125e130)
Location: mm/workingset.c:223
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff8125e130-ffffffff8125e20e: workingset_eviction (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, page</code> ➡️ <code>page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup *target_memcg</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
