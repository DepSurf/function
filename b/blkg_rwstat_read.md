# Function: <code>blkg_rwstat_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat *rwstat);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d71a0)
Location: include/linux/blk-cgroup.h:625
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff813de0e0)
Location: include/linux/blk-cgroup.h:625
Inline: False
Direct callers:
  - block/cfq-iosched.c:blkg_rwstat_add_aux
  - block/cfq-iosched.c:blkg_rwstat_total
```
**Symbols:**

```
ffffffff813d71a0-ffffffff813d7244: blkg_rwstat_read (STB_LOCAL)
ffffffff813de0e0-ffffffff813de184: blkg_rwstat_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat *rwstat);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141ceb0)
Location: include/linux/blk-cgroup.h:626
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff81424200)
Location: include/linux/blk-cgroup.h:626
Inline: False
Direct callers:
  - block/cfq-iosched.c:blkg_rwstat_add_aux
  - block/cfq-iosched.c:blkg_rwstat_total
```
**Symbols:**

```
ffffffff8141ceb0-ffffffff8141cf54: blkg_rwstat_read (STB_LOCAL)
ffffffff81424200-ffffffff814242a4: blkg_rwstat_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat *rwstat);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81438480)
Location: include/linux/blk-cgroup.h:616
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff8143fc10)
Location: include/linux/blk-cgroup.h:616
Inline: False
Direct callers:
  - block/cfq-iosched.c:blkg_rwstat_add_aux
  - block/cfq-iosched.c:blkg_rwstat_total
```
**Symbols:**

```
ffffffff81438480-ffffffff81438524: blkg_rwstat_read (STB_LOCAL)
ffffffff8143fc10-ffffffff8143fcb4: blkg_rwstat_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat *rwstat);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81445c00)
Location: include/linux/blk-cgroup.h:616
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff8144ee90)
Location: include/linux/blk-cgroup.h:616
Inline: False
Direct callers:
  - block/cfq-iosched.c:blkg_rwstat_add_aux
  - block/cfq-iosched.c:blkg_rwstat_total
```
**Symbols:**

```
ffffffff81445c00-ffffffff81445ca4: blkg_rwstat_read (STB_LOCAL)
ffffffff8144ee90-ffffffff8144ef34: blkg_rwstat_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate ⚠️</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat *rwstat);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81472750)
Location: include/linux/blk-cgroup.h:612
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff8147afd0)
Location: include/linux/blk-cgroup.h:612
Inline: False
Direct callers:
  - block/cfq-iosched.c:blkg_rwstat_add_aux
  - block/cfq-iosched.c:blkg_rwstat_total
```
**Symbols:**

```
ffffffff81472750-ffffffff814727f4: blkg_rwstat_read (STB_LOCAL)
ffffffff8147afd0-ffffffff8147b074: blkg_rwstat_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat *rwstat);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a6cf0)
Location: include/linux/blk-cgroup.h:630
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
```
```
In block/cfq-iosched.c (ffffffff814af730)
Location: include/linux/blk-cgroup.h:630
Inline: False
Direct callers:
  - block/cfq-iosched.c:blkg_rwstat_total
```
**Symbols:**

```
ffffffff814a6cf0-ffffffff814a6d94: blkg_rwstat_read (STB_LOCAL)
ffffffff814af730-ffffffff814af7d4: blkg_rwstat_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c0cf0)
Location: include/linux/blk-cgroup.h:696
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
```
**Symbols:**

```
ffffffff814c0cf0-ffffffff814c0d93: blkg_rwstat_read (STB_LOCAL)
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
In block/blk-cgroup.c (ffffffff814ef617)
Location: include/linux/blk-cgroup.h:640
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (ffffffff81508aa7)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup-rwstat.c (ffffffff8156c2f5)
Location: block/blk-cgroup-rwstat.h:89
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
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
In block/blk-cgroup-rwstat.c (ffffffff81587095)
Location: block/blk-cgroup-rwstat.h:89
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
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
In block/blk-cgroup-rwstat.c (ffffffff8158dee1)
Location: block/blk-cgroup-rwstat.h:89
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
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
In block/blk-cgroup-rwstat.c (ffffffff815f3a39)
Location: block/blk-cgroup-rwstat.h:89
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
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
In block/blk-cgroup-rwstat.c (ffffffff816a5159)
Location: block/blk-cgroup-rwstat.h:89
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
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
In block/blk-cgroup-rwstat.c (ffffffff81763fc9)
Location: block/blk-cgroup-rwstat.h:89
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
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
In block/blk-cgroup-rwstat.c (ffffffff817a306b)
Location: block/blk-cgroup-rwstat.h:89
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
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
In block/blk-cgroup-rwstat.c (ffffffff817e6bbb)
Location: block/blk-cgroup-rwstat.h:89
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (ffff80001060b784)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (c07b669c)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (c0000000007a8004)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (ffffffe0004446ee)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (ffffffff81501087)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (ffffffff814f1597)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (ffffffff814fd117)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
In block/blk-cgroup.c (ffffffff815162b7)
Location: include/linux/blk-cgroup.h:642
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
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
</ul>
