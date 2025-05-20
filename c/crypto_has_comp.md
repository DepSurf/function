# Function: <code>crypto_has_comp</code>

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
In mm/zswap.c (ffffffff81f8b7dd)
Location: include/linux/crypto.h:1839
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
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
In mm/zswap.c (ffffffff81fb54a1)
Location: include/linux/crypto.h:1569
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
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
In mm/zswap.c (ffffffff81ff1e8d)
Location: include/linux/crypto.h:1572
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
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
In mm/zswap.c (ffffffff820d446f)
Location: include/linux/crypto.h:1572
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
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
In mm/zswap.c (ffffffff826dd035)
Location: include/linux/crypto.h:1620
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
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
In mm/zswap.c (ffffffff82707574)
Location: include/linux/crypto.h:1633
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffff813d46a9)
Location: include/linux/crypto.h:1633
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
In mm/zswap.c (ffffffff828be946)
Location: include/linux/crypto.h:1818
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffff813eeb86)
Location: include/linux/crypto.h:1818
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
In mm/zswap.c (ffffffff828d7b05)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffff8141af06)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (ffffffff828dff76)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffff81434d56)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (ffffffff812c1b30)
Location: include/linux/crypto.h:897
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_create_fallback
  - mm/zswap.c:__zswap_pool_create_fallback
```
```
In fs/pstore/platform.c (ffffffff81484a66)
Location: include/linux/crypto.h:897
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
In fs/pstore/platform.c (ffffffff814a2096)
Location: include/linux/crypto.h:933
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
In fs/pstore/platform.c (ffffffff814a8136)
Location: include/linux/crypto.h:770
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
In fs/pstore/platform.c (ffffffff81500456)
Location: include/linux/crypto.h:744
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
In fs/pstore/platform.c (ffffffff81591982)
Location: include/linux/crypto.h:753
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
In fs/pstore/platform.c (ffffffff81639072)
Location: include/linux/crypto.h:748
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
In fs/pstore/platform.c (ffffffff816714b2)
Location: include/linux/crypto.h:521
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
In mm/zswap.c (ffff800011459194)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffff80001051abd4)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (c15330d0)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (c06d5018)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (c000000001382bac)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (c0000000006649bc)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (ffffffe00001771c)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffe000383c44)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (ffffffff828c8e2a)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffff8142d336)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (ffffffff828c154f)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffff8141ddb6)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (ffffffff828dbbaa)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffff814294d6)
Location: include/linux/crypto.h:1815
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
In mm/zswap.c (ffffffff828e0fcb)
Location: include/linux/crypto.h:1815
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_param_set
```
```
In fs/pstore/platform.c (ffffffff81440396)
Location: include/linux/crypto.h:1815
Inline: True
```
</details>
</li>
</ul>

## Differences
