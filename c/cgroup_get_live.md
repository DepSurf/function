# Function: <code>cgroup_get_live</code>

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
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81122e00)
Location: kernel/cgroup/cgroup.c:444
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81122e00-ffffffff81122e30: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112ea90)
Location: kernel/cgroup/cgroup.c:552
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff8112ea90-ffffffff8112eac0: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113d0b0)
Location: kernel/cgroup/cgroup.c:555
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff8113d0b0-ffffffff8113d0e0: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811486c0)
Location: kernel/cgroup/cgroup.c:589
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff811486c0-ffffffff811486f0: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81153ef0)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
ffffffff81153ef0-ffffffff81153f20: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115fb40)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
ffffffff8115fb40-ffffffff8115fb70: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811731ef)
Location: kernel/cgroup/cgroup.c:584
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:link_css_set
```
**Symbols:**

```
ffffffff8116fbc0-ffffffff8116fbf0: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116c8c0)
Location: kernel/cgroup/cgroup.c:581
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:link_css_set
```
**Symbols:**

```
ffffffff8116c8c0-ffffffff8116c8f7: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116d520)
Location: kernel/cgroup/cgroup.c:581
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff8116d520-ffffffff8116d557: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119a236)
Location: kernel/cgroup/cgroup.c:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
```
**Symbols:**

```
ffffffff811930b0-ffffffff811930e7: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811ca315)
Location: kernel/cgroup/cgroup.c:613
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:link_css_set
```
**Symbols:**

```
ffffffff811c35f0-ffffffff811c3649: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120d4c4)
Location: kernel/cgroup/cgroup.c:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:link_css_set
```
**Symbols:**

```
ffffffff812056f0-ffffffff81205749: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81222eb4)
Location: kernel/cgroup/cgroup.c:617
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:link_css_set
```
**Symbols:**

```
ffffffff8121b160-ffffffff8121b1b9: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123aba4)
Location: kernel/cgroup/cgroup.c:597
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:link_css_set
```
**Symbols:**

```
ffffffff81232f90-ffffffff81232fe9: cgroup_get_live (STB_LOCAL)
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
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d0a80)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
ffff8000101d0a80-ffff8000101d0ad0: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041442c)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
c041442c-c04144dc: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023aff0)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:link_css_set
```
**Symbols:**

```
c00000000023aff0-c00000000023b08c: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014a824)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
ffffffe00014a824-ffffffe00014a898: cgroup_get_live (STB_LOCAL)
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
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158160)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
ffffffff81158160-ffffffff81158190: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114b480)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
ffffffff8114b480-ffffffff8114b4b0: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155f30)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
ffffffff81155f30-ffffffff81155f60: cgroup_get_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811637a0)
Location: kernel/cgroup/cgroup.c:591
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
**Symbols:**

```
ffffffff811637a0-ffffffff811637e4: cgroup_get_live (STB_LOCAL)
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
