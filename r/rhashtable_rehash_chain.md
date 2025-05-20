# Function: <code>rhashtable_rehash_chain</code>

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
In lib/rhashtable.c (ffffffff81400828)
Location: lib/rhashtable.c:201
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff81447fc8)
Location: lib/rhashtable.c:205
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff81466be8)
Location: lib/rhashtable.c:205
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff8146bac7)
Location: lib/rhashtable.c:306
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff81497db7)
Location: lib/rhashtable.c:306
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff814cd305)
Location: lib/rhashtable.c:275
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff814e1b82)
Location: lib/rhashtable.c:270
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff8150da80)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff8152b8d0)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rhashtable_rehash_chain(struct rhashtable *ht, unsigned int old_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158f050)
Location: lib/rhashtable.c:274
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8158f050-ffffffff8158f0da: rhashtable_rehash_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rhashtable_rehash_chain(struct rhashtable *ht, unsigned int old_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815abbc0)
Location: lib/rhashtable.c:274
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff815abbc0-ffffffff815abc4a: rhashtable_rehash_chain (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff815b5c94)
Location: lib/rhashtable.c:274
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff8161c134)
Location: lib/rhashtable.c:274
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff816ea9b3)
Location: lib/rhashtable.c:274
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff817dac31)
Location: lib/rhashtable.c:276
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff81819ea1)
Location: lib/rhashtable.c:276
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff8185f1f1)
Location: lib/rhashtable.c:276
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffff800010636fb0)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (c07dcda0)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (c0000000007dcfe8)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffe0004644d0)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff81523eb0)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff81514190)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff8151ff40)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
In lib/rhashtable.c (ffffffff81539860)
Location: lib/rhashtable.c:265
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
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
</ul>
