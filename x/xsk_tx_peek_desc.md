# Function: <code>xsk_tx_peek_desc</code>

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
bool xsk_tx_peek_desc(struct xsk_buff_pool *pool, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7270)
Location: net/xdp/xsk.c:316
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81bb7270-ffffffff81bb743f: xsk_tx_peek_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool xsk_tx_peek_desc(struct xsk_buff_pool *pool, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6230)
Location: net/xdp/xsk.c:331
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81ba6230-ffffffff81ba6414: xsk_tx_peek_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool xsk_tx_peek_desc(struct xsk_buff_pool *pool, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:331
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81d43051-ffffffff81d43078: xsk_tx_peek_desc.cold (STB_LOCAL)
ffffffff81c73bd0-ffffffff81c73df0: xsk_tx_peek_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool xsk_tx_peek_desc(struct xsk_buff_pool *pool, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:316
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81f0f9b3-ffffffff81f0f9d0: xsk_tx_peek_desc.cold (STB_LOCAL)
ffffffff81e17440-ffffffff81e17688: xsk_tx_peek_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool xsk_tx_peek_desc(struct xsk_buff_pool *pool, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:316
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff820b5d34-ffffffff820b5d51: xsk_tx_peek_desc.cold (STB_LOCAL)
ffffffff81fee170-ffffffff81fee3b8: xsk_tx_peek_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool xsk_tx_peek_desc(struct xsk_buff_pool *pool, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:317
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff8213727b-ffffffff82137298: xsk_tx_peek_desc.cold (STB_LOCAL)
ffffffff8206a2d0-ffffffff8206a4dd: xsk_tx_peek_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool xsk_tx_peek_desc(struct xsk_buff_pool *pool, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:429
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff82219100-ffffffff82219129: xsk_tx_peek_desc.cold (STB_LOCAL)
ffffffff8213d980-ffffffff8213dc29: xsk_tx_peek_desc (STB_GLOBAL)
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
