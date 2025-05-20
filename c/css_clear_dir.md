# Function: <code>css_clear_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css, struct cgroup *cgrp_override);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81113d00)
Location: kernel/cgroup.c:1439
Inline: False
Direct callers:
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:create_css
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81113d00-ffffffff81113d68: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111bf10)
Location: kernel/cgroup.c:1499
Inline: False
Direct callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8111bf10-ffffffff8111bf7b: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81124250)
Location: kernel/cgroup.c:1504
Inline: False
Direct callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81124250-ffffffff811242bb: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81123800)
Location: kernel/cgroup/cgroup.c:1395
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81123800-ffffffff8112386c: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112f6a0)
Location: kernel/cgroup/cgroup.c:1566
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8112f6a0-ffffffff8112f70c: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113db60)
Location: kernel/cgroup/cgroup.c:1571
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8113db60-ffffffff8113dbfe: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81149550)
Location: kernel/cgroup/cgroup.c:1609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81149550-ffffffff811495ee: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154970)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81154970-ffffffff81154a0e: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811605a0)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff811605a0-ffffffff8116063e: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171b30)
Location: kernel/cgroup/cgroup.c:1640
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81171b30-ffffffff81171bce: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116e7a0)
Location: kernel/cgroup/cgroup.c:1637
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8116e7a0-ffffffff8116e83e: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116f5d0)
Location: kernel/cgroup/cgroup.c:1638
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8116f5d0-ffffffff8116f66d: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811957e0)
Location: kernel/cgroup/cgroup.c:1669
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff811957e0-ffffffff8119587d: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c1ff0)
Location: kernel/cgroup/cgroup.c:1672
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff811c1ff0-ffffffff811c20a9: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812084c0)
Location: kernel/cgroup/cgroup.c:1706
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff812084c0-ffffffff812085a2: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121dc60)
Location: kernel/cgroup/cgroup.c:1700
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8121dc60-ffffffff8121dd42: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812358d0)
Location: kernel/cgroup/cgroup.c:1695
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff812358d0-ffffffff812359b2: css_clear_dir (STB_LOCAL)
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
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d1120)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffff8000101d1120-ffff8000101d11ec: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0412838)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
c0412838-c04128e4: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023bab0)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
c00000000023bab0-c00000000023bbac: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014afce)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffe00014afce-ffffffe00014b076: css_clear_dir (STB_LOCAL)
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
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158bc0)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81158bc0-ffffffff81158c5e: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114bdb0)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8114bdb0-ffffffff8114be4e: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156990)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81156990-ffffffff81156a2e: css_clear_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161d60)
Location: kernel/cgroup/cgroup.c:1650
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81161d60-ffffffff81161dfe: css_clear_dir (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct cgroup *cgrp_override</code>
</li>
</ul>
</details>
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
