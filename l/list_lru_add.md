# Function: <code>list_lru_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811b8ee0)
Location: mm/list_lru.c:109
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff811b8ee0-ffffffff811b8fea: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811d3180)
Location: mm/list_lru.c:109
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff811d3180-ffffffff811d32a9: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811e3040)
Location: mm/list_lru.c:109
Inline: False
Direct callers:
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff811e3040-ffffffff811e315b: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811ed500)
Location: mm/list_lru.c:109
Inline: False
Direct callers:
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff811ed500-ffffffff811ed62f: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81203950)
Location: mm/list_lru.c:109
Inline: False
Direct callers:
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff81203950-ffffffff81203a7f: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81224cc0)
Location: mm/list_lru.c:110
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff81224cc0-ffffffff81224dfa: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81237d80)
Location: mm/list_lru.c:127
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff81237d80-ffffffff81237f05: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81249300)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff81249300-ffffffff812494b1: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81257750)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff81257750-ffffffff81257901: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81285f60)
Location: mm/list_lru.c:115
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
```
**Symbols:**

```
ffffffff81285f60-ffffffff81286072: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81290210)
Location: mm/list_lru.c:115
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
```
**Symbols:**

```
ffffffff81290210-ffffffff81290322: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81295770)
Location: mm/list_lru.c:115
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
```
**Symbols:**

```
ffffffff81295770-ffffffff81295882: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812d5df0)
Location: mm/list_lru.c:115
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
```
**Symbols:**

```
ffffffff812d5df0-ffffffff812d5f02: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:119
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_add_lru
```
**Symbols:**

```
ffffffff81e6d85a-ffffffff81e6d8a6: list_lru_add.cold (STB_LOCAL)
ffffffff81334990-ffffffff81334b2f: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:119
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_add_lru
```
**Symbols:**

```
ffffffff82063b75-ffffffff82063bc1: list_lru_add.cold (STB_LOCAL)
ffffffff813ab770-ffffffff813ab90f: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:119
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_add_lru
```
**Symbols:**

```
ffffffff820e326c-ffffffff820e32b8: list_lru_add.cold (STB_LOCAL)
ffffffff813dfb10-ffffffff813dfc98: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item, int nid, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:88
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_add_obj
  - mm/zswap.c:zswap_lru_add
```
**Symbols:**

```
ffffffff821bfccc-ffffffff821bfcf0: list_lru_add.cold (STB_LOCAL)
ffffffff8140a220-ffffffff8140a35b: list_lru_add (STB_GLOBAL)
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
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffff8000102ef0c8)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffff8000102ef0c8-ffff8000102ef238: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0512840)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
c0512840-c0512990: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0000000003b3830)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
c0000000003b3830-c0000000003b3a70: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffe000203068)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffe000203068-ffffffe0002031d0: list_lru_add (STB_GLOBAL)
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
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124fda0)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff8124fda0-ffffffff8124ff51: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81242d40)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff81242d40-ffffffff81242ef1: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124db40)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff8124db40-ffffffff8124dcf1: list_lru_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool list_lru_add(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8125ce10)
Location: mm/list_lru.c:125
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_add
  - fs/inode.c:inode_lru_list_add
```
**Symbols:**

```
ffffffff8125ce10-ffffffff8125cfbd: list_lru_add (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param added. </b>
<code>struct mem_cgroup *memcg</code>
</li>
</ul>
</details>
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
