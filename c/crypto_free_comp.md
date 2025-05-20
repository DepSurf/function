# Function: <code>crypto_free_comp</code>

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
In mm/zswap.c (ffffffff811d7d9f)
Location: include/linux/crypto.h:1834
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
In mm/zswap.c (ffffffff811f5e9f)
Location: include/linux/crypto.h:1564
Inline: True
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
In mm/zswap.c (ffffffff81206912)
Location: include/linux/crypto.h:1567
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
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
In mm/zswap.c (ffffffff81212032)
Location: include/linux/crypto.h:1567
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
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
In mm/zswap.c (ffffffff8122ca02)
Location: include/linux/crypto.h:1615
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
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
In mm/zswap.c (ffffffff8124f682)
Location: include/linux/crypto.h:1628
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff813d453a)
Location: include/linux/crypto.h:1628
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffff81263d72)
Location: include/linux/crypto.h:1813
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff813eeb01)
Location: include/linux/crypto.h:1813
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffff8127ed02)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff8141add1)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffff8128e742)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff81434c21)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffff812c1032)
Location: include/linux/crypto.h:892
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff81484cb5)
Location: include/linux/crypto.h:892
Inline: True
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
In fs/pstore/platform.c (ffffffff814a22e5)
Location: include/linux/crypto.h:928
Inline: True
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
In fs/pstore/platform.c (ffffffff814a8385)
Location: include/linux/crypto.h:765
Inline: True
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
In fs/pstore/platform.c (ffffffff815006a5)
Location: include/linux/crypto.h:739
Inline: True
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
In fs/pstore/platform.c (ffffffff81591715)
Location: include/linux/crypto.h:748
Inline: True
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
In fs/pstore/platform.c (ffffffff83ecf09d)
Location: include/linux/crypto.h:743
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
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
In fs/pstore/platform.c (ffffffff836f412d)
Location: include/linux/crypto.h:516
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/zswap.c (ffff80001032af84)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffff80001051ab38)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (c0541750)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (c06d4f7c)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (c000000000401f60)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (c000000000664764)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffe00022a074)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffe000383b2a)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffff81286d22)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff8142d201)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffff81278b82)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff8141dc81)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffff81284b32)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff814293a1)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
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
In mm/zswap.c (ffffffff812947d2)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff81440261)
Location: include/linux/crypto.h:1810
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
```
</details>
</li>
</ul>

## Differences
