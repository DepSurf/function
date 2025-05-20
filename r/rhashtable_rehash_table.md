# Function: <code>rhashtable_rehash_table</code>

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
In lib/rhashtable.c (ffffffff81400802)
Location: lib/rhashtable.c:242
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
In lib/rhashtable.c (ffffffff81447fa2)
Location: lib/rhashtable.c:243
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
In lib/rhashtable.c (ffffffff81466bc2)
Location: lib/rhashtable.c:243
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
In lib/rhashtable.c (ffffffff8146b9f6)
Location: lib/rhashtable.c:351
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
In lib/rhashtable.c (ffffffff81497ce6)
Location: lib/rhashtable.c:351
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
In lib/rhashtable.c (ffffffff814cd2e6)
Location: lib/rhashtable.c:320
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
In lib/rhashtable.c (ffffffff814e1b5d)
Location: lib/rhashtable.c:308
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150da40)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8150da40-ffffffff8150dcbe: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152b890)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8152b890-ffffffff8152bb0e: rhashtable_rehash_table (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff8158f27b)
Location: lib/rhashtable.c:312
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff815abe38)
Location: lib/rhashtable.c:312
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b5c50)
Location: lib/rhashtable.c:312
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff815b5c50-ffffffff815b5eae: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8161c0f0)
Location: lib/rhashtable.c:312
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8161c0f0-ffffffff8161c34e: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff816ea970)
Location: lib/rhashtable.c:312
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff816ea970-ffffffff816eaca5: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff817dabf0)
Location: lib/rhashtable.c:315
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff817dabf0-ffffffff817daf52: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81819e60)
Location: lib/rhashtable.c:315
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81819e60-ffffffff8181a1cd: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8185f1b0)
Location: lib/rhashtable.c:315
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8185f1b0-ffffffff8185f51d: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010636f48)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffff800010636f48-ffff800010637294: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dcd40)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
c07dcd40-c07dd0c4: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007dcf70)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
c0000000007dcf70-c0000000007dd3ac: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe000464496)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffe000464496-ffffffe0004646fc: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81523e70)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81523e70-ffffffff815240ee: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81514150)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81514150-ffffffff815143ce: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151ff00)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8151ff00-ffffffff8152017e: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rhashtable_rehash_table(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81539820)
Location: lib/rhashtable.c:303
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81539820-ffffffff81539af5: rhashtable_rehash_table (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
