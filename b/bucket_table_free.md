# Function: <code>bucket_table_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff813fff40)
Location: lib/rhashtable.c:98
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free_rcu
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff813fff40-ffffffff813fff61: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81447670)
Location: lib/rhashtable.c:102
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff81447670-ffffffff81447691: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81465ff0)
Location: lib/rhashtable.c:102
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff81465ff0-ffffffff81466011: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146b220)
Location: lib/rhashtable.c:138
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff8146b220-ffffffff8146b29a: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81497510)
Location: lib/rhashtable.c:138
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff81497510-ffffffff8149758a: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc3d0)
Location: lib/rhashtable.c:102
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff814cc3d0-ffffffff814cc449: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e0800)
Location: lib/rhashtable.c:102
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff814e0800-ffffffff814e0879: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150c820)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff8150c820-ffffffff8150c88d: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152a670)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff8152a670-ffffffff8152a6dd: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158e6c0)
Location: lib/rhashtable.c:109
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_shrink
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff8158e6c0-ffffffff8158e728: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815ab230)
Location: lib/rhashtable.c:109
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff815ab230-ffffffff815ab298: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b6290)
Location: lib/rhashtable.c:109
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff815b6290-ffffffff815b6348: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:109
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff8161c7b0-ffffffff8161c876: bucket_table_free (STB_LOCAL)
ffffffff81cdac3d-ffffffff81cdac83: bucket_table_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:109
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff816e9fc0-ffffffff816ea097: bucket_table_free (STB_LOCAL)
ffffffff81e9350e-ffffffff81e93554: bucket_table_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:109
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff817da1d0-ffffffff817da2a7: bucket_table_free (STB_LOCAL)
ffffffff8207867a-ffffffff820786c0: bucket_table_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:109
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff81819560-ffffffff81819637: bucket_table_free (STB_LOCAL)
ffffffff820f8bf6-ffffffff820f8c41: bucket_table_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:109
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff8185e8b0-ffffffff8185e987: bucket_table_free (STB_LOCAL)
ffffffff821d6717-ffffffff821d6762: bucket_table_free.cold (STB_LOCAL)
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
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010635af8)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffff800010635af8-ffff800010635b94: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dba00)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
c07dba00-c07dba70: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007db5a0)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
c0000000007db5a0-c0000000007db694: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe0004632b0)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffe0004632b0-ffffffe000463328: bucket_table_free (STB_LOCAL)
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
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81522c50)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff81522c50-ffffffff81522cbd: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81512f30)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff81512f30-ffffffff81512f9d: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151ece0)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff8151ece0-ffffffff8151ed4d: bucket_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81538680)
Location: lib/rhashtable.c:100
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:bucket_table_free_rcu
```
**Symbols:**

```
ffffffff81538680-ffffffff815386ed: bucket_table_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
