# Function: <code>crypto_attr_alg</code>

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
In crypto/ecb.c (ffffffff813a90c4)
Location: include/crypto/algapi.h:170
Inline: True
```
```
In crypto/cbc.c (ffffffff813a9674)
Location: include/crypto/algapi.h:170
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
In crypto/ecb.c (ffffffff813e7098)
Location: include/crypto/algapi.h:240
Inline: True
```
```
In crypto/cbc.c (ffffffff813e7638)
Location: include/crypto/algapi.h:240
Inline: True
```
```
In crypto/xts.c (ffffffff813e86e8)
Location: include/crypto/algapi.h:240
Inline: True
```
```
In crypto/ctr.c (ffffffff813e8d28)
Location: include/crypto/algapi.h:240
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
In crypto/ecb.c (ffffffff813ffe48)
Location: include/crypto/algapi.h:170
Inline: True
```
```
In crypto/cbc.c (ffffffff8140006e)
Location: include/crypto/algapi.h:170
Inline: True
```
```
In crypto/ctr.c (ffffffff81402338)
Location: include/crypto/algapi.h:170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff8140d158)
Location: include/crypto/algapi.h:170
Inline: True
```
```
In crypto/cbc.c (ffffffff8140d390)
Location: include/crypto/algapi.h:170
Inline: True
```
```
In crypto/ctr.c (ffffffff8140f46d)
Location: include/crypto/algapi.h:170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff81435bc8)
Location: include/crypto/algapi.h:170
Inline: True
```
```
In crypto/cbc.c (ffffffff81435e00)
Location: include/crypto/algapi.h:170
Inline: True
```
```
In crypto/ctr.c (ffffffff81437f6d)
Location: include/crypto/algapi.h:170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff81468738)
Location: include/crypto/algapi.h:177
Inline: True
```
```
In crypto/cbc.c (ffffffff81468994)
Location: include/crypto/algapi.h:177
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a8db)
Location: include/crypto/algapi.h:177
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff814863a8)
Location: include/crypto/algapi.h:179
Inline: True
```
```
In crypto/cbc.c (ffffffff8148661b)
Location: include/crypto/algapi.h:179
Inline: True
```
```
In crypto/ctr.c (ffffffff8148816b)
Location: include/crypto/algapi.h:179
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
In crypto/skcipher.c (ffffffff814a92b3)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (ffffffff814c3f23)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
</details>
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
In crypto/skcipher.c (ffff8000105bea3c)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (c076c680)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (c000000000746d80)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (ffffffe000403ebe)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (ffffffff814bc503)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (ffffffff814acf23)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (ffffffff814b8593)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (ffffffff814d1073)
Location: include/crypto/algapi.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
</details>
</li>
</ul>

## Differences
