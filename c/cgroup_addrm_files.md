# Function: <code>cgroup_addrm_files</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811139b0)
Location: kernel/cgroup.c:3493
Inline: False
Direct callers:
  - kernel/cgroup.c:css_clear_dir
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:cgroup_apply_cftypes
```
**Symbols:**

```
ffffffff811139b0-ffffffff81113cf5: cgroup_addrm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111bbd0)
Location: kernel/cgroup.c:3680
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff8111bbd0-ffffffff8111bf05: cgroup_addrm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81123f10)
Location: kernel/cgroup.c:3691
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:css_populate_dir
  - kernel/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81123f10-ffffffff81124245: cgroup_addrm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811234d0)
Location: kernel/cgroup/cgroup.c:3198
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff811234d0-ffffffff811237f5: cgroup_addrm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112f370)
Location: kernel/cgroup/cgroup.c:3568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff8112f370-ffffffff8112f695: cgroup_addrm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3596
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff8113d820-ffffffff8113db5a: cgroup_addrm_files (STB_LOCAL)
ffffffff81143a41-ffffffff81143a65: cgroup_addrm_files.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3659
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81149210-ffffffff8114954f: cgroup_addrm_files (STB_LOCAL)
ffffffff8114f551-ffffffff8114f575: cgroup_addrm_files.cold.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3915
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81154640-ffffffff81154961: cgroup_addrm_files (STB_LOCAL)
ffffffff8115b45e-ffffffff8115b48a: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81160270-ffffffff81160591: cgroup_addrm_files (STB_LOCAL)
ffffffff811670ac-ffffffff811670d8: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3858
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81171960-ffffffff81171b22: cgroup_addrm_files (STB_LOCAL)
ffffffff81178835-ffffffff81178858: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3859
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff8116e5d0-ffffffff8116e793: cgroup_addrm_files (STB_LOCAL)
ffffffff81be46ee-ffffffff81be4711: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3872
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff8116f2b0-ffffffff8116f5d0: cgroup_addrm_files (STB_LOCAL)
ffffffff81bd650f-ffffffff81bd653b: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4042
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81195470-ffffffff811957df: cgroup_addrm_files (STB_LOCAL)
ffffffff81cb2e81-ffffffff81cb2ece: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4053
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff811c1bd0-ffffffff811c1fef: cgroup_addrm_files (STB_LOCAL)
ffffffff81e63bd1-ffffffff81e63be5: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4222
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81204230-ffffffff81204614: cgroup_addrm_files (STB_LOCAL)
ffffffff8205c0ab-ffffffff8205c0c0: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4199
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81219780-ffffffff81219b85: cgroup_addrm_files (STB_LOCAL)
ffffffff820da8a2-ffffffff820da8b6: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4232
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff812312a0-ffffffff812316b3: cgroup_addrm_files (STB_LOCAL)
ffffffff821b650b-ffffffff821b6520: cgroup_addrm_files.cold (STB_LOCAL)
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
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d0e18)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffff8000101d0e18-ffff8000101d1120: cgroup_addrm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04124c8)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
c04124c8-c0412838: cgroup_addrm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023b5c0)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
c00000000023b5c0-c00000000023baac: cgroup_addrm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014acd2)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffe00014acd2-ffffffe00014afce: cgroup_addrm_files (STB_LOCAL)
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
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81158890-ffffffff81158bb1: cgroup_addrm_files (STB_LOCAL)
ffffffff8115f6cc-ffffffff8115f6f8: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff8114ba90-ffffffff8114bda5: cgroup_addrm_files (STB_LOCAL)
ffffffff8115295c-ffffffff81152988: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81156660-ffffffff81156981: cgroup_addrm_files (STB_LOCAL)
ffffffff8115d49c-ffffffff8115d4c8: cgroup_addrm_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cfts, bool is_add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
```
**Symbols:**

```
ffffffff81161a60-ffffffff81161d5b: cgroup_addrm_files (STB_LOCAL)
ffffffff8116a6cc-ffffffff8116a6fc: cgroup_addrm_files.cold (STB_LOCAL)
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
