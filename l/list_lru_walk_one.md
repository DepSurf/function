# Function: <code>list_lru_walk_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811b92b0)
Location: mm/list_lru.c:259
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff811b92b0-ffffffff811b92d5: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811d35b0)
Location: mm/list_lru.c:259
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff811d35b0-ffffffff811d35d5: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811e3460)
Location: mm/list_lru.c:259
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff811e3460-ffffffff811e3485: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811ed8a0)
Location: mm/list_lru.c:257
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff811ed8a0-ffffffff811ed8c5: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81203d00)
Location: mm/list_lru.c:258
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff81203d00-ffffffff81203d25: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81224890)
Location: mm/list_lru.c:259
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff81224890-ffffffff812248b5: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81237c30)
Location: mm/list_lru.c:270
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff81237c30-ffffffff81237ca2: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812491b0)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff812491b0-ffffffff81249221: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81257600)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff81257600-ffffffff81257671: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81285d75)
Location: mm/list_lru.c:258
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_node
Direct callers:
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff81285d00-ffffffff81285d6e: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81290051)
Location: mm/list_lru.c:258
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_node
Direct callers:
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff8128ffc0-ffffffff8129002e: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812956a1)
Location: mm/list_lru.c:258
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_node
Direct callers:
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff81295610-ffffffff8129567e: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812d5d11)
Location: mm/list_lru.c:258
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_node
Direct callers:
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff812d5c80-ffffffff812d5cee: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff813350a9)
Location: mm/list_lru.c:268
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_node
Direct callers:
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff81334fc0-ffffffff81335054: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff813abe29)
Location: mm/list_lru.c:268
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_node
Direct callers:
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff813abd30-ffffffff813abdc4: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff813e01c9)
Location: mm/list_lru.c:268
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_node
Direct callers:
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff813e00d0-ffffffff813e0164: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8140aa79)
Location: mm/list_lru.c:269
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_node
Direct callers:
  - mm/zswap.c:shrink_memcg
  - mm/zswap.c:zswap_shrinker_scan
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff8140a980-ffffffff8140aa14: list_lru_walk_one (STB_GLOBAL)
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
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffff8000102ef238)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffff8000102ef238-ffff8000102ef2fc: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0512aec)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
c0512aec-c0512b64: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0000000003b2e50)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
c0000000003b2e50-c0000000003b2f58: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffe000202ea2)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffe000202ea2-ffffffe000202f52: list_lru_walk_one (STB_GLOBAL)
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
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124fc50)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff8124fc50-ffffffff8124fcc1: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81242bf0)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff81242bf0-ffffffff81242c61: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124d9f0)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff8124d9f0-ffffffff8124da61: list_lru_walk_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8125d130)
Location: mm/list_lru.c:268
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - fs/dcache.c:prune_dcache_sb
  - fs/inode.c:prune_icache_sb
```
**Symbols:**

```
ffffffff8125d130-ffffffff8125d19f: list_lru_walk_one (STB_GLOBAL)
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
