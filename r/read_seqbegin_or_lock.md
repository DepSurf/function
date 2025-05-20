# Function: <code>read_seqbegin_or_lock</code>

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
In fs/dcache.c (ffffffff81222f11)
Location: include/linux/seqlock.h:523
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
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
In fs/dcache.c (ffffffff8124b567)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
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
In fs/dcache.c (ffffffff8125e547)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
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
In fs/dcache.c (ffffffff8126bdbe)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
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
In fs/dcache.c (ffffffff8128f6ae)
Location: include/linux/seqlock.h:527
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
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
In fs/dcache.c (ffffffff812b6274)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff812d3798)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff812caeb4)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff812e9148)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff812e7ec1)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813079e7)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff812f9a51)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff8131aa67)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff813323f1)
Location: include/linux/seqlock.h:569
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81354628)
Location: include/linux/seqlock.h:569
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (ffffffff8133e5c0)
Location: include/linux/seqlock.h:1141
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81360f38)
Location: include/linux/seqlock.h:1141
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (ffffffff813449b0)
Location: include/linux/seqlock.h:1141
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81367a17)
Location: include/linux/seqlock.h:1141
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (ffffffff813924a0)
Location: include/linux/seqlock.h:1141
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813b68ea)
Location: include/linux/seqlock.h:1141
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (ffffffff814120c5)
Location: include/linux/seqlock.h:1137
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff8143bef1)
Location: include/linux/seqlock.h:1137
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (ffffffff8149ceb5)
Location: include/linux/seqlock.h:1137
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff814ca551)
Location: include/linux/seqlock.h:1137
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (ffffffff814d22d5)
Location: include/linux/seqlock.h:1138
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81500791)
Location: include/linux/seqlock.h:1138
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (ffffffff81504d15)
Location: include/linux/seqlock.h:1073
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff815353b1)
Location: include/linux/seqlock.h:1073
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (ffff8000103a73b4)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffff8000103d1c04)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (c0588040)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (c05ac960)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/dcache.c (c0000000004a2354)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (c0000000004d4960)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffe00026e774)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffe00028d220)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff812f2031)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81313047)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff812e2c61)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81303c57)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff812efe41)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81310e37)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff812ff9a4)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff8132267f)
Location: include/linux/seqlock.h:526
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
</ul>

## Differences
