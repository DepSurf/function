# Function: <code>pnp_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/core.c (ffffffff814b6e20)
Location: drivers/pnp/core.c:33
Inline: False
Direct callers:
  - drivers/pnp/card.c:card_probe
  - drivers/pnp/interface.c:options_show
  - drivers/pnp/interface.c:resources_show
```
**Symbols:**

```
ffffffff814b6e20-ffffffff814b6e50: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/core.c (ffffffff81506830)
Location: drivers/pnp/core.c:33
Inline: False
Direct callers:
  - drivers/pnp/card.c:card_probe
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff81506830-ffffffff81506860: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/core.c (ffffffff8152aa50)
Location: drivers/pnp/core.c:33
Inline: False
Direct callers:
  - drivers/pnp/card.c:card_probe
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff8152aa50-ffffffff8152aa80: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/core.c (ffffffff8153db30)
Location: drivers/pnp/core.c:33
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff8153db30-ffffffff8153db60: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/core.c (ffffffff815a0ba0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff815a0ba0-ffffffff815a0bd0: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff815d8dfd-ffffffff815d8e0e: pnp_alloc.cold.5 (STB_LOCAL)
ffffffff815d8810-ffffffff815d8836: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff815f270d-ffffffff815f271e: pnp_alloc.cold.5 (STB_LOCAL)
ffffffff815f2120-ffffffff815f2146: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff816245af-ffffffff816245c0: pnp_alloc.cold (STB_LOCAL)
ffffffff81624020-ffffffff81624048: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff8164609f-ffffffff816460b0: pnp_alloc.cold (STB_LOCAL)
ffffffff81645b10-ffffffff81645b38: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff816f4d26-ffffffff816f4d37: pnp_alloc.cold (STB_LOCAL)
ffffffff816f4700-ffffffff816f472a: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff81c039a8-ffffffff81c039b9: pnp_alloc.cold (STB_LOCAL)
ffffffff817117c0-ffffffff817117ea: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff81bf533b-ffffffff81bf534c: pnp_alloc.cold (STB_LOCAL)
ffffffff816f2bb0-ffffffff816f2bda: pnp_alloc (STB_GLOBAL)
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
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/core.c (ffff8000107b2bb0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffff8000107b2bb0-ffff8000107b2bfc: pnp_alloc (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff8160c0ff-ffffffff8160c110: pnp_alloc.cold (STB_LOCAL)
ffffffff8160bb70-ffffffff8160bb98: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff8160064f-ffffffff81600660: pnp_alloc.cold (STB_LOCAL)
ffffffff816000c0-ffffffff816000e8: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff81639edf-ffffffff81639ef0: pnp_alloc.cold (STB_LOCAL)
ffffffff81639950-ffffffff81639978: pnp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *pnp_alloc(long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/core.c (0)
Location: drivers/pnp/core.c:34
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
**Symbols:**

```
ffffffff8165422f-ffffffff81654240: pnp_alloc.cold (STB_LOCAL)
ffffffff81653ca0-ffffffff81653cc8: pnp_alloc (STB_GLOBAL)
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
