# Function: <code>bvec_kmap_local</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c70e4)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
```
```
In block/bio-integrity.c (ffffffff81602363)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff8160390b)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672038)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bio-integrity.c (ffffffff816b4f67)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff816b6b37)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172d76c)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bio-integrity.c (ffffffff81774a3f)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81776af7)
Location: include/linux/bvec.h:194
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81769b23)
Location: include/linux/bvec.h:233
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bio-integrity.c (ffffffff817b4765)
Location: include/linux/bvec.h:233
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff817b66cb)
Location: include/linux/bvec.h:233
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817abcd3)
Location: include/linux/bvec.h:233
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bio-integrity.c (ffffffff817f85a5)
Location: include/linux/bvec.h:233
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff817fb0db)
Location: include/linux/bvec.h:233
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
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
