# Function: <code>fib_select_default</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179e0c0)
Location: net/ipv4/fib_semantics.c:1424
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8179e0c0-ffffffff8179e2c8: fib_select_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8180bc00)
Location: net/ipv4/fib_semantics.c:1436
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8180bc00-ffffffff8180be08: fib_select_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183cd20)
Location: net/ipv4/fib_semantics.c:1440
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8183cd20-ffffffff8183cf28: fib_select_default (STB_GLOBAL)
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
In net/ipv4/fib_semantics.c (ffffffff8185e9b9)
Location: net/ipv4/fib_semantics.c:1542
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffff818dea19)
Location: net/ipv4/fib_semantics.c:1583
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffff81935599)
Location: net/ipv4/fib_semantics.c:1546
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffff81964f9b)
Location: net/ipv4/fib_semantics.c:1583
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819cadcc)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffff81a019bc)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aedaa0)
Location: net/ipv4/fib_semantics.c:2007
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81aedaa0-ffffffff81aeddd3: fib_select_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afaa00)
Location: net/ipv4/fib_semantics.c:2006
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81afaa00-ffffffff81afad33: fib_select_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae5fb0)
Location: net/ipv4/fib_semantics.c:2009
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81ae5fb0-ffffffff81ae62e8: fib_select_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2052
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81ba5a70-ffffffff81ba5e52: fib_select_default (STB_LOCAL)
ffffffff81d3c9ea-ffffffff81d3cae2: fib_select_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2039
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81d38700-ffffffff81d38b0f: fib_select_default (STB_LOCAL)
ffffffff81f092b8-ffffffff81f0938a: fib_select_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2045
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81f00ca0-ffffffff81f010af: fib_select_default (STB_LOCAL)
ffffffff820b0ba8-ffffffff820b0c7a: fib_select_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2045
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81f60720-ffffffff81f60b1b: fib_select_default (STB_LOCAL)
ffffffff82131e2f-ffffffff82131f01: fib_select_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fib_select_default(const struct flowi4 *flp, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2053
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff82026cf0-ffffffff820270eb: fib_select_default (STB_LOCAL)
ffffffff822137ed-ffffffff822138bf: fib_select_default.cold (STB_LOCAL)
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
In net/ipv4/fib_semantics.c (ffff800010cba008)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (c0dc586c)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (c000000000dd32b0)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffe000810a6e)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffff819a175c)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffff8195b21c)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffff81a0bffc)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
In net/ipv4/fib_semantics.c (ffffffff81a167ec)
Location: net/ipv4/fib_semantics.c:1989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
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
