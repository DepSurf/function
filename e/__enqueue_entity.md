# Function: <code>__enqueue_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b2380)
Location: kernel/sched/fair.c:486
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810b2380-ffffffff810b23ee: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b4ea0)
Location: kernel/sched/fair.c:486
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810b4ea0-ffffffff810b4f0e: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bb360)
Location: kernel/sched/fair.c:545
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810bb360-ffffffff810bb3ce: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b5c90)
Location: kernel/sched/fair.c:548
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810b5c90-ffffffff810b5cfe: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bcf80)
Location: kernel/sched/fair.c:550
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810bcf80-ffffffff810bcfde: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4b70)
Location: kernel/sched/fair.c:535
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810c4b70-ffffffff810c4bce: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cdf40)
Location: kernel/sched/fair.c:530
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810cdf40-ffffffff810cdf9e: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6300)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810d6300-ffffffff810d6398: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e0980)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e0980-ffffffff810e0a18: __enqueue_entity (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810f0ff5)
Location: kernel/sched/fair.c:577
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810efc75)
Location: kernel/sched/fair.c:575
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810f16a7)
Location: kernel/sched/fair.c:592
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff8110b1e5)
Location: kernel/sched/fair.c:578
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff81126b6f)
Location: kernel/sched/fair.c:630
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff81150112)
Location: kernel/sched/fair.c:643
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff8115ef83)
Location: kernel/sched/fair.c:643
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81160240)
Location: kernel/sched/fair.c:824
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
```
**Symbols:**

```
ffffffff81160240-ffffffff81160387: __enqueue_entity (STB_LOCAL)
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
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff8000101407c0)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffff8000101407c0-ffff800010140864: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0390ddc)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
c0390ddc-c0390e8c: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000190640)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
c000000000190640-c00000000019072c: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000eed22)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffe0000eed22-ffffffe0000eedba: __enqueue_entity (STB_LOCAL)
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
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dab30)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810dab30-ffffffff810dabc8: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9b40)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810c9b40-ffffffff810c9bd8: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6eb0)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810d6eb0-ffffffff810d6f48: __enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2860)
Location: kernel/sched/fair.c:565
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e2860-ffffffff810e28f8: __enqueue_entity (STB_LOCAL)
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
