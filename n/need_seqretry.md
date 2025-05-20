# Function: <code>need_seqretry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b19a6)
Location: include/linux/seqlock.h:531
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff8122301b)
Location: include/linux/seqlock.h:531
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b4456)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff8124b5e8)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810baa60)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff8125e5c8)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b5330)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff8126be32)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc4e0)
Location: include/linux/seqlock.h:535
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff8128f722)
Location: include/linux/seqlock.h:535
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
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
In kernel/sched/cputime.c (ffffffff810c3bb0)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff812b6393)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff812d37ff)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810cce70)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff812cafd3)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff812e91af)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d5252)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff812e7fd5)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81307a4a)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810df812)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff812f9b65)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff8131aaca)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7b63)
Location: include/linux/seqlock.h:577
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff81332509)
Location: include/linux/seqlock.h:577
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81354693)
Location: include/linux/seqlock.h:577
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e5862)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff8133e6db)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81360fa2)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7832)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff81344ac8)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81367a81)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810feed2)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff813925b8)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813b6971)
Location: include/linux/seqlock.h:1156
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811397a9)
Location: include/linux/seqlock.h:1152
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff814121ff)
Location: include/linux/seqlock.h:1152
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff8143bfe2)
Location: include/linux/seqlock.h:1152
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81163f69)
Location: include/linux/seqlock.h:1152
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff8149cfef)
Location: include/linux/seqlock.h:1152
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff814ca642)
Location: include/linux/seqlock.h:1152
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81174749)
Location: include/linux/seqlock.h:1153
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff814d244d)
Location: include/linux/seqlock.h:1153
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81500880)
Location: include/linux/seqlock.h:1153
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81123b8b)
Location: include/linux/seqlock.h:1088
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_policy.c (ffffffff81182b2b)
Location: include/linux/seqlock.h:1088
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff81504e56)
Location: include/linux/seqlock.h:1088
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff815354a0)
Location: include/linux/seqlock.h:1088
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/proc/base.c (ffffffff815a3166)
Location: include/linux/seqlock.h:1088
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff815ac43f)
Location: include/linux/seqlock.h:1088
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffff80001013f1d0)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffff8000103a74fc)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffff8000103d1c64)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c038f268)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (c0588154)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (c05ac9d4)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c00000000018e36c)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (c0000000004a24a8)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (c0000000004d49d4)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffe0000ed904)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffe00026e8a6)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffe00028d290)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d9a02)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff812f2145)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813130aa)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8ca1)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff812e2d75)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81303cba)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d5d42)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff812eff55)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff81310e9a)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e1657)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In fs/dcache.c (ffffffff812ffacf)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/d_path.c (ffffffff813226e2)
Location: include/linux/seqlock.h:534
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
```
</details>
</li>
</ul>

## Differences
