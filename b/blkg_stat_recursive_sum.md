# Function: <code>blkg_stat_recursive_sum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 blkg_stat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d7ff0)
Location: block/blk-cgroup.c:698
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
```
**Symbols:**

```
ffffffff813d7ff0-ffffffff813d80ec: blkg_stat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 blkg_stat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141dd20)
Location: block/blk-cgroup.c:698
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
```
**Symbols:**

```
ffffffff8141dd20-ffffffff8141de20: blkg_stat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 blkg_stat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814392e0)
Location: block/blk-cgroup.c:699
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
```
**Symbols:**

```
ffffffff814392e0-ffffffff814393e0: blkg_stat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 blkg_stat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81446a60)
Location: block/blk-cgroup.c:700
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
```
**Symbols:**

```
ffffffff81446a60-ffffffff81446b66: blkg_stat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 blkg_stat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81473640)
Location: block/blk-cgroup.c:700
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
```
**Symbols:**

```
ffffffff81473640-ffffffff81473746: blkg_stat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 blkg_stat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a7690)
Location: block/blk-cgroup.c:711
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
```
**Symbols:**

```
ffffffff814a7690-ffffffff814a7778: blkg_stat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 blkg_stat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c1820)
Location: block/blk-cgroup.c:704
Inline: False
```
**Symbols:**

```
ffffffff814c1820-ffffffff814c1905: blkg_stat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
