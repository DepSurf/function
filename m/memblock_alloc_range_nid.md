# Function: <code>memblock_alloc_range_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b133)
Location: mm/memblock.c:1138
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:__memblock_alloc_base
```
**Symbols:**

```
ffffffff81f8b133-ffffffff81f8b171: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb4d7a)
Location: mm/memblock.c:1139
Inline: False
Direct callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_alloc_range
```
**Symbols:**

```
ffffffff81fb4d7a-ffffffff81fb4db8: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff1760)
Location: mm/memblock.c:1139
Inline: False
Direct callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_alloc_range
```
**Symbols:**

```
ffffffff81ff1760-ffffffff81ff179c: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3bb1)
Location: mm/memblock.c:1163
Inline: False
Direct callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_alloc_range
```
**Symbols:**

```
ffffffff820d3bb1-ffffffff820d3bf3: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc5d1)
Location: mm/memblock.c:1135
Inline: False
Direct callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:memblock_alloc_range
```
**Symbols:**

```
ffffffff826dc5d1-ffffffff826dc613: memblock_alloc_range_nid (STB_LOCAL)
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
In mm/memblock.c (ffffffff82706c72)
Location: mm/memblock.c:1143
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_base_nid
  - mm/memblock.c:memblock_alloc_range
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
In mm/memblock.c (ffffffff828bde8a)
Location: mm/memblock.c:1258
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_base_nid
  - mm/memblock.c:memblock_alloc_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828d705f)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff828d705f-ffffffff828d7184: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828df4d0)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff828df4d0-ffffffff828df5e6: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfc9db)
Location: mm/memblock.c:1355
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff82cfc9db-ffffffff82cfcb06: memblock_alloc_range_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe9404)
Location: mm/memblock.c:1314
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff82fe9404-ffffffff82fe952f: memblock_alloc_range_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3ab1)
Location: mm/memblock.c:1315
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff831f3ab1-ffffffff831f3bd9: memblock_alloc_range_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832d9ddf)
Location: mm/memblock.c:1350
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff832d9ddf-ffffffff832d9f1f: memblock_alloc_range_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348edf9)
Location: mm/memblock.c:1354
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff8348edf9-ffffffff8348ef42: memblock_alloc_range_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec1180)
Location: mm/memblock.c:1372
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff83ec1180-ffffffff83ec1345: memblock_alloc_range_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6980)
Location: mm/memblock.c:1385
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff836e6980-ffffffff836e6b54: memblock_alloc_range_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, bool exact_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83918f30)
Location: mm/memblock.c:1443
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff83918f30-ffffffff83919104: memblock_alloc_range_nid (STB_GLOBAL)
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
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff800011458448)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffff800011458448-ffff800011458588: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c15323a0)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
c15323a0-c15324f0: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c000000001381c20)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
c000000001381c20-c000000001381dc0: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000016b94)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffe000016b94-ffffffe000016ca8: memblock_alloc_range_nid (STB_LOCAL)
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
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c8384)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff828c8384-ffffffff828c849a: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c0aa9)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff828c0aa9-ffffffff828c0bbf: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828db104)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff828db104-ffffffff828db21a: memblock_alloc_range_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range_nid(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828e0525)
Location: mm/memblock.c:1343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc_range
```
**Symbols:**

```
ffffffff828e0525-ffffffff828e063b: memblock_alloc_range_nid (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exact_nid</code>
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
