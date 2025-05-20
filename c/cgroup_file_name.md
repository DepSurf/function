# Function: <code>cgroup_file_name</code>

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
In kernel/cgroup.c (ffffffff811137a0)
Location: kernel/cgroup.c:1247
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff811137a0-ffffffff8111380e: cgroup_file_name.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811198c0)
Location: kernel/cgroup.c:1321
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff811198c0-ffffffff81119932: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811213a0)
Location: kernel/cgroup.c:1326
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff811213a0-ffffffff81121412: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81121aa0)
Location: kernel/cgroup/cgroup.c:1218
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81121aa0-ffffffff81121b12: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112d290)
Location: kernel/cgroup/cgroup.c:1389
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff8112d290-ffffffff8112d302: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113bf10)
Location: kernel/cgroup/cgroup.c:1392
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff8113bf10-ffffffff8113bf82: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81147790)
Location: kernel/cgroup/cgroup.c:1427
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81147790-ffffffff81147819: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81152a10)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81152a10-ffffffff81152a9c: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e660)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff8115e660-ffffffff8115e6ec: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116ea00)
Location: kernel/cgroup/cgroup.c:1458
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_add_file
```
**Symbols:**

```
ffffffff8116ea00-ffffffff8116ea93: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1455
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_add_file
```
**Symbols:**

```
ffffffff8116b400-ffffffff8116b4c4: cgroup_file_name (STB_LOCAL)
ffffffff81be46b2-ffffffff81be46be: cgroup_file_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1456
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff8116bf80-ffffffff8116c041: cgroup_file_name (STB_LOCAL)
ffffffff81bd64d3-ffffffff81bd64df: cgroup_file_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1487
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81191ba0-ffffffff81191c61: cgroup_file_name (STB_LOCAL)
ffffffff81cb2dc0-ffffffff81cb2dcc: cgroup_file_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1490
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff811c1550-ffffffff811c1632: cgroup_file_name (STB_LOCAL)
ffffffff81e63bc5-ffffffff81e63bd1: cgroup_file_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81203b10)
Location: kernel/cgroup/cgroup.c:1524
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81203b10-ffffffff81203bf8: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81219070)
Location: kernel/cgroup/cgroup.c:1518
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81219070-ffffffff81219158: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81230c30)
Location: kernel/cgroup/cgroup.c:1513
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81230c30-ffffffff81230d18: cgroup_file_name (STB_LOCAL)
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
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101ceef0)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffff8000101ceef0-ffff8000101cefac: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0412378)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
c0412378-c041242c: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000238fa0)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
c000000000238fa0-c0000000002390a0: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe0001496c6)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffe0001496c6-ffffffe00014977c: cgroup_file_name (STB_LOCAL)
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
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156c80)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81156c80-ffffffff81156d0c: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81149fa0)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81149fa0-ffffffff8114a02c: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154a50)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81154a50-ffffffff81154adc: cgroup_file_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *cgroup_file_name(struct cgroup *cgrp, const struct cftype *cft, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161950)
Location: kernel/cgroup/cgroup.c:1468
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff81161950-ffffffff811619dc: cgroup_file_name (STB_LOCAL)
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
