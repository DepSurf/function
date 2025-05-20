# Function: <code>xp_create_and_assign_umem</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xsk_buff_pool *xp_create_and_assign_umem(struct xdp_sock *xs, struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9940)
Location: net/xdp/xsk_buff_pool.c:44
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81bb9940-ffffffff81bb9ae7: xp_create_and_assign_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xsk_buff_pool *xp_create_and_assign_umem(struct xdp_sock *xs, struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8920)
Location: net/xdp/xsk_buff_pool.c:44
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ba8920-ffffffff81ba8ac7: xp_create_and_assign_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xsk_buff_pool *xp_create_and_assign_umem(struct xdp_sock *xs, struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81c76670)
Location: net/xdp/xsk_buff_pool.c:44
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81c76670-ffffffff81c76817: xp_create_and_assign_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct xsk_buff_pool *xp_create_and_assign_umem(struct xdp_sock *xs, struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:55
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81f0fc1b-ffffffff81f0fc36: xp_create_and_assign_umem.cold (STB_LOCAL)
ffffffff81e1aef0-ffffffff81e1b144: xp_create_and_assign_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct xsk_buff_pool *xp_create_and_assign_umem(struct xdp_sock *xs, struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:55
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff820b5fd8-ffffffff820b5ff3: xp_create_and_assign_umem.cold (STB_LOCAL)
ffffffff81ff2450-ffffffff81ff26a4: xp_create_and_assign_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct xsk_buff_pool *xp_create_and_assign_umem(struct xdp_sock *xs, struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:55
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff82137521-ffffffff8213753c: xp_create_and_assign_umem.cold (STB_LOCAL)
ffffffff8206e680-ffffffff8206e8c2: xp_create_and_assign_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct xsk_buff_pool *xp_create_and_assign_umem(struct xdp_sock *xs, struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:55
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff822193dc-ffffffff822193f7: xp_create_and_assign_umem.cold (STB_LOCAL)
ffffffff82142700-ffffffff8214298c: xp_create_and_assign_umem (STB_GLOBAL)
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
