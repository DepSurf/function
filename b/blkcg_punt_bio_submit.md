# Function: <code>blkcg_punt_bio_submit</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ccf22)
Location: include/linux/blk-cgroup.h:711
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (ffffffff814e6154)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:560
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:516
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:516
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (0)
Location: include/linux/blk-cgroup.h:521
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (0)
Location: block/blk-cgroup.h:396
Inline: True
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
In block/blk-core.c (ffffffff81735d95)
Location: block/blk-cgroup.h:380
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkcg_punt_bio_submit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8179ed60)
Location: block/blk-cgroup.c:242
Inline: False
```
**Symbols:**

```
ffffffff8179ed60-ffffffff8179edfd: blkcg_punt_bio_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkcg_punt_bio_submit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e2840)
Location: block/blk-cgroup.c:242
Inline: False
```
**Symbols:**

```
ffffffff817e2840-ffffffff817e28dd: blkcg_punt_bio_submit (STB_GLOBAL)
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
In block/blk-core.c (ffff8000105e3710)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (c0790a08)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (c0000000007770cc)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (ffffffe0004251e0)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (ffffffff814de734)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (ffffffff814cf0d4)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (ffffffff814da7c4)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
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
In block/blk-core.c (ffffffff814f34c4)
Location: include/linux/blk-cgroup.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
