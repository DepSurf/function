# Function: <code>atomic_try_cmpxchg_release</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8158f875)
Location: include/asm-generic/atomic-instrumented.h:714
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (ffffffff815ac3a5)
Location: include/asm-generic/atomic-instrumented.h:714
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (ffffffff815b7075)
Location: include/asm-generic/atomic-instrumented.h:714
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (ffffffff8161d685)
Location: include/linux/atomic/atomic-instrumented.h:517
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (ffffffff816eb175)
Location: include/linux/atomic/atomic-instrumented.h:547
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (ffffffff817db7f5)
Location: include/linux/atomic/atomic-instrumented.h:547
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (ffffffff8181aa65)
Location: include/linux/atomic/atomic-instrumented.h:1313
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (ffffffff8185fde5)
Location: include/linux/atomic/atomic-instrumented.h:1313
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/rcuref.c (ffffffff818600f1)
Location: include/linux/atomic/atomic-instrumented.h:1313
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
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
In lib/refcount.c (ffff800010637778)
Location: include/linux/atomic-fallback.h:941
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (c07dd428)
Location: include/linux/atomic-fallback.h:941
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (c0000000007dd790)
Location: include/linux/atomic-fallback.h:941
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
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
In lib/refcount.c (ffffffe0004649d2)
Location: include/linux/atomic-fallback.h:941
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
