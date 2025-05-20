# Function: <code>crypto_alloc_comp</code>

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
In mm/zswap.c (ffffffff811d7cbb)
Location: include/linux/crypto.h:1819
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
In mm/zswap.c (ffffffff811f5dbb)
Location: include/linux/crypto.h:1549
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
In mm/zswap.c (ffffffff8120696a)
Location: include/linux/crypto.h:1552
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
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
In mm/zswap.c (ffffffff8121208b)
Location: include/linux/crypto.h:1552
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
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
In mm/zswap.c (ffffffff8122ca5b)
Location: include/linux/crypto.h:1600
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
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
In mm/zswap.c (ffffffff8124f6db)
Location: include/linux/crypto.h:1613
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff813d4707)
Location: include/linux/crypto.h:1613
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
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
In mm/zswap.c (ffffffff81263dcb)
Location: include/linux/crypto.h:1798
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff813eebea)
Location: include/linux/crypto.h:1798
Inline: True
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
In mm/zswap.c (ffffffff8127ed5f)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff8141ae7f)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (ffffffff8128e79b)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff81434ccf)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (ffffffff812c1090)
Location: include/linux/crypto.h:877
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff81484acb)
Location: include/linux/crypto.h:877
Inline: True
Inline callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
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
In fs/pstore/platform.c (ffffffff814a20fb)
Location: include/linux/crypto.h:913
Inline: True
Inline callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
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
In fs/pstore/platform.c (ffffffff814a819b)
Location: include/linux/crypto.h:750
Inline: True
Inline callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
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
In fs/pstore/platform.c (ffffffff815004bb)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
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
In fs/pstore/platform.c (ffffffff815918de)
Location: include/linux/crypto.h:733
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
In fs/pstore/platform.c (ffffffff81638f55)
Location: include/linux/crypto.h:728
Inline: True
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
In fs/pstore/platform.c (ffffffff81671395)
Location: include/linux/crypto.h:501
Inline: True
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
In mm/zswap.c (ffff80001032aff0)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffff80001051ac28)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (c05417a8)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (c06d5060)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (c000000000401ff4)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (c000000000664854)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (ffffffe00022a0d2)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffe000383c7a)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (ffffffff81286d7b)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff8142d2af)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (ffffffff81278bdb)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff8141dd2f)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (ffffffff81284b8b)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff8142944f)
Location: include/linux/crypto.h:1795
Inline: True
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
In mm/zswap.c (ffffffff8129482b)
Location: include/linux/crypto.h:1795
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In fs/pstore/platform.c (ffffffff8144030f)
Location: include/linux/crypto.h:1795
Inline: True
```
</details>
</li>
</ul>

## Differences
