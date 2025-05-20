# Function: <code>xp_assign_dev</code>

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
int xp_assign_dev(struct xsk_buff_pool *pool, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9af0)
Location: net/xdp/xsk_buff_pool.c:194
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81bb9af0-ffffffff81bb9b06: xp_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xp_assign_dev(struct xsk_buff_pool *pool, struct net_device *netdev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8ad0)
Location: net/xdp/xsk_buff_pool.c:122
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_assign_dev_shared
```
**Symbols:**

```
ffffffff81ba8ad0-ffffffff81ba8cae: xp_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev(struct xsk_buff_pool *pool, struct net_device *netdev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:122
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_assign_dev_shared
```
**Symbols:**

```
ffffffff81d431ab-ffffffff81d431c0: xp_assign_dev.cold (STB_LOCAL)
ffffffff81c76820-ffffffff81c76a17: xp_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev(struct xsk_buff_pool *pool, struct net_device *netdev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:143
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_assign_dev_shared
```
**Symbols:**

```
ffffffff81f0fc36-ffffffff81f0fc4b: xp_assign_dev.cold (STB_LOCAL)
ffffffff81e1b150-ffffffff81e1b370: xp_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev(struct xsk_buff_pool *pool, struct net_device *netdev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:143
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_assign_dev_shared
```
**Symbols:**

```
ffffffff820b5ff3-ffffffff820b6008: xp_assign_dev.cold (STB_LOCAL)
ffffffff81ff26c0-ffffffff81ff28e0: xp_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev(struct xsk_buff_pool *pool, struct net_device *netdev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:147
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_assign_dev_shared
```
**Symbols:**

```
ffffffff8213753c-ffffffff82137551: xp_assign_dev.cold (STB_LOCAL)
ffffffff8206e8e0-ffffffff8206eafd: xp_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xp_assign_dev(struct xsk_buff_pool *pool, struct net_device *netdev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:163
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_assign_dev_shared
```
**Symbols:**

```
ffffffff822193f7-ffffffff8221940c: xp_assign_dev.cold (STB_LOCAL)
ffffffff821429a0-ffffffff82142bd7: xp_assign_dev (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *netdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net_device *dev</code>
</li>
</ul>
</details>
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
