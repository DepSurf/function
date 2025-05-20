# Function: <code>rhashtable_try_insert</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81466851)
Location: lib/rhashtable.c:521
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff8146c0a1)
Location: lib/rhashtable.c:615
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff814983a1)
Location: lib/rhashtable.c:617
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff814cd5a3)
Location: lib/rhashtable.c:587
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff814e17a3)
Location: lib/rhashtable.c:579
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
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
In lib/rhashtable.c (ffffffff8150d5e2)
Location: lib/rhashtable.c:580
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
In lib/rhashtable.c (ffffffff8152b432)
Location: lib/rhashtable.c:580
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *rhashtable_try_insert(struct rhashtable *ht, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158e990)
Location: lib/rhashtable.c:587
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff8158e990-ffffffff8158ed54: rhashtable_try_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *rhashtable_try_insert(struct rhashtable *ht, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815ab4f0)
Location: lib/rhashtable.c:587
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff815ab4f0-ffffffff815ab8b4: rhashtable_try_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *rhashtable_try_insert(struct rhashtable *ht, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b6350)
Location: lib/rhashtable.c:587
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff815b6350-ffffffff815b67b6: rhashtable_try_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *rhashtable_try_insert(struct rhashtable *ht, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:587
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff8161c880-ffffffff8161cd2c: rhashtable_try_insert (STB_LOCAL)
ffffffff81cdac83-ffffffff81cdacc5: rhashtable_try_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *rhashtable_try_insert(struct rhashtable *ht, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:587
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff816ea0a0-ffffffff816ea58b: rhashtable_try_insert (STB_LOCAL)
ffffffff81e93554-ffffffff81e93586: rhashtable_try_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *rhashtable_try_insert(struct rhashtable *ht, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:590
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff817da2c0-ffffffff817da7a6: rhashtable_try_insert (STB_LOCAL)
ffffffff820786c0-ffffffff82078708: rhashtable_try_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *rhashtable_try_insert(struct rhashtable *ht, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:590
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff81819650-ffffffff818199fb: rhashtable_try_insert (STB_LOCAL)
ffffffff820f8c41-ffffffff820f8c5c: rhashtable_try_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *rhashtable_try_insert(struct rhashtable *ht, const void *key, struct rhash_head *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:590
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff8185e9a0-ffffffff8185ed4b: rhashtable_try_insert (STB_LOCAL)
ffffffff821d6762-ffffffff821d677d: rhashtable_try_insert.cold (STB_LOCAL)
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
In lib/rhashtable.c (ffff800010636af8)
Location: lib/rhashtable.c:580
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
In lib/rhashtable.c (c07dc840)
Location: lib/rhashtable.c:580
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
In lib/rhashtable.c (c0000000007dc9c4)
Location: lib/rhashtable.c:580
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
Location: lib/rhashtable.c:580
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
In lib/rhashtable.c (ffffffff81523a12)
Location: lib/rhashtable.c:580
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
In lib/rhashtable.c (ffffffff81513cf2)
Location: lib/rhashtable.c:580
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
In lib/rhashtable.c (ffffffff8151faa2)
Location: lib/rhashtable.c:580
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
In lib/rhashtable.c (ffffffff81539387)
Location: lib/rhashtable.c:580
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
