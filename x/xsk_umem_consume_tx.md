# Function: <code>xsk_umem_consume_tx</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, dma_addr_t *dma, u32 *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cc3b0)
Location: net/xdp/xsk.c:161
Inline: False
```
**Symbols:**

```
ffffffff819cc3b0-ffffffff819cc513: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, dma_addr_t *dma, u32 *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a045c0)
Location: net/xdp/xsk.c:173
Inline: False
```
**Symbols:**

```
ffffffff81a045c0-ffffffff81a04723: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a74d60)
Location: net/xdp/xsk.c:187
Inline: False
```
**Symbols:**

```
ffffffff81a74d60-ffffffff81a74ea5: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aab930)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
ffffffff81aab930-ffffffff81aabaf3: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7240)
Location: net/xdp/xsk.c:271
Inline: False
```
**Symbols:**

```
ffffffff81ba7240-ffffffff81ba73e5: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7ee28)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
ffff800010d7ee28-ffff800010d7f01c: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e79b24)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
c0e79b24-c0e79df0: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebf9f0)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
c000000000ebf9f0-c000000000ebfce4: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008ac8da)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
ffffffe0008ac8da-ffffffe0008acaa2: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a4acc0)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
ffffffff81a4acc0-ffffffff81a4ae83: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a078b0)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
ffffffff81a078b0-ffffffff81a07a73: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab6b70)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
ffffffff81ab6b70-ffffffff81ab6d33: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool xsk_umem_consume_tx(struct xdp_umem *umem, struct xdp_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac17e0)
Location: net/xdp/xsk.c:285
Inline: False
```
**Symbols:**

```
ffffffff81ac17e0-ffffffff81ac19b9: xsk_umem_consume_tx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_desc *desc</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t *dma</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
