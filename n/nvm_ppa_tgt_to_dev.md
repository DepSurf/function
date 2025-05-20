# Function: <code>nvm_ppa_tgt_to_dev</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d75a0)
Location: drivers/lightnvm/core.c:464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_tgt_bb_tbl
  - drivers/lightnvm/core.c:nvm_rq_tgt_to_dev
  - drivers/lightnvm/core.c:nvm_rq_tgt_to_dev
```
**Symbols:**

```
ffffffff815d75a0-ffffffff815d765f: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163e390)
Location: drivers/lightnvm/core.c:485
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_tgt_bb_tbl
  - drivers/lightnvm/core.c:nvm_rq_tgt_to_dev
  - drivers/lightnvm/core.c:nvm_rq_tgt_to_dev
```
**Symbols:**

```
ffffffff8163e390-ffffffff8163e44f: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81679970)
Location: drivers/lightnvm/core.c:577
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_tgt_bb_tbl
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_rq_tgt_to_dev
  - drivers/lightnvm/core.c:nvm_rq_tgt_to_dev
```
**Symbols:**

```
ffffffff81679970-ffffffff81679aa8: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81699320)
Location: drivers/lightnvm/core.c:582
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff81699320-ffffffff81699458: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d1db0)
Location: drivers/lightnvm/core.c:584
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff816d1db0-ffffffff816d1ef4: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f5ca0)
Location: drivers/lightnvm/core.c:589
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff816f5ca0-ffffffff816f5de4: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817af2e2)
Location: drivers/lightnvm/core.c:588
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff817aebb0-ffffffff817aecf6: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c3e62)
Location: drivers/lightnvm/core.c:584
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff817c3730-ffffffff817c3876: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a7176)
Location: drivers/lightnvm/core.c:584
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff817a6900-ffffffff817a6a46: nvm_ppa_tgt_to_dev (STB_LOCAL)
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
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108df170)
Location: drivers/lightnvm/core.c:589
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffff8000108df170-ffff8000108df2b0: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09ce5f0)
Location: drivers/lightnvm/core.c:589
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
c09ce5f0-c09ce858: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c0000000009732b0)
Location: drivers/lightnvm/core.c:589
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
c0000000009732b0-c0000000009733f8: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000575614)
Location: drivers/lightnvm/core.c:589
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffe000575614-ffffffe000575746: nvm_ppa_tgt_to_dev (STB_LOCAL)
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
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bb490)
Location: drivers/lightnvm/core.c:589
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff816bb490-ffffffff816bb5d4: nvm_ppa_tgt_to_dev (STB_LOCAL)
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
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9960)
Location: drivers/lightnvm/core.c:589
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff816e9960-ffffffff816e9aa4: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvm_ppa_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct ppa_addr *ppa_list, int nr_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817041a0)
Location: drivers/lightnvm/core.c:589
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff817041a0-ffffffff817042e4: nvm_ppa_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
