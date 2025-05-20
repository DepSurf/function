# Function: <code>padata_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct padata_instance *padata_alloc(struct workqueue_struct *wq, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8118a770)
Location: kernel/padata.c:1036
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff8118a770-ffffffff8118a8de: padata_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct padata_instance *padata_alloc(struct workqueue_struct *wq, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8119d0a0)
Location: kernel/padata.c:973
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff8119d0a0-ffffffff8119d21c: padata_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct padata_instance *padata_alloc(struct workqueue_struct *wq, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811aca40)
Location: kernel/padata.c:961
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff811aca40-ffffffff811acbe4: padata_alloc (STB_GLOBAL)
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
In kernel/padata.c (ffffffff811b3526)
Location: kernel/padata.c:946
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
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
In kernel/padata.c (ffffffff811c7196)
Location: kernel/padata.c:1011
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
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
In kernel/padata.c (ffffffff811e7f56)
Location: kernel/padata.c:1012
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811f8136)
Location: kernel/padata.c:1012
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
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
In kernel/padata.c (0)
Location: kernel/padata.c:1025
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff81210ba0-ffffffff81210d6f: padata_alloc.constprop.0 (STB_LOCAL)
ffffffff81210d8f-ffffffff81210d9b: padata_alloc.constprop.0.cold (STB_LOCAL)
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
In kernel/padata.c (0)
Location: kernel/padata.c:967
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff8121e2e0-ffffffff8121e5cc: padata_alloc.constprop.0 (STB_LOCAL)
ffffffff8121e5e0-ffffffff8121e5ec: padata_alloc.constprop.0.cold (STB_LOCAL)
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
In kernel/padata.c (0)
Location: kernel/padata.c:1057
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff8124a290-ffffffff8124a55c: padata_alloc.constprop.0 (STB_LOCAL)
ffffffff8124a829-ffffffff8124a835: padata_alloc.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct padata_instance *padata_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:982
Inline: False
```
**Symbols:**

```
ffffffff81be6937-ffffffff81be6943: padata_alloc.cold (STB_LOCAL)
ffffffff81254390-ffffffff81254612: padata_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct padata_instance *padata_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:982
Inline: False
```
**Symbols:**

```
ffffffff81bd8638-ffffffff81bd8644: padata_alloc.cold (STB_LOCAL)
ffffffff81258900-ffffffff81258b3f: padata_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct padata_instance *padata_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:969
Inline: False
```
**Symbols:**

```
ffffffff81cb9b74-ffffffff81cb9b80: padata_alloc.cold (STB_LOCAL)
ffffffff81294520-ffffffff8129475f: padata_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct padata_instance *padata_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:969
Inline: False
```
**Symbols:**

```
ffffffff81e6b16d-ffffffff81e6b179: padata_alloc.cold (STB_LOCAL)
ffffffff812ea830-ffffffff812eaa4b: padata_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct padata_instance *padata_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81354740)
Location: kernel/padata.c:982
Inline: False
```
**Symbols:**

```
ffffffff81354740-ffffffff81354971: padata_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct padata_instance *padata_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:982
Inline: False
```
**Symbols:**

```
ffffffff820e16f5-ffffffff820e1710: padata_alloc.cold (STB_LOCAL)
ffffffff81385a70-ffffffff81385d07: padata_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct padata_instance *padata_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:982
Inline: False
```
**Symbols:**

```
ffffffff821be158-ffffffff821be173: padata_alloc.cold (STB_LOCAL)
ffffffff813aef00-ffffffff813af1c6: padata_alloc (STB_GLOBAL)
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
In kernel/padata.c (ffff8000102aa2a0)
Location: kernel/padata.c:967
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffff8000102aa2a0-ffff8000102aa488: padata_alloc.constprop.0 (STB_LOCAL)
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
In kernel/padata.c (c04d8b84)
Location: kernel/padata.c:967
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
c04d8b84-c04d8d08: padata_alloc.constprop.0 (STB_LOCAL)
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
In kernel/padata.c (c00000000035e1e0)
Location: kernel/padata.c:967
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
c00000000035e1e0-c00000000035e468: padata_alloc.constprop.0 (STB_LOCAL)
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
In kernel/padata.c (ffffffe0001d2c18)
Location: kernel/padata.c:967
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
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
In kernel/padata.c (0)
Location: kernel/padata.c:967
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff81216930-ffffffff81216c1c: padata_alloc.constprop.0 (STB_LOCAL)
ffffffff81216c30-ffffffff81216c3c: padata_alloc.constprop.0.cold (STB_LOCAL)
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
In kernel/padata.c (0)
Location: kernel/padata.c:967
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff81209690-ffffffff8120997c: padata_alloc.constprop.0 (STB_LOCAL)
ffffffff81209990-ffffffff8120999c: padata_alloc.constprop.0.cold (STB_LOCAL)
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
In kernel/padata.c (0)
Location: kernel/padata.c:967
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff812146d0-ffffffff812149bc: padata_alloc.constprop.0 (STB_LOCAL)
ffffffff812149d0-ffffffff812149dc: padata_alloc.constprop.0.cold (STB_LOCAL)
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
In kernel/padata.c (0)
Location: kernel/padata.c:967
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff81223680-ffffffff8122396c: padata_alloc.constprop.0 (STB_LOCAL)
ffffffff81223980-ffffffff8122398c: padata_alloc.constprop.0.cold (STB_LOCAL)
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
