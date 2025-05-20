# Function: <code>blkg_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d7a10)
Location: block/blk-cgroup.c:91
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkcg_init_queue
```
**Symbols:**

```
ffffffff813d7a10-ffffffff813d7c3d: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141d710)
Location: block/blk-cgroup.c:91
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff8141d710-ffffffff8141d940: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81438cd0)
Location: block/blk-cgroup.c:91
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff81438cd0-ffffffff81438f00: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814464e0)
Location: block/blk-cgroup.c:92
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff814464e0-ffffffff8144671a: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814730b0)
Location: block/blk-cgroup.c:92
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff814730b0-ffffffff814732ef: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a7480)
Location: block/blk-cgroup.c:92
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff814a7480-ffffffff814a768e: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c1570)
Location: block/blk-cgroup.c:123
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff814c1570-ffffffff814c1751: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814efd10)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff814efd10-ffffffff814eff86: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815091c0)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff815091c0-ffffffff81509436: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156a4f0)
Location: block/blk-cgroup.c:144
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff8156a4f0-ffffffff8156a66a: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81584f50)
Location: block/blk-cgroup.c:150
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff81584f50-ffffffff815850c7: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158bae0)
Location: block/blk-cgroup.c:148
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff8158bae0-ffffffff8158bc5b: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f0e80)
Location: block/blk-cgroup.c:151
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff815f0e80-ffffffff815f1064: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a2dd0)
Location: block/blk-cgroup.c:210
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff816a2dd0-ffffffff816a3019: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct gendisk *disk, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817613a0)
Location: block/blk-cgroup.c:242
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff817613a0-ffffffff81761645: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct gendisk *disk, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8179fb50)
Location: block/blk-cgroup.c:305
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff8179fb50-ffffffff8179fe70: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct gendisk *disk, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e3620)
Location: block/blk-cgroup.c:305
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff817e3620-ffffffff817e3975: blkg_alloc (STB_LOCAL)
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
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060bec0)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffff80001060bec0-ffff80001060c104: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b78bc)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
c07b78bc-c07b7b54: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007a8cc0)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
c0000000007a8cc0-c0000000007a9004: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe000444d7e)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffe000444d7e-ffffffe000444f64: blkg_alloc (STB_LOCAL)
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
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815017a0)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff815017a0-ffffffff81501a16: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1cb0)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff814f1cb0-ffffffff814f1f26: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814fd830)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff814fd830-ffffffff814fdaa6: blkg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct blkcg_gq *blkg_alloc(struct blkcg *blkcg, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81516df0)
Location: block/blk-cgroup.c:145
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff81516df0-ffffffff81517066: blkg_alloc (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
</ul>
</details>
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
