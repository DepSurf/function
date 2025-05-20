# Function: <code>_get_opp_count</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181dcb0)
Location: drivers/opp/core.c:303
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8181dcb0-ffffffff8181dcf8: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818499a0)
Location: drivers/opp/core.c:287
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff818499a0-ffffffff818499e8: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188c780)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8188c780-ffffffff8188c7cf: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818be8f0)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff818be8f0-ffffffff818be93f: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198f806)
Location: drivers/opp/core.c:302
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8198fdb0-ffffffff8198fdff: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819937fe)
Location: drivers/opp/core.c:302
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81993d50-ffffffff81993d9f: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8197951a)
Location: drivers/opp/core.c:332
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81978070-ffffffff819780bf: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81a224da)
Location: drivers/opp/core.c:332
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81d2b722-ffffffff81d2b736: _get_opp_count.cold (STB_LOCAL)
ffffffff81a20fc0-ffffffff81a21028: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8b562)
Location: drivers/opp/core.c:357
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81ef7940-ffffffff81ef7954: _get_opp_count.cold (STB_LOCAL)
ffffffff81b89f00-ffffffff81b89f70: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d2ab0b)
Location: drivers/opp/core.c:401
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff820a8b4d-ffffffff820a8b61: _get_opp_count.cold (STB_LOCAL)
ffffffff81d29570-ffffffff81d295e0: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d93d8b)
Location: drivers/opp/core.c:404
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff82129d23-ffffffff82129d37: _get_opp_count.cold (STB_LOCAL)
ffffffff81d92710-ffffffff81d92780: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81e4b7e3)
Location: drivers/opp/core.c:403
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8220ba6c-ffffffff8220ba80: _get_opp_count.cold (STB_LOCAL)
ffffffff81e4a040-ffffffff81e4a0b0: _get_opp_count (STB_GLOBAL)
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
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b19a18)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffff800010b19a18-ffff800010b19a80: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf46f8)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
c0bf46f8-c0bf4758: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0b490)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
c000000000c0b490-c000000000c0b520: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702304)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffe000702304-ffffffe00070235c: _get_opp_count (STB_GLOBAL)
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
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81863010)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81863010-ffffffff8186305f: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182bcc0)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8182bcc0-ffffffff8182bd0f: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b3da0)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff818b3da0-ffffffff818b3def: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _get_opp_count(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0050)
Location: drivers/opp/core.c:302
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff818d0050-ffffffff818d009f: _get_opp_count (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
