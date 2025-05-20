# Function: <code>xp_release</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xp_release(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7473)
Location: net/xdp/xsk.c:102
Inline: True
Direct callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
**Symbols:**

```
ffffffff81ba8050-ffffffff81ba806d: xp_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xp_release(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb6bbb)
Location: net/xdp/xsk.c:137
Inline: True
Direct callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
**Symbols:**

```
ffffffff81bb7d30-ffffffff81bb7d56: xp_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xp_release(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba5b6f)
Location: net/xdp/xsk.c:137
Inline: True
Direct callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
**Symbols:**

```
ffffffff81ba6eb0-ffffffff81ba6ed6: xp_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xp_release(struct xdp_buff_xsk *xskb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c735e1)
Location: net/xdp/xsk.c:137
Inline: True
Direct callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
**Symbols:**

```
ffffffff81c74b30-ffffffff81c74b56: xp_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e171af)
Location: include/net/xsk_buff_pool.h:213
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv_zc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fedfff)
Location: include/net/xsk_buff_pool.h:213
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv_zc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206a15f)
Location: include/net/xsk_buff_pool.h:213
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv_zc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213d628)
Location: include/net/xsk_buff_pool.h:225
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv_zc
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
</ul>
