# Function: <code>blkcg_bio_issue_check</code>

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
In block/blk-core.c (ffffffff813b61ba)
Location: include/linux/blk-cgroup.h:693
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813faff0)
Location: include/linux/blk-cgroup.h:694
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414abb)
Location: include/linux/blk-cgroup.h:684
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424769)
Location: include/linux/blk-cgroup.h:684
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d895)
Location: include/linux/blk-cgroup.h:680
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814827cb)
Location: include/linux/blk-cgroup.h:700
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff8149d58b)
Location: include/linux/blk-cgroup.h:772
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814cb7cb)
Location: include/linux/blk-cgroup.h:724
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814e4a8e)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blkcg_bio_issue_check(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81542af0)
Location: include/linux/blk-cgroup.h:573
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff81542af0-ffffffff81542c40: blkcg_bio_issue_check (STB_LOCAL)
```
</details>
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
In block/blk-core.c (ffff8000105e2dd4)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (c078f150)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (c00000000077539c)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffe0004240a0)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814dd06e)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814cda19)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814d90fe)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814f1d11)
Location: include/linux/blk-cgroup.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
