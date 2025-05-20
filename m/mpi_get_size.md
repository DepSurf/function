# Function: <code>mpi_get_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81416c62)
Location: include/linux/mpi.h:154
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_get_buffer
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
In crypto/rsa.c (ffffffff813e04c2)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff8145ebad)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
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
In crypto/rsa.c (ffffffff813f8a42)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff8147d67d)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
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
In crypto/dh.c (ffffffff81404f25)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff81405335)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff81486b8d)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
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
In crypto/dh.c (ffffffff8142d83d)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff8142dc2d)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff814c2d0d)
Location: include/linux/mpi.h:153
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
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
In crypto/dh.c (ffffffff814604b5)
Location: include/linux/mpi.h:92
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff814608a5)
Location: include/linux/mpi.h:92
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff814f3c59)
Location: include/linux/mpi.h:92
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff8147def5)
Location: include/linux/mpi.h:92
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff8147e4f5)
Location: include/linux/mpi.h:92
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff81507f89)
Location: include/linux/mpi.h:92
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff814ac215)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff814ac805)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff815360ed)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff814c6ec5)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff814c74b5)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff81556efd)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff81526175)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff815267a5)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff815e07ae)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff81543115)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff81543745)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff81601df3)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff8154b7b5)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff8154bdb5)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff815e4bac)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff815abf95)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff815ac595)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff81650ddc)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff816539c5)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff81654835)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff81767bdf)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff8170d915)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff8170e8c5)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff81896c8f)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff81748185)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff81749225)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff818d914f)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff81789ff5)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff8178b0c5)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/crypto/mpi/mpicoder.c (ffffffff8186fcaf)
Location: include/linux/mpi.h:274
Inline: True
Inline callers:
  - lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_get_buffer
  - lib/crypto/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffff8000105c25a0)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffff8000105c2c40)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffff800010663560)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (c076f9d0)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (c0770004)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (c080c250)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (c00000000074ada8)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (c00000000074b638)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (c000000000818004)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffe000406fda)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffe000407654)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffe00048f834)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff814bf4a5)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff814bfa95)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff8154f4dd)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff814afec5)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff814b04b5)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff8153f7bd)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff814bb535)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff814bbb25)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff8154b21d)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
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
In crypto/dh.c (ffffffff814d4005)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/dh.c:dh_max_size
```
```
In crypto/rsa.c (ffffffff814d45f5)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_max_size
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In lib/mpi/mpicoder.c (ffffffff8156506d)
Location: include/linux/mpi.h:79
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_get_buffer
  - lib/mpi/mpicoder.c:mpi_read_buffer
```
</details>
</li>
</ul>

## Differences
