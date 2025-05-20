# Function: <code>blkcg_policy_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d75c0)
Location: block/blk-cgroup.c:1308
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
```
**Symbols:**

```
ffffffff813d75c0-ffffffff813d7791: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141d2c0)
Location: block/blk-cgroup.c:1317
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
```
**Symbols:**

```
ffffffff8141d2c0-ffffffff8141d491: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81438890)
Location: block/blk-cgroup.c:1318
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
```
**Symbols:**

```
ffffffff81438890-ffffffff81438a51: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81446000)
Location: block/blk-cgroup.c:1404
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
```
**Symbols:**

```
ffffffff81446000-ffffffff814461af: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81472b60)
Location: block/blk-cgroup.c:1406
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
```
**Symbols:**

```
ffffffff81472b60-ffffffff81472d4c: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a6f20)
Location: block/blk-cgroup.c:1441
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/cfq-iosched.c:cfq_init
```
**Symbols:**

```
ffffffff814a6f20-ffffffff814a710c: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c1030)
Location: block/blk-cgroup.c:1473
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
```
**Symbols:**

```
ffffffff814c1030-ffffffff814c121a: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (0)
Location: block/blk-cgroup.c:1439
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
```
**Symbols:**

```
ffffffff814f1bc4-ffffffff814f1bea: blkcg_policy_register.cold (STB_LOCAL)
ffffffff814ef7e0-ffffffff814ef9cc: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81508c70)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff81508c70-ffffffff81508e61: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81569e00)
Location: block/blk-cgroup.c:1393
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff81569e00-ffffffff81569ff1: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81584850)
Location: block/blk-cgroup.c:1446
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff81584850-ffffffff81584a41: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158b510)
Location: block/blk-cgroup.c:1451
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff8158b510-ffffffff8158b701: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f0640)
Location: block/blk-cgroup.c:1445
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-ioprio.c:ioprio_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff815f0640-ffffffff815f091a: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a1b60)
Location: block/blk-cgroup.c:1539
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-ioprio.c:ioprio_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff816a1b60-ffffffff816a1e5c: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81760730)
Location: block/blk-cgroup.c:1556
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-ioprio.c:ioprio_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff81760730-ffffffff81760978: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8179f390)
Location: block/blk-cgroup.c:1670
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-ioprio.c:ioprio_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff8179f390-ffffffff8179f5c7: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e2e60)
Location: block/blk-cgroup.c:1683
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-ioprio.c:ioprio_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff817e2e60-ffffffff817e3097: blkcg_policy_register (STB_GLOBAL)
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
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060bb00)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffff80001060bb00-ffff80001060bd08: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b6c7c)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
c07b6c7c-c07b6eb4: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007a8470)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
c0000000007a8470-c0000000007a8778: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe0004448ba)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffe0004448ba-ffffffe000444a7c: blkcg_policy_register (STB_GLOBAL)
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
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81501250)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff81501250-ffffffff81501441: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1760)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff814f1760-ffffffff814f1951: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814fd2e0)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff814fd2e0-ffffffff814fd4d1: blkcg_policy_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkcg_policy_register(struct blkcg_policy *pol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815167b0)
Location: block/blk-cgroup.c:1501
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_init
  - block/blk-iocost.c:ioc_init
```
**Symbols:**

```
ffffffff815167b0-ffffffff815169a1: blkcg_policy_register (STB_GLOBAL)
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
