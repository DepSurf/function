# Function: <code>xp_free</code>

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
void xp_free(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba94c0)
Location: net/xdp/xsk_buff_pool.c:254
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81ba94c0-ffffffff81ba94f3: xp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xp_free(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb8cb0)
Location: net/xdp/xsk_buff_pool.c:524
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81bb8cb0-ffffffff81bb8ce6: xp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xp_free(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba7ec0)
Location: net/xdp/xsk_buff_pool.c:518
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81ba7ec0-ffffffff81ba7ef6: xp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xp_free(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81c75b50)
Location: net/xdp/xsk_buff_pool.c:518
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81c75b50-ffffffff81c75b86: xp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xp_free(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81e19d70)
Location: net/xdp/xsk_buff_pool.c:637
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81e19d70-ffffffff81e19dc9: xp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xp_free(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1160)
Location: net/xdp/xsk_buff_pool.c:642
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81ff1160-ffffffff81ff11b9: xp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xp_free(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff8206d380)
Location: net/xdp/xsk_buff_pool.c:646
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff8206d380-ffffffff8206d3d9: xp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xp_free(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff82141220)
Location: net/xdp/xsk_buff_pool.c:671
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff82141220-ffffffff82141279: xp_free (STB_GLOBAL)
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
