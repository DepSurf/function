# Function: <code>cgroup_apply_control_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111d150)
Location: kernel/cgroup.c:3240
Inline: False
```
**Symbols:**

```
ffffffff8111d150-ffffffff8111d44c: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81125480)
Location: kernel/cgroup.c:3249
Inline: False
```
**Symbols:**

```
ffffffff81125480-ffffffff8112577c: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81125b60)
Location: kernel/cgroup/cgroup.c:2764
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81125b60-ffffffff81125e29: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81131e30)
Location: kernel/cgroup/cgroup.c:2899
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81131e30-ffffffff8113210b: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81140580-ffffffff81140855: cgroup_apply_control_enable (STB_LOCAL)
ffffffff81143a65-ffffffff81143abe: cgroup_apply_control_enable.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2962
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff8114c000-ffffffff8114c2d5: cgroup_apply_control_enable (STB_LOCAL)
ffffffff8114f575-ffffffff8114f5ce: cgroup_apply_control_enable.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3102
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81157bd0-ffffffff81157ec1: cgroup_apply_control_enable (STB_LOCAL)
ffffffff8115b48a-ffffffff8115b4dd: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81163840-ffffffff81163b44: cgroup_apply_control_enable (STB_LOCAL)
ffffffff811670d8-ffffffff8116712c: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174a90)
Location: kernel/cgroup/cgroup.c:3044
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
**Symbols:**

```
ffffffff81174a90-ffffffff81174be4: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171750)
Location: kernel/cgroup/cgroup.c:3040
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
**Symbols:**

```
ffffffff81171750-ffffffff811718ad: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172380)
Location: kernel/cgroup/cgroup.c:3053
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
**Symbols:**

```
ffffffff81172380-ffffffff811724dd: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3108
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
**Symbols:**

```
ffffffff81198e70-ffffffff81199053: cgroup_apply_control_enable (STB_LOCAL)
ffffffff81cb2f38-ffffffff81cb2f5f: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3119
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
**Symbols:**

```
ffffffff811c9250-ffffffff811c9454: cgroup_apply_control_enable (STB_LOCAL)
ffffffff81e63d1d-ffffffff81e63d44: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3224
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
**Symbols:**

```
ffffffff8120c0a0-ffffffff8120c2a3: cgroup_apply_control_enable (STB_LOCAL)
ffffffff8205c1c7-ffffffff8205c1ee: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3193
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
**Symbols:**

```
ffffffff812216b0-ffffffff812218b3: cgroup_apply_control_enable (STB_LOCAL)
ffffffff820da9bd-ffffffff820da9e4: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
**Symbols:**

```
ffffffff812393a0-ffffffff812395a3: cgroup_apply_control_enable (STB_LOCAL)
ffffffff821b663b-ffffffff821b6662: cgroup_apply_control_enable.cold (STB_LOCAL)
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
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d5018)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffff8000101d5018-ffff8000101d5330: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0417b80)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
c0417b80-c0417eb0: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002404b0)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
c0000000002404b0-c0000000002408f8: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014e39a)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffe00014e39a-ffffffe00014e656: cgroup_apply_control_enable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff8115be60-ffffffff8115c164: cgroup_apply_control_enable (STB_LOCAL)
ffffffff8115f6f8-ffffffff8115f74c: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff8114f150-ffffffff8114f454: cgroup_apply_control_enable (STB_LOCAL)
ffffffff81152988-ffffffff811529dc: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81159c30-ffffffff81159f34: cgroup_apply_control_enable (STB_LOCAL)
ffffffff8115d4c8-ffffffff8115d51c: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cgroup_apply_control_enable(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81166ca0-ffffffff81166fa4: cgroup_apply_control_enable (STB_LOCAL)
ffffffff8116a6fc-ffffffff8116a750: cgroup_apply_control_enable.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
