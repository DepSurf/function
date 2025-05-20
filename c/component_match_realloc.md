# Function: <code>component_match_realloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct component_match *component_match_realloc(struct device *dev, struct component_match *match, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff815457c0)
Location: drivers/base/component.c:232
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff815457c0-ffffffff8154587e: component_match_realloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81597bb7)
Location: drivers/base/component.c:218
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
Direct callers:
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff81597a70-ffffffff81597b03: component_match_realloc.isra.3.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff815c5707)
Location: drivers/base/component.c:218
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
Direct callers:
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff815c55c0-ffffffff815c5653: component_match_realloc.isra.5.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff815da697)
Location: drivers/base/component.c:218
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
Direct callers:
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff815da550-ffffffff815da5e1: component_match_realloc.isra.5.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81641427)
Location: drivers/base/component.c:218
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
Direct callers:
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff816412e0-ffffffff81641371: component_match_realloc.isra.5.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff8167c5fd)
Location: drivers/base/component.c:291
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:component_match_add_release
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff8167c440-ffffffff8167c4c8: component_match_realloc.isra.7.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff8169c10d)
Location: drivers/base/component.c:281
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:component_match_add_release
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff8169bf50-ffffffff8169bfd8: component_match_realloc.isra.7.part.8 (STB_LOCAL)
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
In drivers/base/component.c (ffffffff816d4c5d)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff816d4a20-ffffffff816d4aad: component_match_realloc.isra.0.part.0 (STB_LOCAL)
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
In drivers/base/component.c (ffffffff816f8b2d)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff816f88f0-ffffffff816f897d: component_match_realloc.isra.0.part.0 (STB_LOCAL)
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
In drivers/base/component.c (ffffffff817b152d)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff817b12f0-ffffffff817b137d: component_match_realloc.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff817c5e7d)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff817c5c40-ffffffff817c5ccd: component_match_realloc.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff817a901d)
Location: drivers/base/component.c:310
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff817a8d30-ffffffff817a8db8: component_match_realloc.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff8183227d)
Location: drivers/base/component.c:306
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff81831f10-ffffffff81831f98: component_match_realloc.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int component_match_realloc(struct component_match *match, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81973570)
Location: drivers/base/component.c:359
Inline: False
Direct callers:
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff81973570-ffffffff81973609: component_match_realloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int component_match_realloc(struct component_match *match, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81adea10)
Location: drivers/base/component.c:359
Inline: False
Direct callers:
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff81adea10-ffffffff81adeaa9: component_match_realloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int component_match_realloc(struct component_match *match, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81b2cc90)
Location: drivers/base/component.c:359
Inline: False
Direct callers:
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff81b2cc90-ffffffff81b2cd29: component_match_realloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int component_match_realloc(struct component_match *match, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81b84430)
Location: drivers/base/component.c:359
Inline: False
Direct callers:
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff81b84430-ffffffff81b844c9: component_match_realloc (STB_LOCAL)
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
In drivers/base/component.c (ffff8000108e2958)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffff8000108e26a8-ffff8000108e2744: component_match_realloc.isra.0.part.0 (STB_LOCAL)
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
In drivers/base/component.c (c09d15e0)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
c09d13bc-c09d1440: component_match_realloc.part.0 (STB_LOCAL)
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
In drivers/base/component.c (c00000000097753c)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
c0000000009771d0-c0000000009772cc: component_match_realloc.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffe000577f12)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffe000577cac-ffffffe000577d58: component_match_realloc.isra.0.part.0 (STB_LOCAL)
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
In drivers/base/component.c (ffffffff816be31d)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff816be0e0-ffffffff816be16d: component_match_realloc.isra.0.part.0 (STB_LOCAL)
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
In drivers/base/component.c (ffffffff816995cd)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff81699390-ffffffff8169941d: component_match_realloc.isra.0.part.0 (STB_LOCAL)
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
In drivers/base/component.c (ffffffff816ec7ed)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff816ec5b0-ffffffff816ec63d: component_match_realloc.isra.0.part.0 (STB_LOCAL)
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
In drivers/base/component.c (ffffffff8170702d)
Location: drivers/base/component.c:313
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:__component_match_add
```
**Symbols:**

```
ffffffff81706df0-ffffffff81706e7d: component_match_realloc.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
