# Function: <code>blkcg_policy_enabled</code>

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
In block/blk-cgroup.c (ffffffff813d7b55)
Location: block/blk-cgroup.c:52
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_conf_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141cc70)
Location: block/blk-cgroup.c:52
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8141cc70-ffffffff8141cc92: blkcg_policy_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81438240)
Location: block/blk-cgroup.c:52
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81438240-ffffffff81438262: blkcg_policy_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81445a70)
Location: block/blk-cgroup.c:53
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81445a70-ffffffff81445a90: blkcg_policy_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814725b0)
Location: block/blk-cgroup.c:53
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff814725b0-ffffffff814725d1: blkcg_policy_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a6b40)
Location: block/blk-cgroup.c:53
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff814a6b40-ffffffff814a6b61: blkcg_policy_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c0b90)
Location: block/blk-cgroup.c:56
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff814c0b90-ffffffff814c0bb1: blkcg_policy_enabled (STB_LOCAL)
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
In block/blk-cgroup.c (ffffffff814f04a5)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff81509942)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff8156bac2)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff8158675c)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff8158d46c)
Location: block/blk-cgroup.c:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff815f2f28)
Location: block/blk-cgroup.c:61
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff816a424e)
Location: block/blk-cgroup.c:79
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8175fe40)
Location: block/blk-cgroup.c:111
Inline: True
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8175fe40-ffffffff8175fe68: blkcg_policy_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8179ee10)
Location: block/blk-cgroup.c:113
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_deactivate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8179ee10-ffffffff8179ee38: blkcg_policy_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue *q, const struct blkcg_policy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e28f0)
Location: block/blk-cgroup.c:113
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_deactivate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff817e28f0-ffffffff817e2918: blkcg_policy_enabled (STB_LOCAL)
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
In block/blk-cgroup.c (ffff80001060c714)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (c07b6354)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (c0000000007a9648)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffe0004453f0)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff81501f22)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff814f2432)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff814fdfb2)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffff815160f7)
Location: block/blk-cgroup.c:60
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkg_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
