# Function: <code>xp_destroy</code>

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
void xp_destroy(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9c7a)
Location: net/xdp/xsk_buff_pool.c:22
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create
  - net/xdp/xsk_buff_pool.c:xp_create
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ba9af0-ffffffff81ba9b25: xp_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xp_destroy(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9816)
Location: net/xdp/xsk_buff_pool.c:35
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81bb9910-ffffffff81bb993e: xp_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xp_destroy(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba87f6)
Location: net/xdp/xsk_buff_pool.c:35
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ba88f0-ffffffff81ba891e: xp_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xp_destroy(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81c7654b)
Location: net/xdp/xsk_buff_pool.c:35
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81c76640-ffffffff81c7666e: xp_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xp_destroy(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81e1ad0b)
Location: net/xdp/xsk_buff_pool.c:35
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81e1ae50-ffffffff81e1ae95: xp_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xp_destroy(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ff221b)
Location: net/xdp/xsk_buff_pool.c:35
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ff2390-ffffffff81ff23d5: xp_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xp_destroy(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff8206e44b)
Location: net/xdp/xsk_buff_pool.c:35
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8206e5c0-ffffffff8206e605: xp_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xp_destroy(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff821424cb)
Location: net/xdp/xsk_buff_pool.c:35
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff82142640-ffffffff82142685: xp_destroy (STB_GLOBAL)
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
