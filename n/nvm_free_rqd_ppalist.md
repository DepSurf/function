# Function: <code>nvm_free_rqd_ppalist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_dev *dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815429a0)
Location: drivers/lightnvm/core.c:276
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/core.c:nvm_submit_ppa
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff815429a0-ffffffff815429cc: nvm_free_rqd_ppalist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_dev *dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81594d93)
Location: drivers/lightnvm/core.c:279
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/lightnvm/core.c:nvm_erase_ppa
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff815942e0-ffffffff8159430c: nvm_free_rqd_ppalist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_dev *dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c2a43)
Location: drivers/lightnvm/core.c:374
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
  - drivers/lightnvm/core.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff815c1bd0-ffffffff815c1bfc: nvm_free_rqd_ppalist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d7f0d)
Location: drivers/lightnvm/core.c:820
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_erase_sync
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff815d79e0-ffffffff815d7a11: nvm_free_rqd_ppalist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163eb7f)
Location: drivers/lightnvm/core.c:643
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_erase_sync
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8167a105)
Location: drivers/lightnvm/core.c:706
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81699768)
Location: drivers/lightnvm/core.c:705
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d2203)
Location: drivers/lightnvm/core.c:707
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f60e3)
Location: drivers/lightnvm/core.c:712
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817aee59)
Location: drivers/lightnvm/core.c:711
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c39d9)
Location: drivers/lightnvm/core.c:707
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a6ba8)
Location: drivers/lightnvm/core.c:707
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108df5e4)
Location: drivers/lightnvm/core.c:712
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09ceb48)
Location: drivers/lightnvm/core.c:712
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000973848)
Location: drivers/lightnvm/core.c:712
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000575a08)
Location: drivers/lightnvm/core.c:712
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bb8d3)
Location: drivers/lightnvm/core.c:712
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9da3)
Location: drivers/lightnvm/core.c:712
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817045e3)
Location: drivers/lightnvm/core.c:712
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nvm_tgt_dev *tgt_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_dev *dev</code>
</li>
</ul>
</details>
</li>
</ul>
