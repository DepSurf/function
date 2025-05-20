# Function: <code>task_css_is_root</code>

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
In kernel/cgroup_freezer.c (ffffffff81119c75)
Location: include/linux/cgroup.h:467
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_fork
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
In kernel/cgroup_freezer.c (ffffffff81121a85)
Location: include/linux/cgroup.h:471
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_fork
```
```
In kernel/cpuset.c (ffffffff81123005)
Location: include/linux/cgroup.h:471
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_fork
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
In kernel/cgroup_freezer.c (ffffffff8112a0c5)
Location: include/linux/cgroup.h:471
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_fork
```
```
In kernel/cpuset.c (ffffffff8112aeb5)
Location: include/linux/cgroup.h:471
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_fork
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
In kernel/cgroup/freezer.c (ffffffff8112afc5)
Location: include/linux/cgroup.h:491
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8112c995)
Location: include/linux/cgroup.h:491
Inline: True
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
In kernel/cgroup/freezer.c (ffffffff81137e95)
Location: include/linux/cgroup.h:513
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81139845)
Location: include/linux/cgroup.h:513
Inline: True
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
In kernel/cgroup/freezer.c (ffffffff811467b5)
Location: include/linux/cgroup.h:513
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81148025)
Location: include/linux/cgroup.h:513
Inline: True
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
In kernel/cgroup/freezer.c (ffffffff81152385)
Location: include/linux/cgroup.h:515
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81153c05)
Location: include/linux/cgroup.h:515
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff8115e9e5)
Location: include/linux/cgroup.h:528
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81160165)
Location: include/linux/cgroup.h:528
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff8116a645)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8116be35)
Location: include/linux/cgroup.h:530
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff8117c125)
Location: include/linux/cgroup.h:536
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117d855)
Location: include/linux/cgroup.h:536
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff81178f65)
Location: include/linux/cgroup.h:536
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117a6a5)
Location: include/linux/cgroup.h:536
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff81179ad5)
Location: include/linux/cgroup.h:536
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b225)
Location: include/linux/cgroup.h:536
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff811a13f5)
Location: include/linux/cgroup.h:536
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff811a2d75)
Location: include/linux/cgroup.h:536
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff811d1d15)
Location: include/linux/cgroup.h:537
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff811d3c65)
Location: include/linux/cgroup.h:537
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff81215a15)
Location: include/linux/cgroup.h:479
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81217a05)
Location: include/linux/cgroup.h:479
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff8122b345)
Location: include/linux/cgroup.h:478
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff81243305)
Location: include/linux/cgroup.h:476
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffff8000101de1a8)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffff8000101e0328)
Location: include/linux/cgroup.h:530
Inline: True
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
In kernel/cgroup/legacy_freezer.c (c041fe60)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (c0421ca4)
Location: include/linux/cgroup.h:530
Inline: True
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
In kernel/cgroup/legacy_freezer.c (c00000000024c010)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (c00000000024ef70)
Location: include/linux/cgroup.h:530
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffe000155860)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffe0001571d0)
Location: include/linux/cgroup.h:530
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff81162c65)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81164455)
Location: include/linux/cgroup.h:530
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff81155eb5)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff811576a5)
Location: include/linux/cgroup.h:530
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff81160a35)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81162225)
Location: include/linux/cgroup.h:530
Inline: True
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
In kernel/cgroup/legacy_freezer.c (ffffffff8116ddb5)
Location: include/linux/cgroup.h:530
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8116f7a5)
Location: include/linux/cgroup.h:530
Inline: True
```
</details>
</li>
</ul>

## Differences
