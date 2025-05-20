# Function: <code>sock_needs_netstamp</code>

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
In net/core/sock.c (ffffffff817009f4)
Location: net/core/sock.c:425
Inline: True
Inline callers:
  - net/core/sock.c:sock_disable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_enable_timestamp
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
In net/core/sock.c (ffffffff8176ad17)
Location: net/core/sock.c:386
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff81797dd7)
Location: net/core/sock.c:386
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff817b5987)
Location: net/core/sock.c:428
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff8182dedb)
Location: net/core/sock.c:418
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff818782cb)
Location: net/core/sock.c:424
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff81898a5b)
Location: net/core/sock.c:380
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff818e2ff7)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff819151d7)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff819e71eb)
Location: net/core/sock.c:426
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff819e6a2f)
Location: net/core/sock.c:416
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff819cc832)
Location: net/core/sock.c:416
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff81a7dc9a)
Location: net/core/sock.c:435
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
In net/core/sock.c (ffffffff81bee054)
Location: net/core/sock.c:454
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
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
In net/core/sock.c (ffffffff81d9cba7)
Location: net/core/sock.c:454
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
In net/core/sock.c (ffffffff81e0b3ff)
Location: net/core/sock.c:460
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
In net/core/sock.c (ffffffff81ec7def)
Location: net/core/sock.c:457
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
In net/core/sock.c (ffff800010bae158)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (c0ccbb30)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (c000000000c83b08)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffe00074008e)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff818b51d7)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff8186f127)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff819061d7)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
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
In net/core/sock.c (ffffffff81927207)
Location: net/core/sock.c:429
Inline: True
Inline callers:
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_disable_timestamp
```
</details>
</li>
</ul>

## Differences
