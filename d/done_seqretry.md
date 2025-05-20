# Function: <code>done_seqretry</code>

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
In fs/dcache.c (ffffffff81223076)
Location: include/linux/seqlock.h:536
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
In fs/dcache.c (ffffffff8124b645)
Location: include/linux/seqlock.h:539
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
In fs/dcache.c (ffffffff8125e625)
Location: include/linux/seqlock.h:539
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
In fs/dcache.c (ffffffff8126be9d)
Location: include/linux/seqlock.h:539
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
In fs/dcache.c (ffffffff8128f78d)
Location: include/linux/seqlock.h:540
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
In fs/dcache.c (ffffffff812b6425)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff812d3806)
Location: include/linux/seqlock.h:539
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
In fs/dcache.c (ffffffff812cb065)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff812e91b6)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (ffffffff812e804b)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81307a8c)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (ffffffff812f9bdb)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff8131ab0c)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (ffffffff81332573)
Location: include/linux/seqlock.h:582
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813546da)
Location: include/linux/seqlock.h:582
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff8133e74c)
Location: include/linux/seqlock.h:1169
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81360fa2)
Location: include/linux/seqlock.h:1169
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff81344b39)
Location: include/linux/seqlock.h:1169
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81367a81)
Location: include/linux/seqlock.h:1169
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff81392629)
Location: include/linux/seqlock.h:1169
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813b6971)
Location: include/linux/seqlock.h:1169
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff81412258)
Location: include/linux/seqlock.h:1165
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff8143bf74)
Location: include/linux/seqlock.h:1165
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff8149d048)
Location: include/linux/seqlock.h:1165
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff814ca5d4)
Location: include/linux/seqlock.h:1165
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff814d23cd)
Location: include/linux/seqlock.h:1166
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81500812)
Location: include/linux/seqlock.h:1166
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffffffff81504df3)
Location: include/linux/seqlock.h:1101
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81535432)
Location: include/linux/seqlock.h:1101
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/dcache.c (ffff8000103a7600)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffff8000103d1c88)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (c05881e0)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (c05aca20)
Location: include/linux/seqlock.h:539
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
In fs/dcache.c (c0000000004a2564)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (c0000000004d4a60)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (ffffffe00026e934)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffe00028d2cc)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (ffffffff812f21bb)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813130ec)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (ffffffff812e2deb)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81303cfc)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (ffffffff812effcb)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81310edc)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
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
In fs/dcache.c (ffffffff812ffb32)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813226e2)
Location: include/linux/seqlock.h:539
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
</details>
</li>
</ul>

## Differences
