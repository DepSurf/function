# Function: <code>nvm_set_chunk_meta</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8169b1ed-ffffffff8169b21a: nvm_set_chunk_meta.cold.28 (STB_LOCAL)
ffffffff81699610-ffffffff816997e1: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1040
Inline: False
```
**Symbols:**

```
ffffffff816d3b76-ffffffff816d3ba3: nvm_set_chunk_meta.cold (STB_LOCAL)
ffffffff816d20b0-ffffffff816d2287: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1070
Inline: False
```
**Symbols:**

```
ffffffff816f7a45-ffffffff816f7a72: nvm_set_chunk_meta.cold (STB_LOCAL)
ffffffff816f5f90-ffffffff816f6167: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1069
Inline: False
```
**Symbols:**

```
ffffffff817b063c-ffffffff817b0669: nvm_set_chunk_meta.cold (STB_LOCAL)
ffffffff817aed00-ffffffff817aeed5: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1064
Inline: False
```
**Symbols:**

```
ffffffff81c0d8f0-ffffffff81c0d91d: nvm_set_chunk_meta.cold (STB_LOCAL)
ffffffff817c3880-ffffffff817c3a55: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1064
Inline: False
```
**Symbols:**

```
ffffffff81bffc64-ffffffff81bffc91: nvm_set_chunk_meta.cold (STB_LOCAL)
ffffffff817a6a50-ffffffff817a6c24: nvm_set_chunk_meta (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108df4a0)
Location: drivers/lightnvm/core.c:1070
Inline: False
```
**Symbols:**

```
ffff8000108df4a0-ffff8000108df690: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09ce9e4)
Location: drivers/lightnvm/core.c:1070
Inline: False
```
**Symbols:**

```
c09ce9e4-c09cebec: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c0000000009736b0)
Location: drivers/lightnvm/core.c:1070
Inline: False
```
**Symbols:**

```
c0000000009736b0-c000000000973970: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe0005758da)
Location: drivers/lightnvm/core.c:1070
Inline: False
```
**Symbols:**

```
ffffffe0005758da-ffffffe000575a82: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1070
Inline: False
```
**Symbols:**

```
ffffffff816bd235-ffffffff816bd262: nvm_set_chunk_meta.cold (STB_LOCAL)
ffffffff816bb780-ffffffff816bb957: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1070
Inline: False
```
**Symbols:**

```
ffffffff816eb705-ffffffff816eb732: nvm_set_chunk_meta.cold (STB_LOCAL)
ffffffff816e9c50-ffffffff816e9e27: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nvm_set_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1070
Inline: False
```
**Symbols:**

```
ffffffff81705f45-ffffffff81705f72: nvm_set_chunk_meta.cold (STB_LOCAL)
ffffffff81704490-ffffffff81704667: nvm_set_chunk_meta (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
