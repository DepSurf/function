# Function: <code>psock_set_prog</code>

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
In net/core/skmsg.c (ffffffff818e730e)
Location: include/linux/skmsg.h:428
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff818f32e7)
Location: include/linux/skmsg.h:428
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (ffffffff81936c9b)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff819457b7)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (ffffffff81969b6b)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff8197a7d7)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (ffffffff81a3d63f)
Location: include/linux/skmsg.h:425
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff81a4fbe4)
Location: include/linux/skmsg.h:425
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
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
In net/core/skmsg.c (ffffffff81a4021f)
Location: include/linux/skmsg.h:410
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff81a55bf4)
Location: include/linux/skmsg.h:410
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
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
In net/core/skmsg.c (ffffffff81a4d723)
Location: include/linux/skmsg.h:457
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81a4f3eb)
Location: include/linux/skmsg.h:457
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
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
In net/core/skmsg.c (ffffffff81b07ab6)
Location: include/linux/skmsg.h:472
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81b07fcb)
Location: include/linux/skmsg.h:472
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
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
In net/core/skmsg.c (ffffffff81c8d866)
Location: include/linux/skmsg.h:462
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81c8eb7d)
Location: include/linux/skmsg.h:462
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In net/core/skmsg.c (ffffffff81e486e6)
Location: include/linux/skmsg.h:464
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81e49ced)
Location: include/linux/skmsg.h:464
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In net/core/skmsg.c (ffffffff81ea3d76)
Location: include/linux/skmsg.h:464
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81ea440d)
Location: include/linux/skmsg.h:464
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In net/core/skmsg.c (ffffffff81f66676)
Location: include/linux/skmsg.h:470
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81f67bfd)
Location: include/linux/skmsg.h:470
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In net/core/skmsg.c (ffff800010c0fd58)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffff800010c21b14)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (c0d27b50)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (c0d39140)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
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
In net/core/skmsg.c (c000000000cfbf9c)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (c000000000d140f4)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (ffffffe00078c2ec)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffe00079a93e)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (ffffffff81909b3b)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff8191a647)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (ffffffff818c394b)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff818d43f7)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (ffffffff8195ab6b)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff8196b7d7)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
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
In net/core/skmsg.c (ffffffff8197cd8b)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffffffff8198dc47)
Location: include/linux/skmsg.h:444
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
</details>
</li>
</ul>

## Differences
