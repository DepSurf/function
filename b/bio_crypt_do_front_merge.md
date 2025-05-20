# Function: <code>bio_crypt_do_front_merge</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81545a5f)
Location: block/blk-crypto-internal.h:112
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_front_merge
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
In block/blk-merge.c (ffffffff81568f77)
Location: block/blk-crypto-internal.h:112
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
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
In block/blk-merge.c (ffffffff81570e3f)
Location: block/blk-crypto-internal.h:112
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
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
In block/blk-merge.c (ffffffff815d54ea)
Location: block/blk-crypto-internal.h:112
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
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
In block/blk-merge.c (ffffffff8168130d)
Location: block/blk-crypto-internal.h:124
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_crypt_do_front_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173ca70)
Location: block/blk-crypto-internal.h:138
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
**Symbols:**

```
ffffffff8173ca70-ffffffff8173cab3: bio_crypt_do_front_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_crypt_do_front_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81778ff0)
Location: block/blk-crypto-internal.h:148
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
**Symbols:**

```
ffffffff81778ff0-ffffffff81779033: bio_crypt_do_front_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_crypt_do_front_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bb3c0)
Location: block/blk-crypto-internal.h:148
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
**Symbols:**

```
ffffffff817bb3c0-ffffffff817bb403: bio_crypt_do_front_merge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
