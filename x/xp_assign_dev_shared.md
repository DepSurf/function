# Function: <code>xp_assign_dev_shared</code>

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
int xp_assign_dev_shared(struct xsk_buff_pool *pool, struct xdp_umem *umem, struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9b10)
Location: net/xdp/xsk_buff_pool.c:200
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81bb9b10-ffffffff81bb9b60: xp_assign_dev_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool *pool, struct xdp_umem *umem, struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8cb0)
Location: net/xdp/xsk_buff_pool.c:194
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ba8cb0-ffffffff81ba8d00: xp_assign_dev_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool *pool, struct xdp_umem *umem, struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:194
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81d431c0-ffffffff81d431fb: xp_assign_dev_shared.cold (STB_LOCAL)
ffffffff81c76a20-ffffffff81c76ab5: xp_assign_dev_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool *pool, struct xdp_umem *umem, struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:215
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81f0fc4b-ffffffff81f0fc86: xp_assign_dev_shared.cold (STB_LOCAL)
ffffffff81e1b370-ffffffff81e1b421: xp_assign_dev_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool *pool, struct xdp_sock *umem_xs, struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:215
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff820b6008-ffffffff820b6044: xp_assign_dev_shared.cold (STB_LOCAL)
ffffffff81ff28f0-ffffffff81ff29ba: xp_assign_dev_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool *pool, struct xdp_sock *umem_xs, struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:218
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff82137551-ffffffff82137586: xp_assign_dev_shared.cold (STB_LOCAL)
ffffffff8206eb10-ffffffff8206ebdb: xp_assign_dev_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev_shared(struct xsk_buff_pool *pool, struct xdp_sock *umem_xs, struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:242
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8221940c-ffffffff82219441: xp_assign_dev_shared.cold (STB_LOCAL)
ffffffff82142bf0-ffffffff82142cbb: xp_assign_dev_shared (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_sock *umem_xs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_umem *umem</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
