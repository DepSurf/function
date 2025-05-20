# Function: <code>__cfq_set_weight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __cfq_set_weight(struct cgroup_subsys_state *css, u64 val, bool on_dfl, bool reset_dev, bool is_leaf_weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813df0d0)
Location: block/cfq-iosched.c:1817
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight
  - block/cfq-iosched.c:cfq_set_leaf_weight
  - block/cfq-iosched.c:cfq_cpd_bind
  - block/cfq-iosched.c:cfq_cpd_bind
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
```
**Symbols:**

```
ffffffff813df0d0-ffffffff813df20f: __cfq_set_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __cfq_set_weight(struct cgroup_subsys_state *css, u64 val, bool on_dfl, bool reset_dev, bool is_leaf_weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81425640)
Location: block/cfq-iosched.c:1841
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_set_leaf_weight
  - block/cfq-iosched.c:cfq_set_weight
  - block/cfq-iosched.c:cfq_cpd_bind
  - block/cfq-iosched.c:cfq_cpd_bind
```
**Symbols:**

```
ffffffff81425640-ffffffff81425769: __cfq_set_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __cfq_set_weight(struct cgroup_subsys_state *css, u64 val, bool on_dfl, bool reset_dev, bool is_leaf_weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81444400)
Location: block/cfq-iosched.c:1832
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_set_leaf_weight
  - block/cfq-iosched.c:cfq_set_weight
  - block/cfq-iosched.c:cfq_cpd_bind
  - block/cfq-iosched.c:cfq_cpd_bind
```
**Symbols:**

```
ffffffff81444400-ffffffff81444529: __cfq_set_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __cfq_set_weight(struct cgroup_subsys_state *css, u64 val, bool on_dfl, bool reset_dev, bool is_leaf_weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814535d0)
Location: block/cfq-iosched.c:1837
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_set_leaf_weight
  - block/cfq-iosched.c:cfq_set_weight
  - block/cfq-iosched.c:cfq_cpd_bind
  - block/cfq-iosched.c:cfq_cpd_bind
```
**Symbols:**

```
ffffffff814535d0-ffffffff81453731: __cfq_set_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cfq_set_weight(struct cgroup_subsys_state *css, u64 val, bool on_dfl, bool reset_dev, bool is_leaf_weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147ce50)
Location: block/cfq-iosched.c:1817
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_set_leaf_weight
  - block/cfq-iosched.c:cfq_set_weight
  - block/cfq-iosched.c:cfq_cpd_bind
  - block/cfq-iosched.c:cfq_cpd_bind
```
**Symbols:**

```
ffffffff8147ce50-ffffffff8147cfb1: __cfq_set_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cfq_set_weight(struct cgroup_subsys_state *css, u64 val, bool on_dfl, bool reset_dev, bool is_leaf_weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b1870)
Location: block/cfq-iosched.c:1820
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_set_leaf_weight
  - block/cfq-iosched.c:cfq_set_weight
  - block/cfq-iosched.c:cfq_cpd_bind
  - block/cfq-iosched.c:cfq_cpd_bind
```
**Symbols:**

```
ffffffff814b1870-ffffffff814b19d1: __cfq_set_weight (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
