# Function: <code>generic_to_dev_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: include/linux/lightnvm.h:356
Inline: True
```
```
In drivers/lightnvm/sysblk.c (0)
Location: include/linux/lightnvm.h:356
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815943bc)
Location: include/linux/lightnvm.h:361
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_tbl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c1ca5)
Location: include/linux/lightnvm.h:394
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_tbl
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
  - drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d75ea)
Location: include/linux/lightnvm.h:376
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff8163e3da)
Location: include/linux/lightnvm.h:379
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff81679a18)
Location: include/linux/lightnvm.h:432
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff81699951)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff816d24fa)
Location: include/linux/lightnvm.h:442
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff816f63da)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff817af30b)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
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
In drivers/lightnvm/core.c (ffffffff817c3e8b)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
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
In drivers/lightnvm/core.c (ffffffff817a71a5)
Location: include/linux/lightnvm.h:438
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
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
In drivers/lightnvm/core.c (ffff8000108dfb08)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (c09ced6c)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (c000000000973bf0)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffe000575c64)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff816bbbca)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff816ea09a)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
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
In drivers/lightnvm/core.c (ffffffff817048da)
Location: include/linux/lightnvm.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_ppa_tgt_to_dev
```
</details>
</li>
</ul>

## Differences
