# Function: <code>mkdir_mondata_subdir</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042190)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1372
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff81042190-ffffffff81042361: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81045660)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1443
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff81045660-ffffffff81045831: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047a90)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff81047a90-ffffffff81047c73: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81056fc0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2289
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff81056fc0-ffffffff810571a3: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff8105a1a0-ffffffff8105a353: mkdir_mondata_subdir (STB_LOCAL)
ffffffff8105d4c9-ffffffff8105d4df: mkdir_mondata_subdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ab20)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2337
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff8105ab20-ffffffff8105ace7: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060110)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81060110-ffffffff810602f5: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e2b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2472
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105e2b0-ffffffff8105e48d: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ec90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2468
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105ec90-ffffffff8105ee6d: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810685a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2519
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff810685a0-ffffffff81068774: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075610)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2519
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff81075610-ffffffff81075844: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81085500)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2565
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
```
**Symbols:**

```
ffffffff81085500-ffffffff81085722: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088250)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2847
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
```
**Symbols:**

```
ffffffff81088250-ffffffff81088464: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108f330)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2975
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
```
**Symbols:**

```
ffffffff8108f330-ffffffff8108f544: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a6a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2337
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff8105a6a0-ffffffff8105a867: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104a720)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2337
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff8104a720-ffffffff8104a8e7: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105aad0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2337
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff8105aad0-ffffffff8105ac97: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mkdir_mondata_subdir(struct kernfs_node *parent_kn, struct rdt_domain *d, struct rdt_resource *r, struct rdtgroup *prgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bf90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2337
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir_allrdtgrp
```
**Symbols:**

```
ffffffff8105bf90-ffffffff8105c157: mkdir_mondata_subdir (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
