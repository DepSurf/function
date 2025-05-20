# Function: <code>__xp_alloc</code>

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
struct xdp_buff_xsk *__xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9580)
Location: net/xdp/xsk_buff_pool.c:179
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81ba9580-ffffffff81ba96d4: __xp_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xdp_buff_xsk *__xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9180)
Location: net/xdp/xsk_buff_pool.c:448
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81bb9180-ffffffff81bb9321: __xp_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xdp_buff_xsk *__xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8190)
Location: net/xdp/xsk_buff_pool.c:442
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81ba8190-ffffffff81ba832d: __xp_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct xdp_buff_xsk *__xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:442
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81c75ee0-ffffffff81c760b4: __xp_alloc (STB_LOCAL)
ffffffff81d4316d-ffffffff81d43182: __xp_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct xdp_buff_xsk *__xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:470
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81e1a220-ffffffff81e1a416: __xp_alloc (STB_LOCAL)
ffffffff81f0fb25-ffffffff81f0fb73: __xp_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct xdp_buff_xsk *__xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:475
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81ff1720-ffffffff81ff1916: __xp_alloc (STB_LOCAL)
ffffffff820b5ee2-ffffffff820b5f30: __xp_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct xdp_buff_xsk *__xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:479
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff8206d930-ffffffff8206db18: __xp_alloc (STB_LOCAL)
ffffffff8213742b-ffffffff82137479: __xp_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct xdp_buff_xsk *__xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:503
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff82141970-ffffffff82141b5c: __xp_alloc (STB_LOCAL)
ffffffff822192e6-ffffffff82219334: __xp_alloc.cold (STB_LOCAL)
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
