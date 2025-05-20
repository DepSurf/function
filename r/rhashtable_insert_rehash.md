# Function: <code>rhashtable_insert_rehash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rhashtable_insert_rehash(struct rhashtable *ht, struct bucket_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81400580)
Location: lib/rhashtable.c:392
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81400580-ffffffff81400653: rhashtable_insert_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rhashtable_insert_rehash(struct rhashtable *ht, struct bucket_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81447a30)
Location: lib/rhashtable.c:395
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81447a30-ffffffff81447b0e: rhashtable_insert_rehash (STB_GLOBAL)
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
In lib/rhashtable.c (ffffffff81466851)
Location: lib/rhashtable.c:381
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
Location: lib/rhashtable.c:470
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
Location: lib/rhashtable.c:470
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
In lib/rhashtable.c (ffffffff814cd756)
Location: lib/rhashtable.c:440
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
In lib/rhashtable.c (ffffffff814e1949)
Location: lib/rhashtable.c:432
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
In lib/rhashtable.c (ffffffff8150d962)
Location: lib/rhashtable.c:430
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
In lib/rhashtable.c (ffffffff8152b7b2)
Location: lib/rhashtable.c:430
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
int rhashtable_insert_rehash(struct rhashtable *ht, struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158e730)
Location: lib/rhashtable.c:439
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
**Symbols:**

```
ffffffff8158e730-ffffffff8158e7e9: rhashtable_insert_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rhashtable_insert_rehash(struct rhashtable *ht, struct bucket_table *tbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815ab2a0)
Location: lib/rhashtable.c:439
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
**Symbols:**

```
ffffffff815ab2a0-ffffffff815ab359: rhashtable_insert_rehash (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff815b66ce)
Location: lib/rhashtable.c:439
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
In lib/rhashtable.c (ffffffff8161cc3f)
Location: lib/rhashtable.c:439
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
In lib/rhashtable.c (ffffffff816ea4bf)
Location: lib/rhashtable.c:439
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
In lib/rhashtable.c (ffffffff817da6d7)
Location: lib/rhashtable.c:442
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
In lib/rhashtable.c (ffffffff8181991b)
Location: lib/rhashtable.c:442
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
In lib/rhashtable.c (ffffffff8185ec6b)
Location: lib/rhashtable.c:442
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
In lib/rhashtable.c (ffff800010636e4c)
Location: lib/rhashtable.c:430
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
In lib/rhashtable.c (c07dcc3c)
Location: lib/rhashtable.c:430
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
In lib/rhashtable.c (c0000000007dce50)
Location: lib/rhashtable.c:430
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
In lib/rhashtable.c (ffffffe00046420a)
Location: lib/rhashtable.c:430
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
In lib/rhashtable.c (ffffffff81523d92)
Location: lib/rhashtable.c:430
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
In lib/rhashtable.c (ffffffff81514072)
Location: lib/rhashtable.c:430
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
In lib/rhashtable.c (ffffffff8151fe22)
Location: lib/rhashtable.c:430
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
In lib/rhashtable.c (ffffffff8153973b)
Location: lib/rhashtable.c:430
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
