# Function: <code>xp_check_unaligned</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9663)
Location: net/xdp/xsk_buff_pool.c:163
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk_buff_pool.c (ffffffff81bb929f)
Location: net/xdp/xsk_buff_pool.c:432
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk_buff_pool.c (ffffffff81ba82ac)
Location: net/xdp/xsk_buff_pool.c:426
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk_buff_pool.c (ffffffff81c76032)
Location: net/xdp/xsk_buff_pool.c:426
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xp_check_unaligned(struct xsk_buff_pool *pool, u64 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81e19dd0)
Location: net/xdp/xsk_buff_pool.c:454
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
**Symbols:**

```
ffffffff81e19dd0-ffffffff81e19e55: xp_check_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xp_check_unaligned(struct xsk_buff_pool *pool, u64 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ff11d0)
Location: net/xdp/xsk_buff_pool.c:459
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
**Symbols:**

```
ffffffff81ff11d0-ffffffff81ff1255: xp_check_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xp_check_unaligned(struct xsk_buff_pool *pool, u64 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff8206d3f0)
Location: net/xdp/xsk_buff_pool.c:463
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
**Symbols:**

```
ffffffff8206d3f0-ffffffff8206d480: xp_check_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xp_check_unaligned(struct xsk_buff_pool *pool, u64 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff82141290)
Location: net/xdp/xsk_buff_pool.c:487
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
**Symbols:**

```
ffffffff82141290-ffffffff82141320: xp_check_unaligned (STB_LOCAL)
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
