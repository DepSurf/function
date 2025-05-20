# Function: <code>cgroup_idr_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff811138b0)
Location: kernel/cgroup.c:314
Inline: True
Direct callers:
  - kernel/cgroup.c:create_css
  - kernel/cgroup.c:cgroup_init_subsys
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:cgroup_init
```
**Symbols:**

```
ffffffff811138b0-ffffffff81113912: cgroup_idr_alloc.constprop.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff8111acc0)
Location: kernel/cgroup.c:331
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_init_subsys
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff8111acc0-ffffffff8111ad22: cgroup_idr_alloc.constprop.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff811229f0)
Location: kernel/cgroup.c:334
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_init_subsys
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff811229f0-ffffffff81122a52: cgroup_idr_alloc.constprop.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811227c0)
Location: kernel/cgroup/cgroup.c:289
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff811227c0-ffffffff81122822: cgroup_idr_alloc.constprop.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112e480)
Location: kernel/cgroup/cgroup.c:294
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff8112e480-ffffffff8112e51a: cgroup_idr_alloc.constprop.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113c920)
Location: kernel/cgroup/cgroup.c:297
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff8113c920-ffffffff8113c982: cgroup_idr_alloc.constprop.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81147fe0)
Location: kernel/cgroup/cgroup.c:302
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff81147fe0-ffffffff81148042: cgroup_idr_alloc.constprop.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81153340)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff81153340-ffffffff811533a6: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115ef90)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff8115ef90-ffffffff8115eff6: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170328)
Location: kernel/cgroup/cgroup.c:297
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
**Symbols:**

```
ffffffff8116f210-ffffffff8116f276: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116ce5b)
Location: kernel/cgroup/cgroup.c:294
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
**Symbols:**

```
ffffffff8116bc30-ffffffff8116bc96: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116dabb)
Location: kernel/cgroup/cgroup.c:294
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
**Symbols:**

```
ffffffff8116c6e0-ffffffff8116c746: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81193398)
Location: kernel/cgroup/cgroup.c:318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
**Symbols:**

```
ffffffff811922e0-ffffffff81192346: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c4662)
Location: kernel/cgroup/cgroup.c:319
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
**Symbols:**

```
ffffffff811c23c0-ffffffff811c2459: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff83eb0787)
Location: kernel/cgroup/cgroup.c:324
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
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
In kernel/cgroup/cgroup.c (ffffffff836d5777)
Location: kernel/cgroup/cgroup.c:323
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
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
In kernel/cgroup/cgroup.c (ffffffff83907ae7)
Location: kernel/cgroup/cgroup.c:325
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d19d0)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffff8000101d19d0-ffff8000101d1abc: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (c0413560)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
c0413560-c04135d4: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023a030)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
c00000000023a030-c00000000023a0cc: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014a2a6)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffe00014a2a6-ffffffe00014a322: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811575b0)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff811575b0-ffffffff81157616: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a8d0)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff8114a8d0-ffffffff8114a936: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155380)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff81155380-ffffffff811553e6: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811628a0)
Location: kernel/cgroup/cgroup.c:304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
**Symbols:**

```
ffffffff811628a0-ffffffff81162921: cgroup_idr_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
