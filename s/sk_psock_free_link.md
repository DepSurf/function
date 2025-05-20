# Function: <code>sk_psock_free_link</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e737d)
Location: include/linux/skmsg.h:313
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff818f27e5)
Location: include/linux/skmsg.h:313
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81976b0e)
Location: include/linux/skmsg.h:313
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (ffffffff81936d0b)
Location: include/linux/skmsg.h:313
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff819448a2)
Location: include/linux/skmsg.h:313
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e0671)
Location: include/linux/skmsg.h:313
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (ffffffff81969bdb)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff819798a2)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a176a1)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (ffffffff81a3d6b2)
Location: include/linux/skmsg.h:321
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff81a4ea95)
Location: include/linux/skmsg.h:321
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_del_link
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
In net/core/skmsg.c (ffffffff81a40292)
Location: include/linux/skmsg.h:323
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff81a54a75)
Location: include/linux/skmsg.h:323
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_del_link
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
In net/core/skmsg.c (ffffffff81a4d7ab)
Location: include/linux/skmsg.h:388
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81a50695)
Location: include/linux/skmsg.h:388
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
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
In net/core/skmsg.c (ffffffff81b05e6b)
Location: include/linux/skmsg.h:421
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81b09223)
Location: include/linux/skmsg.h:421
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
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
In net/core/skmsg.c (ffffffff81c8b87b)
Location: include/linux/skmsg.h:411
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81c8f2b4)
Location: include/linux/skmsg.h:411
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
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
In net/core/skmsg.c (ffffffff81e463db)
Location: include/linux/skmsg.h:413
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81e4a514)
Location: include/linux/skmsg.h:413
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
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
In net/core/skmsg.c (ffffffff81ea29e4)
Location: include/linux/skmsg.h:413
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81ea5c20)
Location: include/linux/skmsg.h:413
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
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
In net/core/skmsg.c (ffffffff81f65a84)
Location: include/linux/skmsg.h:419
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81f686e0)
Location: include/linux/skmsg.h:419
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
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
In net/core/skmsg.c (ffff800010c0fdf0)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffff800010c20d18)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd30dc)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (c0d27c00)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (c0d386ac)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (c0ddd47c)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (c000000000cfc064)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (c000000000d13190)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (c000000000df1d48)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (ffffffe00078c352)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffe000799d32)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824546)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (ffffffff81909bab)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff81919712)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b6d31)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (ffffffff818c39bb)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff818d34c2)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81973b21)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (ffffffff8195abdb)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff8196a8a2)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a217b1)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
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
In net/core/skmsg.c (ffffffff8197cdfb)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff8198cd12)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2cb01)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
</details>
</li>
</ul>

## Differences
