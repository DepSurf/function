# Function: <code>nvm_get_chunk_meta</code>

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
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct nvm_chk_meta *meta, struct ppa_addr ppa, int nchks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81679d10)
Location: drivers/lightnvm/core.c:715
Inline: False
```
**Symbols:**

```
ffffffff81679d10-ffffffff81679d70: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81699e30)
Location: drivers/lightnvm/core.c:1024
Inline: False
```
**Symbols:**

```
ffffffff81699e30-ffffffff81699ea8: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d29c0)
Location: drivers/lightnvm/core.c:1026
Inline: False
```
**Symbols:**

```
ffffffff816d29c0-ffffffff816d2a3c: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f68a0)
Location: drivers/lightnvm/core.c:1056
Inline: False
```
**Symbols:**

```
ffffffff816f68a0-ffffffff816f691c: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817af2b0)
Location: drivers/lightnvm/core.c:1055
Inline: False
```
**Symbols:**

```
ffffffff817af2b0-ffffffff817af3ad: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c3e30)
Location: drivers/lightnvm/core.c:1050
Inline: False
```
**Symbols:**

```
ffffffff817c3e30-ffffffff817c3f2d: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a7140)
Location: drivers/lightnvm/core.c:1050
Inline: False
```
**Symbols:**

```
ffffffff817a7140-ffffffff817a723c: nvm_get_chunk_meta (STB_GLOBAL)
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
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108dff38)
Location: drivers/lightnvm/core.c:1056
Inline: False
```
**Symbols:**

```
ffff8000108dff38-ffff8000108dffd0: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cf1b4)
Location: drivers/lightnvm/core.c:1056
Inline: False
```
**Symbols:**

```
c09cf1b4-c09cf23c: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000973fe0)
Location: drivers/lightnvm/core.c:1056
Inline: False
```
**Symbols:**

```
c000000000973fe0-c0000000009740b0: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000575f9a)
Location: drivers/lightnvm/core.c:1056
Inline: False
```
**Symbols:**

```
ffffffe000575f9a-ffffffe000576020: nvm_get_chunk_meta (STB_GLOBAL)
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
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bc090)
Location: drivers/lightnvm/core.c:1056
Inline: False
```
**Symbols:**

```
ffffffff816bc090-ffffffff816bc10c: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816ea560)
Location: drivers/lightnvm/core.c:1056
Inline: False
```
**Symbols:**

```
ffffffff816ea560-ffffffff816ea5dc: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvm_get_chunk_meta(struct nvm_tgt_dev *tgt_dev, struct ppa_addr ppa, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81704da0)
Location: drivers/lightnvm/core.c:1056
Inline: False
```
**Symbols:**

```
ffffffff81704da0-ffffffff81704e1c: nvm_get_chunk_meta (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>tgt_dev, meta, ppa, nchks</code> ➡️ <code>tgt_dev, ppa, nchks, meta</code>
</li>
</ul>
</details>
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
