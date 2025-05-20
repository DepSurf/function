# Function: <code>load_unaligned_zeropad</code>

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
In fs/namei.c (ffffffff8121802d)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - fs/namei.c:full_name_hash
  - fs/namei.c:link_path_walk
```
```
In fs/dcache.c (ffffffff81225415)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - fs/dcache.c:d_instantiate_unique
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_lookup
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
In fs/namei.c (ffffffff812406ec)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff8124d373)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
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
In fs/namei.c (ffffffff81252bcc)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff81260433)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
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
In fs/namei.c (ffffffff8125ed90)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff8126c416)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff818f6830)
Location: arch/x86/include/asm/word-at-a-time.h:79
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff812810f0)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff8128e7f6)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff8197d230)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff812a7def)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff812b5557)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff819d9787)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff812ba1ef)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff812ca807)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81a119a7)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff812d80df)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff812e728e)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81a80fd0)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff812e9c4f)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff812f8dfe)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81ab81d0)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff81321df1)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff81331dbb)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff815f2d27)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff8132d3b1)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff8133d7db)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff816173d7)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff81332ea4)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff8134411b)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff815faa64)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff81380634)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff81391c0b)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81668304)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_unaligned
  - lib/siphash.c:__siphash_unaligned
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
In fs/namei.c (ffffffff814004d4)
Location: arch/x86/include/asm/word-at-a-time.h:82
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff81412cff)
Location: arch/x86/include/asm/word-at-a-time.h:82
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81781b51)
Location: arch/x86/include/asm/word-at-a-time.h:82
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_unaligned
  - lib/siphash.c:__hsiphash_unaligned
  - lib/siphash.c:__siphash_unaligned
  - lib/siphash.c:__siphash_unaligned
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff8178e6e9)
Location: arch/x86/include/asm/word-at-a-time.h:82
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
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
In fs/namei.c (ffffffff8148990c)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff814a03f0)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff8203e19b)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_unaligned
  - lib/siphash.c:__siphash_unaligned
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff8204bfc5)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
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
In fs/namei.c (ffffffff814be83c)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff814d5710)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff820bc69b)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_unaligned
  - lib/siphash.c:__siphash_unaligned
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff820ca838)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
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
In fs/namei.c (ffffffff814f0cbc)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff81507b60)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff82196f9b)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_unaligned
  - lib/siphash.c:__siphash_unaligned
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff821a5191)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
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
In fs/namei.c (ffff800010391d1c)
Location: arch/arm64/include/asm/word-at-a-time.h:54
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffff8000103a7244)
Location: arch/arm64/include/asm/word-at-a-time.h:54
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffff800010d92150)
Location: arch/arm64/include/asm/word-at-a-time.h:54
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (c057843c)
Location: arch/arm/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (c0588950)
Location: arch/arm/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
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
In fs/namei.c (c000000000489c40)
Location: arch/powerpc/include/asm/word-at-a-time.h:167
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (c0000000004a07c8)
Location: arch/powerpc/include/asm/word-at-a-time.h:167
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (c000000000ed5c08)
Location: arch/powerpc/include/asm/word-at-a-time.h:167
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In fs/namei.c (ffffffff812e222f)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff812f13de)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81a57020)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff812d2e6f)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff812e200e)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81a14100)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff812e003f)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff812ef1ee)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81ac3410)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
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
In fs/namei.c (ffffffff812f189f)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
  - fs/namei.c:full_name_hash
```
```
In fs/dcache.c (ffffffff813000de)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup_rcu
```
```
In lib/siphash.c (ffffffff81acf8e0)
Location: arch/x86/include/asm/word-at-a-time.h:80
Inline: True
Inline callers:
  - lib/siphash.c:__hsiphash_aligned
  - lib/siphash.c:__siphash_aligned
```
</details>
</li>
</ul>

## Differences
