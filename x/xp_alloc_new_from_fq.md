# Function: <code>xp_alloc_new_from_fq</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 xp_alloc_new_from_fq(struct xsk_buff_pool *pool, struct xdp_buff **xdp, u32 max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:535
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
```
**Symbols:**

```
ffffffff81e1a7e0-ffffffff81e1a9f6: xp_alloc_new_from_fq (STB_LOCAL)
ffffffff81f0fb9c-ffffffff81f0fc06: xp_alloc_new_from_fq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 xp_alloc_new_from_fq(struct xsk_buff_pool *pool, struct xdp_buff **xdp, u32 max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:540
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
```
**Symbols:**

```
ffffffff81ff1cb0-ffffffff81ff1ec6: xp_alloc_new_from_fq (STB_LOCAL)
ffffffff820b5f59-ffffffff820b5fc3: xp_alloc_new_from_fq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 xp_alloc_new_from_fq(struct xsk_buff_pool *pool, struct xdp_buff **xdp, u32 max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:544
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
```
**Symbols:**

```
ffffffff8206dec0-ffffffff8206e0cc: xp_alloc_new_from_fq (STB_LOCAL)
ffffffff821374a2-ffffffff8213750c: xp_alloc_new_from_fq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 xp_alloc_new_from_fq(struct xsk_buff_pool *pool, struct xdp_buff **xdp, u32 max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:569
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
```
**Symbols:**

```
ffffffff82141f40-ffffffff82142150: xp_alloc_new_from_fq (STB_LOCAL)
ffffffff8221935d-ffffffff822193c7: xp_alloc_new_from_fq.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
