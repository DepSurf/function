# Function: <code>cgroup_finalize_control</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111eacb)
Location: kernel/cgroup.c:3360
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:rebind_subsystems
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
In kernel/cgroup.c (ffffffff81126e5b)
Location: kernel/cgroup.c:3369
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:rebind_subsystems
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
In kernel/cgroup/cgroup.c (ffffffff81127154)
Location: kernel/cgroup/cgroup.c:2884
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
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
In kernel/cgroup/cgroup.c (ffffffff81133a17)
Location: kernel/cgroup/cgroup.c:3019
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
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
In kernel/cgroup/cgroup.c (ffffffff8114210e)
Location: kernel/cgroup/cgroup.c:3037
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114cbb1)
Location: kernel/cgroup/cgroup.c:3082
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8114c9c0-ffffffff8114ca2c: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811587bc)
Location: kernel/cgroup/cgroup.c:3222
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff811585c0-ffffffff81158632: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116441a)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81164230-ffffffff811642a2: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117545e)
Location: kernel/cgroup/cgroup.c:3164
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81175110-ffffffff8117519b: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117210e)
Location: kernel/cgroup/cgroup.c:3160
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81171dc0-ffffffff81171e4b: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172bf6)
Location: kernel/cgroup/cgroup.c:3173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff811729e0-ffffffff81172a6b: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81199ba8)
Location: kernel/cgroup/cgroup.c:3228
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff811995b0-ffffffff8119963b: cgroup_finalize_control (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff811cb19e)
Location: kernel/cgroup/cgroup.c:3239
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
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
In kernel/cgroup/cgroup.c (ffffffff8120e5ce)
Location: kernel/cgroup/cgroup.c:3340
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
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
In kernel/cgroup/cgroup.c (ffffffff81223fce)
Location: kernel/cgroup/cgroup.c:3309
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
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
In kernel/cgroup/cgroup.c (ffffffff8123bcae)
Location: kernel/cgroup/cgroup.c:3318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d5d04)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffff8000101d5b00-ffff8000101d5b84: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041880c)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
c04185f8-c0418668: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002416d4)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
c000000000241410-c0000000002414c0: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014ef4c)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffe00014ed86-ffffffe00014edf6: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115ca3a)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8115c850-ffffffff8115c8c2: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114fd2a)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8114fb40-ffffffff8114fbb2: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a80a)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8115a620-ffffffff8115a692: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cgroup_finalize_control(struct cgroup *cgrp, int ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116786a)
Location: kernel/cgroup/cgroup.c:3223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81167680-ffffffff811676f2: cgroup_finalize_control (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
