# Function: <code>xp_disable_drv_zc</code>

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
void xp_disable_drv_zc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb8d80)
Location: net/xdp/xsk_buff_pool.c:103
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:__xp_assign_dev
```
**Symbols:**

```
ffffffff81bb8d80-ffffffff81bb8e42: xp_disable_drv_zc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba7f90)
Location: net/xdp/xsk_buff_pool.c:103
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81ba7f90-ffffffff81ba8052: xp_disable_drv_zc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:103
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81c75df0-ffffffff81c75ed9: xp_disable_drv_zc (STB_LOCAL)
ffffffff81d43143-ffffffff81d4316d: xp_disable_drv_zc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:124
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81e1a070-ffffffff81e1a189: xp_disable_drv_zc (STB_LOCAL)
ffffffff81f0fad6-ffffffff81f0fb00: xp_disable_drv_zc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:124
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81ff14d0-ffffffff81ff15e9: xp_disable_drv_zc (STB_LOCAL)
ffffffff820b5e81-ffffffff820b5eab: xp_disable_drv_zc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:124
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff8206d6f0-ffffffff8206d809: xp_disable_drv_zc (STB_LOCAL)
ffffffff821373ca-ffffffff821373f4: xp_disable_drv_zc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:140
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff82141840-ffffffff82141956: xp_disable_drv_zc (STB_LOCAL)
ffffffff822192bc-ffffffff822192e6: xp_disable_drv_zc.cold (STB_LOCAL)
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
