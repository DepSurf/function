# Function: <code>skcipher_crypto_instance</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813de6cc)
Location: include/crypto/internal/skcipher.h:39
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:39
Inline: True
```
```
In crypto/ctr.c (ffffffff813e8ebf)
Location: include/crypto/internal/skcipher.h:39
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff813f60fc)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:75
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:75
Inline: True
```
```
In crypto/xts.c (ffffffff8140162e)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814024d0)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff81402519)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:75
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:75
Inline: True
```
```
In crypto/xts.c (ffffffff8140e9e9)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8140f5f7)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff8142ab89)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:75
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:75
Inline: True
```
```
In crypto/xts.c (ffffffff814374b9)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814380f7)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff8145d8e6)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (ffffffff814689d8)
Location: include/crypto/internal/skcipher.h:75
Inline: True
```
```
In crypto/cts.c (ffffffff814692a7)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81469dd7)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8146aa8e)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff8147b186)
Location: include/crypto/internal/skcipher.h:73
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (ffffffff81486654)
Location: include/crypto/internal/skcipher.h:73
Inline: True
```
```
In crypto/cts.c (ffffffff81486c72)
Location: include/crypto/internal/skcipher.h:73
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81487ac7)
Location: include/crypto/internal/skcipher.h:73
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8148830f)
Location: include/crypto/internal/skcipher.h:73
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a9304)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffffffff814b4d88)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b57d0)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b5d58)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c3f74)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffffffff814cd858)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814ce9d0)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814cef58)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81523048)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:68
Inline: True
```
```
In crypto/cts.c (ffffffff8152cc82)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8152dcc8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8152e254)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff8153ffa5)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:68
Inline: True
```
```
In crypto/cts.c (ffffffff81549d0e)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8154ac88)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8154b23c)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff81548565)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:69
Inline: True
```
```
In crypto/cts.c (ffffffff8155234e)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff815532b2)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81553862)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff815a8d45)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:69
Inline: True
```
```
In crypto/cts.c (ffffffff815b334e)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff815b42e2)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff815b4892)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff8165021a)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:69
Inline: True
```
```
In crypto/cts.c (ffffffff8165c356)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8165d174)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8165d786)
Location: include/crypto/internal/skcipher.h:69
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff8170998a)
Location: include/crypto/internal/skcipher.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:77
Inline: True
```
```
In crypto/cts.c (ffffffff81715d36)
Location: include/crypto/internal/skcipher.h:77
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81716c64)
Location: include/crypto/internal/skcipher.h:77
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81717306)
Location: include/crypto/internal/skcipher.h:77
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff8174325a)
Location: include/crypto/internal/skcipher.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:77
Inline: True
```
```
In crypto/cts.c (ffffffff817515e6)
Location: include/crypto/internal/skcipher.h:77
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81752515)
Location: include/crypto/internal/skcipher.h:77
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81752c16)
Location: include/crypto/internal/skcipher.h:77
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffffffff8178554c)
Location: include/crypto/internal/skcipher.h:92
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffffffff81793468)
Location: include/crypto/internal/skcipher.h:92
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff817944ee)
Location: include/crypto/internal/skcipher.h:92
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81794bb8)
Location: include/crypto/internal/skcipher.h:92
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105bea84)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffff8000105c9734)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffff8000105ca64c)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffff8000105cadc0)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076c6c8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (c07772c4)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0778260)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c0778980)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000746dd8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (c000000000753e34)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0000000007555d8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c000000000755dc8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe000403f00)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffffffe00040e420)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffe00040edc8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffe00040f4f8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bc554)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffffffff814c5e38)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c6fb0)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c7538)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814acf74)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffffffff814b6858)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b79d0)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b7f58)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b85e4)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffffffff814c1ec8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c3040)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c35c8)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d10c4)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_register_instance
```
```
In crypto/cts.c (ffffffff814da998)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814dbb10)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814dc098)
Location: include/crypto/internal/skcipher.h:68
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
</ul>

## Differences
