# Function: <code>__nodes_subset</code>

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
In kernel/cpuset.c (ffffffff8111c649)
Location: include/linux/nodemask.h:207
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:207
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e17b6)
Location: include/linux/nodemask.h:207
Inline: True
Inline callers:
  - mm/mempolicy.c:SyS_migrate_pages
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
In kernel/cpuset.c (ffffffff81124549)
Location: include/linux/nodemask.h:209
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff811a58e3)
Location: include/linux/nodemask.h:209
Inline: True
```
```
In mm/mempolicy.c (ffffffff81201daa)
Location: include/linux/nodemask.h:209
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/mempolicy.c:SyS_migrate_pages
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
In kernel/cpuset.c (ffffffff8112d722)
Location: include/linux/nodemask.h:209
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff811b5d80)
Location: include/linux/nodemask.h:209
Inline: True
```
```
In mm/mempolicy.c (ffffffff812138d2)
Location: include/linux/nodemask.h:209
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8112ecc5)
Location: include/linux/nodemask.h:209
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff811bd917)
Location: include/linux/nodemask.h:209
Inline: True
```
```
In mm/mempolicy.c (ffffffff8121ebe9)
Location: include/linux/nodemask.h:209
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8113bb65)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff811d2557)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff81239e09)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8114ac47)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff811f3497)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff8125d3f9)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff81157456)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff8120549a)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff81271cac)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff81163fef)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff8121c447)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff8128d2eb)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8116fe2b)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff81229e17)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff8129cf1a)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff81181e9a)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff8125572e)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/mempolicy.c (ffffffff812d0afa)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8117edaa)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff812603ae)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/mempolicy.c (ffffffff812dc61a)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8117edb7)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff8126509e)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/mempolicy.c (ffffffff812e3e6d)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff811a6f77)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff812a18ce)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/mempolicy.c (ffffffff8132b15d)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff811d7fdb)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:is_cpuset_subset
```
```
In mm/oom_kill.c (ffffffff812f978e)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/mempolicy.c (ffffffff8139abd0)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8121ceea)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:is_cpuset_subset
```
```
In mm/oom_kill.c (ffffffff8136336e)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/mempolicy.c (ffffffff8141ac40)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8123333b)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:is_cpuset_subset
```
```
In mm/oom_kill.c (ffffffff813957be)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/mempolicy.c (ffffffff8144e1a0)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8124d062)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:is_cpuset_subset
```
```
In mm/oom_kill.c (ffffffff813bf57e)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/mempolicy.c (ffffffff81487d40)
Location: include/linux/nodemask.h:220
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffff8000101e392c)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffff8000102b7d44)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffff80001033bfc4)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (c0424638)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/cgroup/cpuset.c (c000000000253580)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (c00000000036fc08)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (c000000000416f30)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffe000159f1a)
Location: include/linux/nodemask.h:219
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116844b)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff81222467)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff812954fa)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8115b65f)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff81215617)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff8128710a)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff8116621b)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff81220207)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff8129330a)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
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
In kernel/cgroup/cpuset.c (ffffffff81173819)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff8122f327)
Location: include/linux/nodemask.h:219
Inline: True
```
```
In mm/mempolicy.c (ffffffff812a316a)
Location: include/linux/nodemask.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
```
</details>
</li>
</ul>

## Differences
