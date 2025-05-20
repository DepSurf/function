# Function: <code>cgroup_rm_cftypes_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811163e0)
Location: kernel/cgroup.c:3607
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff811163e0-ffffffff8111643e: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111cdf0)
Location: kernel/cgroup.c:3794
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff8111cdf0-ffffffff8111ce4e: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81125120)
Location: kernel/cgroup.c:3805
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff81125120-ffffffff8112517e: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811261a0)
Location: kernel/cgroup/cgroup.c:3312
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff811261a0-ffffffff811261fa: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811324a0)
Location: kernel/cgroup/cgroup.c:3681
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff811324a0-ffffffff811324fa: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81140b70)
Location: kernel/cgroup/cgroup.c:3709
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff81140b70-ffffffff81140bca: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c5f0)
Location: kernel/cgroup/cgroup.c:3773
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff8114c5f0-ffffffff8114c64a: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811581e0)
Location: kernel/cgroup/cgroup.c:4029
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff811581e0-ffffffff81158241: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81163e60)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff81163e60-ffffffff81163ec1: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117398a)
Location: kernel/cgroup/cgroup.c:3972
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117068a)
Location: kernel/cgroup/cgroup.c:3973
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811712ba)
Location: kernel/cgroup/cgroup.c:3986
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81197bda)
Location: kernel/cgroup/cgroup.c:4161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
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
In kernel/cgroup/cgroup.c (ffffffff811c7c49)
Location: kernel/cgroup/cgroup.c:4172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
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
In kernel/cgroup/cgroup.c (ffffffff8120abc9)
Location: kernel/cgroup/cgroup.c:4346
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
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
In kernel/cgroup/cgroup.c (ffffffff812201a9)
Location: kernel/cgroup/cgroup.c:4323
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
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
In kernel/cgroup/cgroup.c (ffffffff81237ef9)
Location: kernel/cgroup/cgroup.c:4356
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
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
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d5640)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffff8000101d5640-ffff8000101d56b0: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04181a8)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
c04181a8-c0418210: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000240dc0)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
c000000000240dc0-c000000000240e68: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014e970)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffe00014e970-ffffffe00014e9c6: cgroup_rm_cftypes_locked (STB_LOCAL)
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
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c480)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff8115c480-ffffffff8115c4e1: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f770)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff8114f770-ffffffff8114f7d1: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a250)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff8115a250-ffffffff8115a2b1: cgroup_rm_cftypes_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_rm_cftypes_locked(struct cftype *cfts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811672b0)
Location: kernel/cgroup/cgroup.c:4031
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
```
**Symbols:**

```
ffffffff811672b0-ffffffff81167311: cgroup_rm_cftypes_locked (STB_LOCAL)
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
