# Function: <code>cgroup_freeze</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8115e440)
Location: kernel/cgroup/freezer.c:251
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff8115e440-ffffffff8115e5a2: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8116a060)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff8116a060-ffffffff8116a1c2: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8117bbb0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff8117bbb0-ffffffff8117bd12: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81178a00)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff81178a00-ffffffff81178b4e: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81179570)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff81179570-ffffffff811796be: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff81cb31ee-ffffffff81cb3203: cgroup_freeze.cold (STB_LOCAL)
ffffffff811a0e80-ffffffff811a0fd8: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff81e63ff3-ffffffff81e64008: cgroup_freeze.cold (STB_LOCAL)
ffffffff811d16a0-ffffffff811d182b: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff8205c415-ffffffff8205c42a: cgroup_freeze.cold (STB_LOCAL)
ffffffff81215280-ffffffff81215418: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff820dac28-ffffffff820dac3d: cgroup_freeze.cold (STB_LOCAL)
ffffffff8122abb0-ffffffff8122ad48: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff821b68bb-ffffffff821b68d0: cgroup_freeze.cold (STB_LOCAL)
ffffffff81242b70-ffffffff81242d08: cgroup_freeze (STB_GLOBAL)
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
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffff8000101dda28)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffff8000101dda28-ffff8000101ddc10: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (c041f5e0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
c041f5e0-c041fa94: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (c00000000024b7c0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
c00000000024b7c0-c00000000024b9f0: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffe000155314)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffe000155314-ffffffe00015547e: cgroup_freeze (STB_GLOBAL)
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
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81162680)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff81162680-ffffffff811627e2: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811558d0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff811558d0-ffffffff81155a32: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81160450)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff81160450-ffffffff811605b2: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup *cgrp, bool freeze);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8116d7b0)
Location: kernel/cgroup/freezer.c:260
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
```
**Symbols:**

```
ffffffff8116d7b0-ffffffff8116d927: cgroup_freeze (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
