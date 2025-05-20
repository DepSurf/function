# Function: <code>xsk_reg_pool_at_qid</code>

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
int xsk_reg_pool_at_qid(struct net_device *dev, struct xsk_buff_pool *pool, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7cb0)
Location: net/xdp/xsk.c:121
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:__xp_assign_dev
```
**Symbols:**

```
ffffffff81bb7cb0-ffffffff81bb7d22: xsk_reg_pool_at_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xsk_reg_pool_at_qid(struct net_device *dev, struct xsk_buff_pool *pool, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6e30)
Location: net/xdp/xsk.c:121
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81ba6e30-ffffffff81ba6ea8: xsk_reg_pool_at_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xsk_reg_pool_at_qid(struct net_device *dev, struct xsk_buff_pool *pool, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c74ab0)
Location: net/xdp/xsk.c:121
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81c74ab0-ffffffff81c74b2c: xsk_reg_pool_at_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xsk_reg_pool_at_qid(struct net_device *dev, struct xsk_buff_pool *pool, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e18b50)
Location: net/xdp/xsk.c:121
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81e18b50-ffffffff81e18beb: xsk_reg_pool_at_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xsk_reg_pool_at_qid(struct net_device *dev, struct xsk_buff_pool *pool, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fefdd0)
Location: net/xdp/xsk.c:121
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81fefdd0-ffffffff81fefe6b: xsk_reg_pool_at_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xsk_reg_pool_at_qid(struct net_device *dev, struct xsk_buff_pool *pool, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206bf70)
Location: net/xdp/xsk.c:122
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff8206bf70-ffffffff8206c00b: xsk_reg_pool_at_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xsk_reg_pool_at_qid(struct net_device *dev, struct xsk_buff_pool *pool, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213fb30)
Location: net/xdp/xsk.c:124
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff8213fb30-ffffffff8213fbc2: xsk_reg_pool_at_qid (STB_GLOBAL)
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
