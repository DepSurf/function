# Function: <code>raw_seqcount_begin</code>

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
In fs/dcache.c (ffffffff81225ce7)
Location: include/linux/seqlock.h:181
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff8171bed3)
Location: include/linux/seqlock.h:181
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff8124de37)
Location: include/linux/seqlock.h:181
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff8178476b)
Location: include/linux/seqlock.h:181
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff81260f17)
Location: include/linux/seqlock.h:181
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff817b1d5b)
Location: include/linux/seqlock.h:181
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff8126e71b)
Location: include/linux/seqlock.h:181
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff817cf3b1)
Location: include/linux/seqlock.h:181
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff8129103b)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff81848d21)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff812b770a)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff81892d75)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff812cc86a)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff818b37f5)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff812e9461)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff81900085)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff812fb001)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff819323a5)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff81333cf7)
Location: include/linux/seqlock.h:200
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
In fs/dcache.c (ffff8000103aa380)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffff800010bd0340)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (c058b318)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (c0ceae9c)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (c0000000004a527c)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (c000000000cae01c)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffe0002700e6)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffe00075ab72)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff812f35e1)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff818d23a5)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff812e4211)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff8188c235)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff812f13f1)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff819233a5)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
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
In fs/dcache.c (ffffffff813025b1)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In net/core/dev.c (ffffffff819447f3)
Location: include/linux/seqlock.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
</details>
</li>
</ul>

## Differences
