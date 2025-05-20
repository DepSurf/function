# Function: <code>ghes_edac_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:64
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:64
Inline: True
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
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:64
Inline: True
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
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:70
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff817d3860)
Location: drivers/edac/ghes_edac.c:430
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff817d3860-ffffffff817d3ae5: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:436
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8181c841-ffffffff8181c934: ghes_edac_register.cold.2 (STB_LOCAL)
ffffffff8181c640-ffffffff8181c7e1: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:459
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff818481b1-ffffffff818482a5: ghes_edac_register.cold.3 (STB_LOCAL)
ffffffff81847fb0-ffffffff81848157: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:457
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8188b026-ffffffff8188b11a: ghes_edac_register.cold (STB_LOCAL)
ffffffff8188ae30-ffffffff8188afd0: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:474
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff818bd0f3-ffffffff818bd1fd: ghes_edac_register.cold (STB_LOCAL)
ffffffff818bce10-ffffffff818bd01b: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:455
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8198d75e-ffffffff8198d877: ghes_edac_register.cold (STB_LOCAL)
ffffffff8198d460-ffffffff8198d67e: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:508
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81c28d78-ffffffff81c28e94: ghes_edac_register.cold (STB_LOCAL)
ffffffff81991030-ffffffff8199133f: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:508
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81c1af64-ffffffff81c1b07d: ghes_edac_register.cold (STB_LOCAL)
ffffffff819755a0-ffffffff819758a2: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:508
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81d2ae94-ffffffff81d2afe4: ghes_edac_register.cold (STB_LOCAL)
ffffffff81a1e2a0-ffffffff81a1e5bf: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:387
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81ef702d-ffffffff81ef7180: ghes_edac_register.cold (STB_LOCAL)
ffffffff81b869d0-ffffffff81b86d27: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:388
Inline: True
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_init
```
**Symbols:**

```
ffffffff81d259d0-ffffffff81d25dcf: ghes_edac_register.isra.0 (STB_LOCAL)
ffffffff820a8978-ffffffff820a898d: ghes_edac_register.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:388
Inline: True
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_init
```
**Symbols:**

```
ffffffff81d8ebf0-ffffffff81d8eff8: ghes_edac_register.isra.0 (STB_LOCAL)
ffffffff82129b71-ffffffff82129b86: ghes_edac_register.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:388
Inline: True
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_init
```
**Symbols:**

```
ffffffff81e46500-ffffffff81e46908: ghes_edac_register.isra.0 (STB_LOCAL)
ffffffff8220b8ba-ffffffff8220b8cf: ghes_edac_register.isra.0.cold (STB_LOCAL)
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
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffff800010b15280)
Location: drivers/edac/ghes_edac.c:474
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffff800010b15280-ffff800010b15508: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:474
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff818b25a3-ffffffff818b26ad: ghes_edac_register.cold (STB_LOCAL)
ffffffff818b22c0-ffffffff818b24cb: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ghes_edac_register(struct ghes *ghes, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:474
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff818ce853-ffffffff818ce95d: ghes_edac_register.cold (STB_LOCAL)
ffffffff818ce570-ffffffff818ce77b: ghes_edac_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
