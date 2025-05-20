# Function: <code>cgroup_sk_alloc_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81121710)
Location: kernel/cgroup.c:6275
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81121710-ffffffff81121738: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81129c90)
Location: kernel/cgroup.c:6304
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81129c90-ffffffff81129cb8: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81128a50)
Location: kernel/cgroup/cgroup.c:5124
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81128a50-ffffffff81128a79: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811350a0)
Location: kernel/cgroup/cgroup.c:5791
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811350a0-ffffffff811350c9: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:5829
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81143ad8-ffffffff81143af0: cgroup_sk_alloc_disable.cold.49 (STB_LOCAL)
ffffffff811437e0-ffffffff811437f8: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:5932
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8114f5e8-ffffffff8114f600: cgroup_sk_alloc_disable.cold.53 (STB_LOCAL)
ffffffff8114f300-ffffffff8114f318: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6351
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115b51d-ffffffff8115b535: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff8115b140-ffffffff8115b158: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81167146-ffffffff8116715e: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff81166df0-ffffffff81166e08: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6426
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81178872-ffffffff8117888a: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff811784e0-ffffffff811784f8: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81be4743-ffffffff81be475b: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff81175220-ffffffff81175238: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6396
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81bd656b-ffffffff81bd6584: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff81175d80-ffffffff81175d93: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8c40)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffff8000101d8c40-ffff8000101d8c88: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041b97c)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
c041b97c-c041b9bc: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000245fe0)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
c000000000245fe0-c000000000246038: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151bb4)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffe000151bb4-ffffffe000151bf8: cgroup_sk_alloc_disable (STB_GLOBAL)
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
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115f766-ffffffff8115f77e: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff8115f410-ffffffff8115f428: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811529f6-ffffffff81152a0e: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff811526a0-ffffffff811526b8: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115d536-ffffffff8115d54e: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff8115d1e0-ffffffff8115d1f8: cgroup_sk_alloc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cgroup_sk_alloc_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6366
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8116a76a-ffffffff8116a782: cgroup_sk_alloc_disable.cold (STB_LOCAL)
ffffffff8116a330-ffffffff8116a348: cgroup_sk_alloc_disable (STB_GLOBAL)
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
