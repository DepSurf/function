# Function: <code>blkcg_policy_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d77a0)
Location: block/blk-cgroup.c:1381
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff813d77a0-ffffffff813d7891: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141d4a0)
Location: block/blk-cgroup.c:1390
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff8141d4a0-ffffffff8141d591: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81438a60)
Location: block/blk-cgroup.c:1389
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff81438a60-ffffffff81438b51: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814461b0)
Location: block/blk-cgroup.c:1475
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff814461b0-ffffffff8144628f: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81472d50)
Location: block/blk-cgroup.c:1482
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff81472d50-ffffffff81472e39: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a7110)
Location: block/blk-cgroup.c:1517
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit
  - block/cfq-iosched.c:cfq_init
```
**Symbols:**

```
ffffffff814a7110-ffffffff814a7201: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c1220)
Location: block/blk-cgroup.c:1551
Inline: False
```
**Symbols:**

```
ffffffff814c1220-ffffffff814c1311: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (0)
Location: block/blk-cgroup.c:1517
Inline: False
```
**Symbols:**

```
ffffffff814f1bea-ffffffff814f1bfd: blkcg_policy_unregister.cold (STB_LOCAL)
ffffffff814ef9d0-ffffffff814efabd: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81508e70)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff81508e70-ffffffff81508f61: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156a000)
Location: block/blk-cgroup.c:1472
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff8156a000-ffffffff8156a0f1: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81584a50)
Location: block/blk-cgroup.c:1525
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff81584a50-ffffffff81584b41: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158b710)
Location: block/blk-cgroup.c:1530
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff8158b710-ffffffff8158b801: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f0920)
Location: block/blk-cgroup.c:1524
Inline: False
Direct callers:
  - block/blk-ioprio.c:ioprio_exit
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff815f0920-ffffffff815f0ab2: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a1e60)
Location: block/blk-cgroup.c:1618
Inline: False
Direct callers:
  - block/blk-ioprio.c:ioprio_exit
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff816a1e60-ffffffff816a1ffe: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81760990)
Location: block/blk-cgroup.c:1630
Inline: False
Direct callers:
  - block/blk-ioprio.c:ioprio_exit
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff81760990-ffffffff81760a5e: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8179f5e0)
Location: block/blk-cgroup.c:1742
Inline: False
Direct callers:
  - block/blk-ioprio.c:ioprio_exit
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff8179f5e0-ffffffff8179f6ae: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e30b0)
Location: block/blk-cgroup.c:1755
Inline: False
Direct callers:
  - block/blk-ioprio.c:ioprio_exit
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff817e30b0-ffffffff817e317e: blkcg_policy_unregister (STB_GLOBAL)
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
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060bd08)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffff80001060bd08-ffff80001060be18: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b6eb4)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
c07b6eb4-c07b6fb8: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007a8780)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
c0000000007a8780-c0000000007a8928: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe000444a7c)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffe000444a7c-ffffffe000444b7c: blkcg_policy_unregister (STB_GLOBAL)
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
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81501450)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff81501450-ffffffff81501541: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1960)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff814f1960-ffffffff814f1a51: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814fd4e0)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff814fd4e0-ffffffff814fd5d1: blkcg_policy_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blkcg_policy_unregister(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815169b0)
Location: block/blk-cgroup.c:1580
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_exit
```
**Symbols:**

```
ffffffff815169b0-ffffffff81516aa1: blkcg_policy_unregister (STB_GLOBAL)
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
