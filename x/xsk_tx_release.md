# Function: <code>xsk_tx_release</code>

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
void xsk_tx_release(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb5700)
Location: net/xdp/xsk.c:302
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81bb5700-ffffffff81bb5784: xsk_tx_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xsk_tx_release(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba46f0)
Location: net/xdp/xsk.c:317
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81ba46f0-ffffffff81ba476e: xsk_tx_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xsk_tx_release(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c72260)
Location: net/xdp/xsk.c:317
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81c72260-ffffffff81c722de: xsk_tx_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xsk_tx_release(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e15e20)
Location: net/xdp/xsk.c:302
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81e15e20-ffffffff81e15eb2: xsk_tx_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xsk_tx_release(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fece40)
Location: net/xdp/xsk.c:302
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff81fece40-ffffffff81feced2: xsk_tx_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xsk_tx_release(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff820690e0)
Location: net/xdp/xsk.c:303
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff820690e0-ffffffff82069172: xsk_tx_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xsk_tx_release(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213c370)
Location: net/xdp/xsk.c:415
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
**Symbols:**

```
ffffffff8213c370-ffffffff8213c402: xsk_tx_release (STB_GLOBAL)
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
