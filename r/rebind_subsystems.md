# Function: <code>rebind_subsystems</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, long unsigned int ss_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81113ea0)
Location: kernel/cgroup.c:1489
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_remount
  - kernel/cgroup.c:cgroup_remount
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff81113ea0-ffffffff811143a4: rebind_subsystems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111ec70)
Location: kernel/cgroup.c:1557
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:cgroup_remount
  - kernel/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff8111ec70-ffffffff8111eff3: rebind_subsystems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81127000)
Location: kernel/cgroup.c:1562
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:cgroup_remount
  - kernel/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff81127000-ffffffff81127383: rebind_subsystems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81126540)
Location: kernel/cgroup/cgroup.c:1453
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
**Symbols:**

```
ffffffff81126540-ffffffff81126939: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811328b0)
Location: kernel/cgroup/cgroup.c:1624
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
**Symbols:**

```
ffffffff811328b0-ffffffff81132c3c: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1640
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
**Symbols:**

```
ffffffff81143abe-ffffffff81143ad8: rebind_subsystems.cold.48 (STB_LOCAL)
ffffffff81140f80-ffffffff811412e6: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1678
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
**Symbols:**

```
ffffffff8114f5ce-ffffffff8114f5e8: rebind_subsystems.cold.52 (STB_LOCAL)
ffffffff8114ca30-ffffffff8114cd96: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8115b4dd-ffffffff8115b50a: rebind_subsystems.cold (STB_LOCAL)
ffffffff81158640-ffffffff81158995: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8116712c-ffffffff81167146: rebind_subsystems.cold (STB_LOCAL)
ffffffff811642b0-ffffffff811645fa: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1709
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81178858-ffffffff81178872: rebind_subsystems.cold (STB_LOCAL)
ffffffff811752f0-ffffffff81175633: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1706
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81be4729-ffffffff81be4743: rebind_subsystems.cold (STB_LOCAL)
ffffffff81171fa0-ffffffff811722e5: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1707
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81bd6553-ffffffff81bd656b: rebind_subsystems.cold (STB_LOCAL)
ffffffff81172a70-ffffffff81172e2b: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1738
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81cb2f80-ffffffff81cb300f: rebind_subsystems.cold (STB_LOCAL)
ffffffff81199640-ffffffff81199ca4: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1741
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81e63d65-ffffffff81e63def: rebind_subsystems.cold (STB_LOCAL)
ffffffff811c9800-ffffffff811c9e50: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1787
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8205c20f-ffffffff8205c27f: rebind_subsystems.cold (STB_LOCAL)
ffffffff8120c940-ffffffff8120cfd6: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1781
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff820daa05-ffffffff820daa99: rebind_subsystems.cold (STB_LOCAL)
ffffffff81221f50-ffffffff812229ca: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1778
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff821b6683-ffffffff821b6717: rebind_subsystems.cold (STB_LOCAL)
ffffffff81239c40-ffffffff8123a6ba: rebind_subsystems (STB_GLOBAL)
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
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d5b88)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffff8000101d5b88-ffff8000101d5f1c: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0418668)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
c0418668-c0418b20: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002414c0)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
c0000000002414c0-c000000000241984: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014edf6)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffe00014edf6-ffffffe00014f194: rebind_subsystems (STB_GLOBAL)
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
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8115f74c-ffffffff8115f766: rebind_subsystems.cold (STB_LOCAL)
ffffffff8115c8d0-ffffffff8115cc1a: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff811529dc-ffffffff811529f6: rebind_subsystems.cold (STB_LOCAL)
ffffffff8114fbc0-ffffffff8114ff04: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8115d51c-ffffffff8115d536: rebind_subsystems.cold (STB_LOCAL)
ffffffff8115a6a0-ffffffff8115a9ea: rebind_subsystems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rebind_subsystems(struct cgroup_root *dst_root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1719
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8116a750-ffffffff8116a76a: rebind_subsystems.cold (STB_LOCAL)
ffffffff81167700-ffffffff81167a41: rebind_subsystems (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>long unsigned int ss_mask</code> ➡️ <code>u16 ss_mask</code>
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
