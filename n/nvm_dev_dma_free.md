# Function: <code>nvm_dev_dma_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *ppa_list, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815428c0)
Location: drivers/lightnvm/core.c:83
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/core.c:nvm_submit_ppa
```
**Symbols:**

```
ffffffff815428c0-ffffffff815428db: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81594d9c)
Location: drivers/lightnvm/core.c:89
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/lightnvm/core.c:nvm_erase_ppa
```
**Symbols:**

```
ffffffff81594220-ffffffff8159423b: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c2a4c)
Location: drivers/lightnvm/core.c:89
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
  - drivers/lightnvm/core.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff815c1ae0-ffffffff815c1afb: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d7f1d)
Location: drivers/lightnvm/core.c:588
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_erase_sync
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff815d7900-ffffffff815d791b: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163eb8b)
Location: drivers/lightnvm/core.c:590
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_erase_sync
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff8163e700-ffffffff8163e721: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8167a111)
Location: drivers/lightnvm/core.c:653
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff81679ce0-ffffffff81679d01: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81699774)
Location: drivers/lightnvm/core.c:652
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff81698a90-ffffffff81698ab1: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d2210)
Location: drivers/lightnvm/core.c:654
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff816d15c0-ffffffff816d15e1: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f60f0)
Location: drivers/lightnvm/core.c:659
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff816f53e0-ffffffff816f5401: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817aee65)
Location: drivers/lightnvm/core.c:658
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff817adce0-ffffffff817add01: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c39e5)
Location: drivers/lightnvm/core.c:654
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff817c2880-ffffffff817c28a1: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a6bb4)
Location: drivers/lightnvm/core.c:654
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff817a5d40-ffffffff817a5d61: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108df5f0)
Location: drivers/lightnvm/core.c:659
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffff8000108dea30-ffff8000108dea7c: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09ceb50)
Location: drivers/lightnvm/core.c:659
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
c09cdae8-c09cdb10: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000973854)
Location: drivers/lightnvm/core.c:659
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
c0000000009723a0-c0000000009723e8: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000575a0e)
Location: drivers/lightnvm/core.c:659
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffe000574ca6-ffffffe000574cde: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bb8e0)
Location: drivers/lightnvm/core.c:659
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff816babd0-ffffffff816babf1: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9db0)
Location: drivers/lightnvm/core.c:659
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff816e90a0-ffffffff816e90c1: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nvm_dev_dma_free(struct nvm_dev *dev, void *addr, dma_addr_t dma_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817045f0)
Location: drivers/lightnvm/core.c:659
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
**Symbols:**

```
ffffffff817038e0-ffffffff81703901: nvm_dev_dma_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *addr</code>
</li>
<li>
<b>Param removed. </b>
<code>void *ppa_list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
