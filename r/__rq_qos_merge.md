# Function: <code>__rq_qos_merge</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff815053c0)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
ffffffff815053c0-ffffffff81505401: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81565c90)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_front_merge
  - block/blk-core.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff81565c90-ffffffff81565cd1: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81580c10)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff81580c10-ffffffff81580c51: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81588780)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff81588780-ffffffff815887c1: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff815ee420)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff815ee420-ffffffff815ee461: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8169ec70)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff8169ec70-ffffffff8169ecbd: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8175d4d0)
Location: block/blk-rq-qos.c:80
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff8175d4d0-ffffffff8175d51d: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8179c230)
Location: block/blk-rq-qos.c:80
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff8179c230-ffffffff8179c27d: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff817dfc90)
Location: block/blk-rq-qos.c:80
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff817dfc90-ffffffff817dfcdd: __rq_qos_merge (STB_GLOBAL)
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
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffff800010607468)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
ffff800010607468-ffff8000106074c4: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c07b2690)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
c07b2690-c07b26e0: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c0000000007a3f30)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
c0000000007a3f30-c0000000007a3fc4: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffe0004420c4)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
ffffffe0004420c4-ffffffe000442102: __rq_qos_merge (STB_GLOBAL)
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
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814fd9a0)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
ffffffff814fd9a0-ffffffff814fd9e1: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814edeb0)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
ffffffff814edeb0-ffffffff814edef1: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814f9a30)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
ffffffff814f9a30-ffffffff814f9a71: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81512a90)
Location: block/blk-rq-qos.c:86
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
ffffffff81512a90-ffffffff81512ad1: __rq_qos_merge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
