# Function: <code>rhashtable_insert_one</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bucket_table *rhashtable_insert_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, struct rhash_head *obj, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81466120)
Location: lib/rhashtable.c:474
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff81466120-ffffffff8146620b: rhashtable_insert_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bucket_table *rhashtable_insert_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, struct rhash_head *obj, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146b630)
Location: lib/rhashtable.c:563
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff8146b630-ffffffff8146b748: rhashtable_insert_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bucket_table *rhashtable_insert_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, struct rhash_head *obj, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81497920)
Location: lib/rhashtable.c:565
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff81497920-ffffffff81497a38: rhashtable_insert_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bucket_table *rhashtable_insert_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, struct rhash_head *obj, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc860)
Location: lib/rhashtable.c:535
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff814cc860-ffffffff814cc993: rhashtable_insert_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bucket_table *rhashtable_insert_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, struct rhash_head *obj, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e0e50)
Location: lib/rhashtable.c:527
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff814e0e50-ffffffff814e0f83: rhashtable_insert_one (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff8150d6a9)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff8152b4f9)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff8158ea81)
Location: lib/rhashtable.c:538
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
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
In lib/rhashtable.c (ffffffff815ab5e1)
Location: lib/rhashtable.c:538
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
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
In lib/rhashtable.c (ffffffff815b6444)
Location: lib/rhashtable.c:538
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
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
In lib/rhashtable.c (ffffffff8161c987)
Location: lib/rhashtable.c:538
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
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
In lib/rhashtable.c (ffffffff816ea17c)
Location: lib/rhashtable.c:538
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
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
In lib/rhashtable.c (ffffffff817da39a)
Location: lib/rhashtable.c:541
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
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
In lib/rhashtable.c (ffffffff818196aa)
Location: lib/rhashtable.c:541
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
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
In lib/rhashtable.c (ffffffff8185e9fa)
Location: lib/rhashtable.c:541
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
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
In lib/rhashtable.c (ffff800010636bd4)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (c07dc954)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (c0000000007dcae4)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffe0004640a2)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff81523ad9)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff81513db9)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff8151fb69)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff81539455)
Location: lib/rhashtable.c:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
