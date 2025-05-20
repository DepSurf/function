# Function: <code>bip_get_seed</code>

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
In block/bio-integrity.c (0)
Location: include/linux/bio.h:394
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: include/linux/bio.h:394
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (0)
Location: include/linux/bio.h:343
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: include/linux/bio.h:343
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (0)
Location: include/linux/bio.h:340
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: include/linux/bio.h:340
Inline: True
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
In drivers/scsi/sd_dif.c (0)
Location: include/linux/bio.h:354
Inline: True
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
In drivers/scsi/sd_dif.c (0)
Location: include/linux/bio.h:350
Inline: True
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
In drivers/scsi/sd_dif.c (0)
Location: include/linux/bio.h:382
Inline: True
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
In block/t10-pi.c (0)
Location: include/linux/bio.h:338
Inline: True
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
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
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
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
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
In block/t10-pi.c (ffffffff81577ebe)
Location: include/linux/bio.h:353
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
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
In block/t10-pi.c (ffffffff81594b3f)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
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
In block/t10-pi.c (ffffffff8159b906)
Location: include/linux/bio.h:365
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff816038a6)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
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
In block/t10-pi.c (ffffffff816b6ac1)
Location: include/linux/bio.h:362
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff81776a81)
Location: include/linux/bio.h:362
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff817b665c)
Location: include/linux/bio.h:364
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
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff817fb06c)
Location: include/linux/bio.h:374
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
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
In block/t10-pi.c (c07c65c0)
Location: include/linux/bio.h:345
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
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
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
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
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
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
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
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
In block/t10-pi.c (0)
Location: include/linux/bio.h:345
Inline: True
```
</details>
</li>
</ul>

## Differences
