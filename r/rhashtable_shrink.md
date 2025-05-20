# Function: <code>rhashtable_shrink</code>

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
In lib/rhashtable.c (ffffffff81400960)
Location: lib/rhashtable.c:324
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
In lib/rhashtable.c (ffffffff81447fc1)
Location: lib/rhashtable.c:325
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
In lib/rhashtable.c (ffffffff81466be1)
Location: lib/rhashtable.c:325
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
In lib/rhashtable.c (ffffffff8146ba36)
Location: lib/rhashtable.c:422
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
In lib/rhashtable.c (ffffffff81497d26)
Location: lib/rhashtable.c:422
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
In lib/rhashtable.c (ffffffff814cd27b)
Location: lib/rhashtable.c:392
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
In lib/rhashtable.c (ffffffff814e1af1)
Location: lib/rhashtable.c:380
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
In lib/rhashtable.c (ffffffff8150dd80)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff8152bbd0)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rhashtable_shrink(struct rhashtable *ht);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158f160)
Location: lib/rhashtable.c:387
Inline: False
Direct callers:
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8158f160-ffffffff8158f1ec: rhashtable_shrink (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff815abee6)
Location: lib/rhashtable.c:387
Inline: True
Inline callers:
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
In lib/rhashtable.c (ffffffff815b6a7f)
Location: lib/rhashtable.c:387
Inline: True
Inline callers:
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
In lib/rhashtable.c (ffffffff8161cffc)
Location: lib/rhashtable.c:387
Inline: True
Inline callers:
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
In lib/rhashtable.c (ffffffff816eada2)
Location: lib/rhashtable.c:387
Inline: True
Inline callers:
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
In lib/rhashtable.c (ffffffff817db062)
Location: lib/rhashtable.c:390
Inline: True
Inline callers:
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
In lib/rhashtable.c (ffffffff8181a2d2)
Location: lib/rhashtable.c:390
Inline: True
Inline callers:
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
In lib/rhashtable.c (ffffffff8185f622)
Location: lib/rhashtable.c:390
Inline: True
Inline callers:
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
In lib/rhashtable.c (ffff800010637378)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (c07dd1a8)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (c0000000007dd4e0)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffe0004647b0)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff815241b0)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff81514490)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff81520240)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
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
In lib/rhashtable.c (ffffffff81539bc0)
Location: lib/rhashtable.c:378
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
