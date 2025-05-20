# Function: <code>rhashtable_rehash_one</code>

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
In lib/rhashtable.c (ffffffff8140084b)
Location: lib/rhashtable.c:158
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
In lib/rhashtable.c (ffffffff81447fcf)
Location: lib/rhashtable.c:162
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
In lib/rhashtable.c (ffffffff81466bef)
Location: lib/rhashtable.c:162
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
In lib/rhashtable.c (ffffffff8146baf5)
Location: lib/rhashtable.c:258
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
In lib/rhashtable.c (ffffffff81497de5)
Location: lib/rhashtable.c:258
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
In lib/rhashtable.c (ffffffff814cd337)
Location: lib/rhashtable.c:227
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
In lib/rhashtable.c (ffffffff814e1bb6)
Location: lib/rhashtable.c:223
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
In lib/rhashtable.c (ffffffff8150dabe)
Location: lib/rhashtable.c:215
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
In lib/rhashtable.c (ffffffff8152b90e)
Location: lib/rhashtable.c:215
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8158dfb0)
Location: lib/rhashtable.c:224
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_rehash_chain
```
**Symbols:**

```
ffffffff8158dfb0-ffffffff8158e0c2: rhashtable_rehash_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff815aab40)
Location: lib/rhashtable.c:224
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_rehash_chain
```
**Symbols:**

```
ffffffff815aab40-ffffffff815aac52: rhashtable_rehash_one.constprop.0 (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff815b5cd2)
Location: lib/rhashtable.c:224
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
In lib/rhashtable.c (ffffffff8161c172)
Location: lib/rhashtable.c:224
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
In lib/rhashtable.c (ffffffff816ea9fc)
Location: lib/rhashtable.c:224
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
In lib/rhashtable.c (ffffffff817dac89)
Location: lib/rhashtable.c:224
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
In lib/rhashtable.c (ffffffff81819efa)
Location: lib/rhashtable.c:224
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
In lib/rhashtable.c (ffffffff8185f24a)
Location: lib/rhashtable.c:224
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
In lib/rhashtable.c (ffff800010637000)
Location: lib/rhashtable.c:215
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
In lib/rhashtable.c (c07dce1c)
Location: lib/rhashtable.c:215
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
In lib/rhashtable.c (c0000000007dd050)
Location: lib/rhashtable.c:215
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
In lib/rhashtable.c (ffffffe0004644d6)
Location: lib/rhashtable.c:215
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
In lib/rhashtable.c (ffffffff81523eee)
Location: lib/rhashtable.c:215
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
In lib/rhashtable.c (ffffffff815141ce)
Location: lib/rhashtable.c:215
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
In lib/rhashtable.c (ffffffff8151ff7e)
Location: lib/rhashtable.c:215
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
In lib/rhashtable.c (ffffffff815398a5)
Location: lib/rhashtable.c:215
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
</details>
</li>
</ul>

## Differences
