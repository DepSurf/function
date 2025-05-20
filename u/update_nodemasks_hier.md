# Function: <code>update_nodemasks_hier</code>

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
In kernel/cpuset.c (ffffffff8111c6c0)
Location: kernel/cpuset.c:1148
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
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
In kernel/cpuset.c (ffffffff811245c0)
Location: kernel/cpuset.c:1150
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
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
In kernel/cpuset.c (ffffffff8112d873)
Location: kernel/cpuset.c:1150
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8112ee16)
Location: kernel/cgroup/cpuset.c:1138
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8113bcb6)
Location: kernel/cgroup/cpuset.c:1149
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8114a558)
Location: kernel/cgroup/cpuset.c:1150
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff811570fa)
Location: kernel/cgroup/cpuset.c:1673
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff81163c74)
Location: kernel/cgroup/cpuset.c:1634
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8116faa9)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_nodemasks_hier(struct cpuset *cs, nodemask_t *new_mems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117ea80)
Location: kernel/cgroup/cpuset.c:1710
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8117ea80-ffffffff8117edea: update_nodemasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_nodemasks_hier(struct cpuset *cs, nodemask_t *new_mems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117b8e0)
Location: kernel/cgroup/cpuset.c:1733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8117b8e0-ffffffff8117bc78: update_nodemasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_nodemasks_hier(struct cpuset *cs, nodemask_t *new_mems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117d280)
Location: kernel/cgroup/cpuset.c:1733
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8117d280-ffffffff8117d618: update_nodemasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_nodemasks_hier(struct cpuset *cs, nodemask_t *new_mems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a4e20)
Location: kernel/cgroup/cpuset.c:1784
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff811a4e20-ffffffff811a51b8: update_nodemasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_nodemasks_hier(struct cpuset *cs, nodemask_t *new_mems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d4ca0)
Location: kernel/cgroup/cpuset.c:1822
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff811d4ca0-ffffffff811d5028: update_nodemasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_nodemasks_hier(struct cpuset *cs, nodemask_t *new_mems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81218b80)
Location: kernel/cgroup/cpuset.c:2011
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff81218b80-ffffffff81218efb: update_nodemasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_nodemasks_hier(struct cpuset *cs, nodemask_t *new_mems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8122e3f0)
Location: kernel/cgroup/cpuset.c:2046
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff8122e3f0-ffffffff8122e76b: update_nodemasks_hier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_nodemasks_hier(struct cpuset *cs, nodemask_t *new_mems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff812468d0)
Location: kernel/cgroup/cpuset.c:2827
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff812468d0-ffffffff81246c4b: update_nodemasks_hier (STB_LOCAL)
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
In kernel/cgroup/cpuset.c (ffff8000101e36fc)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (c0424394)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (c00000000025319c)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffe000159cf4)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff811680c9)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff8115b2e3)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff81165e99)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (ffffffff81173470)
Location: kernel/cgroup/cpuset.c:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
