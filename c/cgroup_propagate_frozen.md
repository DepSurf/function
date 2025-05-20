# Function: <code>cgroup_propagate_frozen</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup *cgrp, bool frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8117b4a0)
Location: kernel/cgroup/freezer.c:14
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff8117b4a0-ffffffff8117b67d: cgroup_propagate_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup *cgrp, bool frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81178340)
Location: kernel/cgroup/freezer.c:14
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81178340-ffffffff811784fb: cgroup_propagate_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup *cgrp, bool frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81178eb0)
Location: kernel/cgroup/freezer.c:14
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81178eb0-ffffffff8117906b: cgroup_propagate_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup *cgrp, bool frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811a07e0)
Location: kernel/cgroup/freezer.c:14
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff811a07e0-ffffffff811a098f: cgroup_propagate_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup *cgrp, bool frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811d0f40)
Location: kernel/cgroup/freezer.c:14
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff811d0f40-ffffffff811d1134: cgroup_propagate_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup *cgrp, bool frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81214ac0)
Location: kernel/cgroup/freezer.c:14
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81214ac0-ffffffff81214cb2: cgroup_propagate_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup *cgrp, bool frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8122a3e0)
Location: kernel/cgroup/freezer.c:14
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff8122a3e0-ffffffff8122a5e9: cgroup_propagate_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup *cgrp, bool frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff812423a0)
Location: kernel/cgroup/freezer.c:14
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff812423a0-ffffffff812425a9: cgroup_propagate_frozen (STB_LOCAL)
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
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/cgroup/freezer.c (ffffffe000154b30)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:14
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
