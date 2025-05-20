# Function: <code>read_word_at_a_time</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5554)
Location: include/linux/compiler.h:267
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff819d9b85)
Location: include/linux/compiler.h:267
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff812ca804)
Location: include/linux/compiler.h:272
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81a11da5)
Location: include/linux/compiler.h:272
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff812e728b)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81a812fb)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff812f8dfb)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81ab8948)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff81331db8)
Location: include/linux/compiler.h:328
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff815f35ae)
Location: include/linux/compiler.h:328
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff8133d7d8)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81617c3e)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff81344118)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff815fb28e)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff81391c08)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81668b5e)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff81412cfc)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81782540)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff814a03ed)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff8203f3d0)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff814d570d)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff820bd843)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff81507b5d)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff821980c3)
Location: include/asm-generic/rwonce.h:83
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffff8000103a7238)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffff800010d92d40)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (c058894c)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (c0e8f640)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (c0000000004a07c8)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (c000000000ed6dc0)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In lib/string.c (ffffffe0008bd0da)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff812f13db)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81a57798)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff812e200b)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81a14878)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff812ef1eb)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81ac3b88)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/dcache.c (ffffffff813000db)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/string.c (ffffffff81ad0058)
Location: include/linux/compiler.h:278
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
</ul>

## Differences
