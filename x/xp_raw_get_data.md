# Function: <code>xp_raw_get_data</code>

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
void *xp_raw_get_data(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9500)
Location: net/xdp/xsk_buff_pool.c:261
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81ba9500-ffffffff81ba952c: xp_raw_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xp_raw_get_data(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb8cf0)
Location: net/xdp/xsk_buff_pool.c:531
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81bb8cf0-ffffffff81bb8d22: xp_raw_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xp_raw_get_data(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba7f00)
Location: net/xdp/xsk_buff_pool.c:525
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
**Symbols:**

```
ffffffff81ba7f00-ffffffff81ba7f32: xp_raw_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *xp_raw_get_data(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:525
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
**Symbols:**

```
ffffffff81d430ec-ffffffff81d43109: xp_raw_get_data.cold (STB_LOCAL)
ffffffff81c75c90-ffffffff81c75ce2: xp_raw_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *xp_raw_get_data(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:647
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
**Symbols:**

```
ffffffff81f0faa4-ffffffff81f0fac1: xp_raw_get_data.cold (STB_LOCAL)
ffffffff81e19f90-ffffffff81e19fec: xp_raw_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *xp_raw_get_data(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:652
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
**Symbols:**

```
ffffffff820b5e4f-ffffffff820b5e6c: xp_raw_get_data.cold (STB_LOCAL)
ffffffff81ff13d0-ffffffff81ff142c: xp_raw_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *xp_raw_get_data(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:656
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
**Symbols:**

```
ffffffff82137398-ffffffff821373b5: xp_raw_get_data.cold (STB_LOCAL)
ffffffff8206d5f0-ffffffff8206d64c: xp_raw_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *xp_raw_get_data(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:681
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
**Symbols:**

```
ffffffff8221922e-ffffffff8221924b: xp_raw_get_data.cold (STB_LOCAL)
ffffffff82141490-ffffffff821414ec: xp_raw_get_data (STB_GLOBAL)
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
