# Function: <code>dma_buf_pin</code>

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
int dma_buf_pin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff818259b6)
Location: drivers/dma-buf/dma-buf.c:814
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
**Symbols:**

```
ffffffff81824770-ffffffff81824793: dma_buf_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_pin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81836396)
Location: drivers/dma-buf/dma-buf.c:827
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
**Symbols:**

```
ffffffff818350f0-ffffffff81835113: dma_buf_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_buf_pin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81818310)
Location: drivers/dma-buf/dma-buf.c:875
Inline: False
```
**Symbols:**

```
ffffffff81818310-ffffffff8181833e: dma_buf_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_buf_pin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff818a2990)
Location: drivers/dma-buf/dma-buf.c:879
Inline: False
```
**Symbols:**

```
ffffffff818a2990-ffffffff818a29be: dma_buf_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_buf_pin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff819ec1d0)
Location: drivers/dma-buf/dma-buf.c:871
Inline: False
```
**Symbols:**

```
ffffffff819ec1d0-ffffffff819ec20e: dma_buf_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_buf_pin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81b68e70)
Location: drivers/dma-buf/dma-buf.c:1045
Inline: False
```
**Symbols:**

```
ffffffff81b68e70-ffffffff81b68eae: dma_buf_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_buf_pin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81bbc290)
Location: drivers/dma-buf/dma-buf.c:1045
Inline: False
```
**Symbols:**

```
ffffffff81bbc290-ffffffff81bbc2ce: dma_buf_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_buf_pin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81c10a90)
Location: drivers/dma-buf/dma-buf.c:1040
Inline: False
```
**Symbols:**

```
ffffffff81c10a90-ffffffff81c10ace: dma_buf_pin (STB_GLOBAL)
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
