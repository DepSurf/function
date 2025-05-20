# Function: <code>css_rightmost_descendant</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811165c0)
Location: kernel/cgroup.c:3874
Inline: False
Direct callers:
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
**Symbols:**

```
ffffffff811165c0-ffffffff81116609: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111d450)
Location: kernel/cgroup.c:4063
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff8111d450-ffffffff8111d49a: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81125780)
Location: kernel/cgroup.c:4074
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
```
**Symbols:**

```
ffffffff81125780-ffffffff811257ca: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81126370)
Location: kernel/cgroup/cgroup.c:3561
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
```
**Symbols:**

```
ffffffff81126370-ffffffff811263ba: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81132670)
Location: kernel/cgroup/cgroup.c:3930
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81132670-ffffffff811326ba: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81140d50)
Location: kernel/cgroup/cgroup.c:3967
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81140d50-ffffffff81140d9a: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c7d0)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff8114c7d0-ffffffff8114c81a: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811583b0)
Location: kernel/cgroup/cgroup.c:4288
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff811583b0-ffffffff811583f7: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164030)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81164030-ffffffff81164077: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174e60)
Location: kernel/cgroup/cgroup.c:4232
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81174e60-ffffffff81174ee4: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171b20)
Location: kernel/cgroup/cgroup.c:4233
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81171b20-ffffffff81171b9e: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172750)
Location: kernel/cgroup/cgroup.c:4246
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81172750-ffffffff811727cf: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811992d0)
Location: kernel/cgroup/cgroup.c:4421
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff811992d0-ffffffff8119934f: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c9460)
Location: kernel/cgroup/cgroup.c:4432
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff811c9460-ffffffff811c94e2: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120c560)
Location: kernel/cgroup/cgroup.c:4629
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff8120c560-ffffffff8120c5e2: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81221b70)
Location: kernel/cgroup/cgroup.c:4606
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81221b70-ffffffff81221bf2: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81239860)
Location: kernel/cgroup/cgroup.c:4636
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81239860-ffffffff812398e2: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d58a8)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffff8000101d58a8-ffff8000101d5918: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04183a8)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
c04183a8-c0418400: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002410f0)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
c0000000002410f0-c000000000241188: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014eb8a)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffe00014eb8a-ffffffe00014ebde: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c650)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff8115c650-ffffffff8115c697: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f940)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff8114f940-ffffffff8114f987: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a420)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff8115a420-ffffffff8115a467: css_rightmost_descendant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_rightmost_descendant(struct cgroup_subsys_state *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81167480)
Location: kernel/cgroup/cgroup.c:4290
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
**Symbols:**

```
ffffffff81167480-ffffffff811674c7: css_rightmost_descendant (STB_GLOBAL)
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
