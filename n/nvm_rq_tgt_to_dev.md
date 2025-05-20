# Function: <code>nvm_rq_tgt_to_dev</code>

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
void nvm_rq_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d77c0)
Location: drivers/lightnvm/core.c:486
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_submit_io
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff815d77c0-ffffffff815d77ee: nvm_rq_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvm_rq_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163e5b0)
Location: drivers/lightnvm/core.c:507
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff8163e5b0-ffffffff8163e5de: nvm_rq_tgt_to_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvm_rq_tgt_to_dev(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81679c50)
Location: drivers/lightnvm/core.c:599
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
**Symbols:**

```
ffffffff81679c50-ffffffff81679c7e: nvm_rq_tgt_to_dev (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff8169972e)
Location: drivers/lightnvm/core.c:604
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff816d21d0)
Location: drivers/lightnvm/core.c:606
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff816f60b0)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff817aee26)
Location: drivers/lightnvm/core.c:610
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff817c39a6)
Location: drivers/lightnvm/core.c:606
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff817a6b75)
Location: drivers/lightnvm/core.c:606
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffff8000108df5ac)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (c09ceb0c)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (c000000000973800)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffe0005759d8)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff816bb8a0)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff816e9d70)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff817045b0)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_set_chunk_meta
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
</ul>
