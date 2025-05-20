# Function: <code>list_lru_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811b96c0)
Location: mm/list_lru.c:128
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - fs/inode.c:evict_inodes
  - fs/inode.c:invalidate_inodes
```
**Symbols:**

```
ffffffff811b96c0-ffffffff811b97d4: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811d39c0)
Location: mm/list_lru.c:128
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_tree_insert
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff811d39c0-ffffffff811d3af5: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811e3890)
Location: mm/list_lru.c:128
Inline: False
Direct callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff811e3890-ffffffff811e39bb: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811edce0)
Location: mm/list_lru.c:129
Inline: False
Direct callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff811edce0-ffffffff811ede13: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81204140)
Location: mm/list_lru.c:129
Inline: False
Direct callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81204140-ffffffff81204273: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81224e00)
Location: mm/list_lru.c:130
Inline: False
Direct callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81224e00-ffffffff81224f42: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81237f10)
Location: mm/list_lru.c:151
Inline: False
Direct callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81237f10-ffffffff8123804f: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812494c0)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff812494c0-ffffffff81249625: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81257910)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81257910-ffffffff81257a75: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81286150)
Location: mm/list_lru.c:139
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:iput_final
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81286150-ffffffff81286236: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81290400)
Location: mm/list_lru.c:139
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:iput_final
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81290400-ffffffff812904e6: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81295890)
Location: mm/list_lru.c:139
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:iput_final
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81295890-ffffffff81295979: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812d5f10)
Location: mm/list_lru.c:139
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff812d5f10-ffffffff812d5ff9: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:143
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81e6d918-ffffffff81e6d95c: list_lru_del.cold (STB_LOCAL)
ffffffff813353e0-ffffffff81335544: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:143
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff82063c33-ffffffff82063c77: list_lru_del.cold (STB_LOCAL)
ffffffff813ac180-ffffffff813ac2e4: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:143
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff820e332a-ffffffff820e336e: list_lru_del.cold (STB_LOCAL)
ffffffff813e0520-ffffffff813e068d: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item, int nid, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:120
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del_obj
  - mm/zswap.c:zswap_lru_del
```
**Symbols:**

```
ffffffff821bfd95-ffffffff821bfdb9: list_lru_del.cold (STB_LOCAL)
ffffffff8140ad90-ffffffff8140aea5: list_lru_del (STB_GLOBAL)
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
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffff8000102ef430)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_del
```
**Symbols:**

```
ffff8000102ef430-ffff8000102ef590: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0512f04)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
```
**Symbols:**

```
c0512f04-c0513034: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0000000003b3a70)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_del
```
**Symbols:**

```
c0000000003b3a70-c0000000003b3c68: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffe0002031d0)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
```
**Symbols:**

```
ffffffe0002031d0-ffffffe00020331a: list_lru_del (STB_GLOBAL)
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
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124ff60)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff8124ff60-ffffffff812500c5: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81242f00)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff81242f00-ffffffff81243065: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124dd00)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff8124dd00-ffffffff8124de65: list_lru_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool list_lru_del(struct list_lru *lru, struct list_head *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8125d6b0)
Location: mm/list_lru.c:149
Inline: False
Direct callers:
  - fs/dcache.c:d_lru_del
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
**Symbols:**

```
ffffffff8125d6b0-ffffffff8125d80d: list_lru_del (STB_GLOBAL)
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
