# Function: <code>rhashtable_lookup_one</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void *rhashtable_lookup_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81465ef0)
Location: lib/rhashtable.c:429
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff81465ef0-ffffffff81465fe6: rhashtable_lookup_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *rhashtable_lookup_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146b0a0)
Location: lib/rhashtable.c:518
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff8146b0a0-ffffffff8146b1cf: rhashtable_lookup_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *rhashtable_lookup_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81497380)
Location: lib/rhashtable.c:518
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff81497380-ffffffff814974b9: rhashtable_lookup_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *rhashtable_lookup_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc5a0)
Location: lib/rhashtable.c:488
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff814cc5a0-ffffffff814cc6c9: rhashtable_lookup_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *rhashtable_lookup_one(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e0910)
Location: lib/rhashtable.c:480
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff814e0910-ffffffff814e0a39: rhashtable_lookup_one (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff8150d612)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (ffffffff8152b462)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (ffffffff8158e9ee)
Location: lib/rhashtable.c:487
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
In lib/rhashtable.c (ffffffff815ab54e)
Location: lib/rhashtable.c:487
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
In lib/rhashtable.c (ffffffff815b63b0)
Location: lib/rhashtable.c:487
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
In lib/rhashtable.c (ffffffff8161c8e0)
Location: lib/rhashtable.c:487
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
In lib/rhashtable.c (ffffffff816ea0f2)
Location: lib/rhashtable.c:487
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
In lib/rhashtable.c (ffffffff817da314)
Location: lib/rhashtable.c:490
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:490
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
**Symbols:**

```
ffffffff81818900-ffffffff81818a9e: rhashtable_lookup_one.isra.0 (STB_LOCAL)
ffffffff820f8abd-ffffffff820f8ad2: rhashtable_lookup_one.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:490
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
**Symbols:**

```
ffffffff8185dc00-ffffffff8185dd9e: rhashtable_lookup_one.isra.0 (STB_LOCAL)
ffffffff821d65de-ffffffff821d65f3: rhashtable_lookup_one.isra.0.cold (STB_LOCAL)
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
In lib/rhashtable.c (ffff800010636b74)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (c07dc8b0)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (c0000000007dca60)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (ffffffe000464070)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (ffffffff81523a42)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (ffffffff81513d22)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (ffffffff8151fad2)
Location: lib/rhashtable.c:478
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
In lib/rhashtable.c (ffffffff815393be)
Location: lib/rhashtable.c:478
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
