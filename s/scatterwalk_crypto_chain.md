# Function: <code>scatterwalk_crypto_chain</code>

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
In crypto/scatterwalk.c (ffffffff8139eb4a)
Location: include/crypto/scatterwalk.h:28
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/eseqiv.c (ffffffff813a262c)
Location: include/crypto/scatterwalk.h:28
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/eseqiv.c:eseqiv_givencrypt
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
In crypto/scatterwalk.c (ffffffff813db90d)
Location: include/crypto/scatterwalk.h:24
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
In crypto/scatterwalk.c (ffffffff813f324d)
Location: include/crypto/scatterwalk.h:24
Inline: True
```
```
In crypto/xts.c (ffffffff81401b15)
Location: include/crypto/scatterwalk.h:24
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/scatterwalk.c (ffffffff813ff56d)
Location: include/crypto/scatterwalk.h:24
Inline: True
```
```
In crypto/xts.c (ffffffff8140eedb)
Location: include/crypto/scatterwalk.h:24
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/scatterwalk.c (ffffffff81427b2d)
Location: include/crypto/scatterwalk.h:24
Inline: True
```
```
In crypto/xts.c (ffffffff814379ab)
Location: include/crypto/scatterwalk.h:24
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/scatterwalk.c (ffffffff8145a98d)
Location: include/crypto/scatterwalk.h:24
Inline: True
```
```
In crypto/xts.c (ffffffff8146a2d3)
Location: include/crypto/scatterwalk.h:24
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/scatterwalk.c (ffffffff814784fd)
Location: include/crypto/scatterwalk.h:24
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
In crypto/scatterwalk.c (ffffffff814a631b)
Location: include/crypto/scatterwalk.h:19
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
In crypto/scatterwalk.c (ffffffff814c0fab)
Location: include/crypto/scatterwalk.h:19
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
In crypto/scatterwalk.c (ffffffff8152185b)
Location: include/crypto/scatterwalk.h:19
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
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
In crypto/scatterwalk.c (ffffffff8153e6cb)
Location: include/crypto/scatterwalk.h:19
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
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
In crypto/scatterwalk.c (ffffffff81546d7b)
Location: include/crypto/scatterwalk.h:19
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
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
In crypto/scatterwalk.c (ffffffff815a755b)
Location: include/crypto/scatterwalk.h:19
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
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
In crypto/scatterwalk.c (ffffffff8164e65a)
Location: include/crypto/scatterwalk.h:20
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
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
In crypto/scatterwalk.c (ffffffff81707aaa)
Location: include/crypto/scatterwalk.h:20
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
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
In crypto/scatterwalk.c (ffffffff8174121a)
Location: include/crypto/scatterwalk.h:20
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
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
In crypto/scatterwalk.c (ffffffff817820ba)
Location: include/crypto/scatterwalk.h:20
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
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
In crypto/scatterwalk.c (ffff8000105baf90)
Location: include/crypto/scatterwalk.h:19
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
In crypto/scatterwalk.c (c07692c4)
Location: include/crypto/scatterwalk.h:19
Inline: True
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
In crypto/scatterwalk.c (c000000000741620)
Location: include/crypto/scatterwalk.h:19
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
In crypto/scatterwalk.c (ffffffe000400ce6)
Location: include/crypto/scatterwalk.h:19
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
In crypto/scatterwalk.c (ffffffff814b958b)
Location: include/crypto/scatterwalk.h:19
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
In crypto/scatterwalk.c (ffffffff814a9fab)
Location: include/crypto/scatterwalk.h:19
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
In crypto/scatterwalk.c (ffffffff814b561b)
Location: include/crypto/scatterwalk.h:19
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
In crypto/scatterwalk.c (ffffffff814ce0bb)
Location: include/crypto/scatterwalk.h:19
Inline: True
```
</details>
</li>
</ul>

## Differences
