# Function: <code>atomic_cmpxchg_release</code>

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
In kernel/locking/osq_lock.c (ffffffff8110f732)
Location: include/asm-generic/atomic-instrumented.h:672
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
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
In kernel/locking/osq_lock.c (ffffffff8110c8f2)
Location: include/asm-generic/atomic-instrumented.h:672
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
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
In kernel/locking/osq_lock.c (ffffffff8110e722)
Location: include/asm-generic/atomic-instrumented.h:672
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
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
In kernel/locking/osq_lock.c (ffffffff8112deb2)
Location: include/linux/atomic/atomic-instrumented.h:487
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
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
In kernel/locking/osq_lock.c (ffffffff8114eed2)
Location: include/linux/atomic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
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
In kernel/locking/osq_lock.c (ffffffff8117e122)
Location: include/linux/atomic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
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
In kernel/locking/osq_lock.c (ffffffff8118edc2)
Location: include/linux/atomic/atomic-instrumented.h:1230
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
```
```
In lib/rcuref.c (ffffffff8181ad71)
Location: include/linux/atomic/atomic-instrumented.h:1230
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
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
In kernel/locking/osq_lock.c (ffffffff8119d772)
Location: include/linux/atomic/atomic-instrumented.h:1230
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
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
In kernel/locking/osq_lock.c (ffff80001016a760)
Location: include/asm-generic/atomic-instrumented.h:671
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
```
```
In lib/refcount.c (ffff800010637778)
Location: include/asm-generic/atomic-instrumented.h:671
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
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
In kernel/locking/mutex.c (c0e9b5f8)
Location: include/linux/atomic-fallback.h:883
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/locking/osq_lock.c (c03b6784)
Location: include/linux/atomic-fallback.h:883
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
```
```
In lib/refcount.c (c07dd428)
Location: include/linux/atomic-fallback.h:883
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
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
In kernel/locking/osq_lock.c (c0000000001c246c)
Location: include/linux/atomic-fallback.h:883
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
```
```
In lib/refcount.c (c0000000007dd790)
Location: include/linux/atomic-fallback.h:883
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
Location: arch/riscv/include/asm/atomic.h:301
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
