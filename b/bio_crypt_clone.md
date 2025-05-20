# Function: <code>bio_crypt_clone</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f322)
Location: include/linux/blk-crypto.h:116
Inline: True
Inline callers:
  - block/bio.c:bio_clone_fast
```
```
In block/bounce.c (ffffffff815667db)
Location: include/linux/blk-crypto.h:116
Inline: True
```
```
In drivers/md/dm.c (ffffffff819770be)
Location: include/linux/blk-crypto.h:116
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155bb22)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - block/bio.c:bio_clone_fast
```
```
In block/bounce.c (ffffffff815816f0)
Location: include/linux/blk-crypto.h:127
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197bcbe)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815641b2)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - block/bio.c:bio_clone_fast
```
```
In drivers/md/dm.c (ffffffff819611dc)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c84a2)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - block/bio.c:bio_clone_fast
```
```
In drivers/md/dm.c (ffffffff81a0adfc)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671449)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - block/bio.c:__bio_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172cbfc)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - block/bio.c:__bio_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81768f7c)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - block/bio.c:__bio_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817aafac)
Location: include/linux/blk-crypto.h:127
Inline: True
Inline callers:
  - block/bio.c:__bio_clone
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
