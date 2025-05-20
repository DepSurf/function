# Function: <code>nvm_set_rqd_ppalist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_set_rqd_ppalist(struct nvm_dev *dev, struct nvm_rq *rqd, struct ppa_addr *ppas, int nr_ppas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81542bf0)
Location: drivers/lightnvm/core.c:241
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/lightnvm/sysblk.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff81542bf0-ffffffff81542cdd: nvm_set_rqd_ppalist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_set_rqd_ppalist(struct nvm_dev *dev, struct nvm_rq *rqd, const struct ppa_addr *ppas, int nr_ppas, int vblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81594800)
Location: drivers/lightnvm/core.c:239
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/sysblk.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff81594800-ffffffff8159496d: nvm_set_rqd_ppalist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_set_rqd_ppalist(struct nvm_dev *dev, struct nvm_rq *rqd, const struct ppa_addr *ppas, int nr_ppas, int vblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c2110)
Location: drivers/lightnvm/core.c:333
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
  - drivers/lightnvm/core.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff815c2110-ffffffff815c227d: nvm_set_rqd_ppalist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nvm_set_rqd_ppalist(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, const struct ppa_addr *ppas, int nr_ppas, int vblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d7bb0)
Location: drivers/lightnvm/core.c:778
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_erase_sync
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff815d7bb0-ffffffff815d7d25: nvm_set_rqd_ppalist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvm_set_rqd_ppalist(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, const struct ppa_addr *ppas, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163e8f0)
Location: drivers/lightnvm/core.c:607
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_erase_sync
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff8163e8f0-ffffffff8163e9ed: nvm_set_rqd_ppalist (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff8167a020)
Location: drivers/lightnvm/core.c:670
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
In drivers/lightnvm/core.c (ffffffff8169967c)
Location: drivers/lightnvm/core.c:669
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
In drivers/lightnvm/core.c (ffffffff816d211c)
Location: drivers/lightnvm/core.c:671
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
In drivers/lightnvm/core.c (ffffffff816f5ffc)
Location: drivers/lightnvm/core.c:676
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
In drivers/lightnvm/core.c (ffffffff817aed67)
Location: drivers/lightnvm/core.c:675
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
In drivers/lightnvm/core.c (ffffffff817c38e7)
Location: drivers/lightnvm/core.c:671
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
In drivers/lightnvm/core.c (ffffffff817a6ab7)
Location: drivers/lightnvm/core.c:671
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
In drivers/lightnvm/core.c (ffff8000108df518)
Location: drivers/lightnvm/core.c:676
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
In drivers/lightnvm/core.c (c09cea48)
Location: drivers/lightnvm/core.c:676
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
In drivers/lightnvm/core.c (c000000000973730)
Location: drivers/lightnvm/core.c:676
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
In drivers/lightnvm/core.c (ffffffe000575916)
Location: drivers/lightnvm/core.c:676
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
In drivers/lightnvm/core.c (ffffffff816bb7ec)
Location: drivers/lightnvm/core.c:676
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
In drivers/lightnvm/core.c (ffffffff816e9cbc)
Location: drivers/lightnvm/core.c:676
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
In drivers/lightnvm/core.c (ffffffff817044fc)
Location: drivers/lightnvm/core.c:676
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int vblk</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct ppa_addr *ppas</code> ➡️ <code>const struct ppa_addr *ppas</code>
</li>
</ul>
</details>
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
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int vblk</code>
</li>
</ul>
</details>
</li>
</ul>
