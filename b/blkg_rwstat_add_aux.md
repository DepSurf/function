# Function: <code>blkg_rwstat_add_aux</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat *to, struct blkg_rwstat *from);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d7330)
Location: include/linux/blk-cgroup.h:673
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/cfq-iosched.c (ffffffff813de190)
Location: include/linux/blk-cgroup.h:673
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff813d7330-ffffffff813d73c7: blkg_rwstat_add_aux (STB_LOCAL)
ffffffff813de190-ffffffff813de227: blkg_rwstat_add_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat *to, struct blkg_rwstat *from);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141d040)
Location: include/linux/blk-cgroup.h:674
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/cfq-iosched.c (ffffffff814242b0)
Location: include/linux/blk-cgroup.h:674
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff8141d040-ffffffff8141d0bd: blkg_rwstat_add_aux (STB_LOCAL)
ffffffff814242b0-ffffffff8142432d: blkg_rwstat_add_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat *to, struct blkg_rwstat *from);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81438610)
Location: include/linux/blk-cgroup.h:664
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/cfq-iosched.c (ffffffff8143fcc0)
Location: include/linux/blk-cgroup.h:664
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff81438610-ffffffff8143868d: blkg_rwstat_add_aux (STB_LOCAL)
ffffffff8143fcc0-ffffffff8143fd3d: blkg_rwstat_add_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat *to, struct blkg_rwstat *from);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81445d90)
Location: include/linux/blk-cgroup.h:664
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/cfq-iosched.c (ffffffff8144ef40)
Location: include/linux/blk-cgroup.h:664
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff81445d90-ffffffff81445e0d: blkg_rwstat_add_aux (STB_LOCAL)
ffffffff8144ef40-ffffffff8144efbd: blkg_rwstat_add_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate ⚠️</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat *to, struct blkg_rwstat *from);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814728e0)
Location: include/linux/blk-cgroup.h:660
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/cfq-iosched.c (ffffffff8147b080)
Location: include/linux/blk-cgroup.h:660
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff814728e0-ffffffff8147295d: blkg_rwstat_add_aux (STB_LOCAL)
ffffffff8147b080-ffffffff8147b0fd: blkg_rwstat_add_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a7f64)
Location: include/linux/blk-cgroup.h:678
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/cfq-iosched.c (ffffffff814b2b0e)
Location: include/linux/blk-cgroup.h:678
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
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
In block/blk-cgroup.c (ffffffff814c1c15)
Location: include/linux/blk-cgroup.h:744
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (ffffffff814f02d0)
Location: include/linux/blk-cgroup.h:687
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (ffffffff81509780)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060c558)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (c07b7c10)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (c0000000007a932c)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (ffffffe000444fda)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (ffffffff81501d60)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (ffffffff814f2270)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (ffffffff814fddf0)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
In block/blk-cgroup.c (ffffffff815175d0)
Location: include/linux/blk-cgroup.h:689
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
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
</ul>
