# Function: <code>clk_core_free_parent_map</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162dd70)
Location: drivers/clk/clk.c:3572
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff8162dd70-ffffffff8162ddde: clk_core_free_parent_map.isra.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8164fa80)
Location: drivers/clk/clk.c:3621
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff8164fa80-ffffffff8164faee: clk_core_free_parent_map.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fc810)
Location: drivers/clk/clk.c:3711
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff816fc810-ffffffff816fc880: clk_core_free_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81719710)
Location: drivers/clk/clk.c:3780
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff81719710-ffffffff81719780: clk_core_free_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816faa20)
Location: drivers/clk/clk.c:3789
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff816faa20-ffffffff816faa90: clk_core_free_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81774eb0)
Location: drivers/clk/clk.c:3817
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff81774eb0-ffffffff81774f20: clk_core_free_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818aba80)
Location: drivers/clk/clk.c:3890
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff818aba80-ffffffff818abb04: clk_core_free_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f7190)
Location: drivers/clk/clk.c:4079
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff819f7190-ffffffff819f7214: clk_core_free_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3f390)
Location: drivers/clk/clk.c:4131
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff81a3f390-ffffffff81a3f414: clk_core_free_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8acc0)
Location: drivers/clk/clk.c:4177
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff81a8acc0-ffffffff81a8ad44: clk_core_free_parent_map (STB_LOCAL)
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
In drivers/clk/clk.c (ffff8000107bea00)
Location: drivers/clk/clk.c:3621
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffff8000107bea00-ffff8000107bea84: clk_core_free_parent_map.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clk_core_free_parent_map(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e8bf0)
Location: drivers/clk/clk.c:3621
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
c08e8bf0-c08e8c58: clk_core_free_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050de2e)
Location: drivers/clk/clk.c:3621
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffe00050de2e-ffffffe00050deb2: clk_core_free_parent_map.isra.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81615ae0)
Location: drivers/clk/clk.c:3621
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff81615ae0-ffffffff81615b4e: clk_core_free_parent_map.isra.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8160a010)
Location: drivers/clk/clk.c:3621
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff8160a010-ffffffff8160a07e: clk_core_free_parent_map.isra.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816438c0)
Location: drivers/clk/clk.c:3621
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff816438c0-ffffffff8164392e: clk_core_free_parent_map.isra.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8165dd00)
Location: drivers/clk/clk.c:3621
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff8165dd00-ffffffff8165dd6e: clk_core_free_parent_map.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
