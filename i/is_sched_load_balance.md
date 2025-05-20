# Function: <code>is_sched_load_balance</code>

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
In kernel/cpuset.c (ffffffff8111a7ac)
Location: kernel/cpuset.c:197
Inline: True
Inline callers:
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:cpuset_read_u64
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:cpuset_css_offline
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
In kernel/cpuset.c (ffffffff811241b9)
Location: kernel/cpuset.c:197
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_offline
  - kernel/cpuset.c:cpuset_read_u64
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
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
In kernel/cpuset.c (ffffffff8112d0e9)
Location: kernel/cpuset.c:197
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_offline
  - kernel/cpuset.c:cpuset_read_u64
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8112e339)
Location: kernel/cgroup/cpuset.c:200
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8113af39)
Location: kernel/cgroup/cpuset.c:201
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8114a2c9)
Location: kernel/cgroup/cpuset.c:201
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff81156e93)
Location: kernel/cgroup/cpuset.c:252
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff811647d3)
Location: kernel/cgroup/cpuset.c:240
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8117062d)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff81181980)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8117e890)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8117e8a0)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff811a65bd)
Location: kernel/cgroup/cpuset.c:244
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff811d7a39)
Location: kernel/cgroup/cpuset.c:251
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8121c749)
Location: kernel/cgroup/cpuset.c:281
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff81232b39)
Location: kernel/cgroup/cpuset.c:280
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8124c2b9)
Location: kernel/cgroup/cpuset.c:309
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_partition_sd_lb
  - kernel/cgroup/cpuset.c:update_partition_sd_lb
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffff8000101e354c)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (c042400c)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (c000000000254180)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffe000159174)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff81168c4d)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8115be5d)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff81166a1d)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
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
In kernel/cgroup/cpuset.c (ffffffff8117409d)
Location: kernel/cgroup/cpuset.c:241
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
</details>
</li>
</ul>

## Differences
