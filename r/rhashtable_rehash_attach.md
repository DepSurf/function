# Function: <code>rhashtable_rehash_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff81400530)
Location: lib/rhashtable.c:216
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81400530-ffffffff81400576: rhashtable_rehash_attach.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff814477f0)
Location: lib/rhashtable.c:220
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff814477f0-ffffffff81447836: rhashtable_rehash_attach.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff81466210)
Location: lib/rhashtable.c:220
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81466210-ffffffff81466256: rhashtable_rehash_attach.isra.12 (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff8146c2b3)
Location: lib/rhashtable.c:328
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
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
In lib/rhashtable.c (ffffffff814985b2)
Location: lib/rhashtable.c:328
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
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
In lib/rhashtable.c (ffffffff814cd795)
Location: lib/rhashtable.c:297
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
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
In lib/rhashtable.c (ffffffff814e1984)
Location: lib/rhashtable.c:292
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
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
In lib/rhashtable.c (ffffffff8150d99c)
Location: lib/rhashtable.c:286
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
In lib/rhashtable.c (ffffffff8152b7ec)
Location: lib/rhashtable.c:286
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
In lib/rhashtable.c (ffffffff8158e773)
Location: lib/rhashtable.c:295
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_shrink
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
In lib/rhashtable.c (ffffffff815ab2e3)
Location: lib/rhashtable.c:295
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff815b670b)
Location: lib/rhashtable.c:295
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff8161cc7c)
Location: lib/rhashtable.c:295
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff816ea4f8)
Location: lib/rhashtable.c:295
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff817da710)
Location: lib/rhashtable.c:298
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff8181995f)
Location: lib/rhashtable.c:298
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff8185ecaf)
Location: lib/rhashtable.c:298
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffff800010636e90)
Location: lib/rhashtable.c:286
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
In lib/rhashtable.c (c07dcc90)
Location: lib/rhashtable.c:286
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
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
In lib/rhashtable.c (c0000000007dce90)
Location: lib/rhashtable.c:286
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
In lib/rhashtable.c (ffffffe000464248)
Location: lib/rhashtable.c:286
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
In lib/rhashtable.c (ffffffff81523dcc)
Location: lib/rhashtable.c:286
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
In lib/rhashtable.c (ffffffff815140ac)
Location: lib/rhashtable.c:286
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
In lib/rhashtable.c (ffffffff8151fe5c)
Location: lib/rhashtable.c:286
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
In lib/rhashtable.c (ffffffff81539775)
Location: lib/rhashtable.c:286
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
</details>
</li>
</ul>

## Differences
