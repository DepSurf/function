# Function: <code>rhashtable_lookup_insert_fast</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff818a524c)
Location: include/linux/rhashtable.h:867
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff818cb53d)
Location: include/linux/rhashtable.h:911
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff819502dd)
Location: include/linux/rhashtable.h:913
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff819a9f9a)
Location: include/linux/rhashtable.h:925
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff819e0acf)
Location: include/linux/rhashtable.h:793
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff81a4f7bf)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff81a8644f)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff81b8133c)
Location: include/linux/rhashtable.h:896
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff81b90b7c)
Location: include/linux/rhashtable.h:896
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff81b7fd8c)
Location: include/linux/rhashtable.h:896
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/ioam6.c (ffffffff81c3a117)
Location: include/linux/rhashtable.h:896
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b62c)
Location: include/linux/rhashtable.h:896
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/ioam6.c (ffffffff81dd7e75)
Location: include/linux/rhashtable.h:896
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb01c)
Location: include/linux/rhashtable.h:896
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/ioam6.c (ffffffff81fa986c)
Location: include/linux/rhashtable.h:905
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbec0c)
Location: include/linux/rhashtable.h:905
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/ioam6.c (ffffffff8200a1ec)
Location: include/linux/rhashtable.h:905
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201ff8c)
Location: include/linux/rhashtable.h:905
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/handshake/request.c (ffffffff82093332)
Location: include/linux/rhashtable.h:905
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_submit
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
In net/ipv6/ioam6.c (ffffffff820d918d)
Location: include/linux/rhashtable.h:905
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ef0bc)
Location: include/linux/rhashtable.h:905
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/handshake/request.c (ffffffff82169be2)
Location: include/linux/rhashtable.h:905
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_submit
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
In net/ipv6/seg6_hmac.c (ffff800010d52344)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (c0e5318c)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (c000000000e8a4fc)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffe000889de8)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff81a25adf)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff819e289f)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff81a9055f)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In net/ipv6/seg6_hmac.c (ffffffff81a9d68f)
Location: include/linux/rhashtable.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
