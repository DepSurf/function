# Function: <code>dev_pm_opp_unregister_set_opp_helper</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4010)
Location: drivers/opp/core.c:1559
Inline: True
```
**Symbols:**

```
ffffffff817d4010-ffffffff817d405b: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181caf0)
Location: drivers/opp/core.c:1532
Inline: False
```
**Symbols:**

```
ffffffff8181caf0-ffffffff8181cb1c: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848610)
Location: drivers/opp/core.c:1673
Inline: False
```
**Symbols:**

```
ffffffff81848610-ffffffff8184863c: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1744
Inline: False
```
**Symbols:**

```
ffffffff8188d55d-ffffffff8188d570: dev_pm_opp_unregister_set_opp_helper.cold (STB_LOCAL)
ffffffff8188b660-ffffffff8188b697: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bd740)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
ffffffff818bd740-ffffffff818bd76c: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198e100)
Location: drivers/opp/core.c:1907
Inline: False
```
**Symbols:**

```
ffffffff8198e100-ffffffff8198e14c: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81991e00)
Location: drivers/opp/core.c:2001
Inline: False
```
**Symbols:**

```
ffffffff81991e00-ffffffff81991e52: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81978a9d)
Location: drivers/opp/core.c:2255
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
```
**Symbols:**

```
ffffffff81976500-ffffffff8197656f: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a21a1d)
Location: drivers/opp/core.c:2265
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
```
**Symbols:**

```
ffffffff81a1f230-ffffffff81a1f29f: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8aa3c)
Location: drivers/opp/core.c:2405
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
```
**Symbols:**

```
ffffffff81b87d50-ffffffff81b87dd3: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
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
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18480)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
ffff800010b18480-ffff800010b184dc: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3430)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
c0bf3430-c0bf3488: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09b40)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
c000000000c09b40-c000000000c09b74: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701084)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
ffffffe000701084-ffffffe0007010c0: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
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
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81861e60)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
ffffffff81861e60-ffffffff81861e8c: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182ab10)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
ffffffff8182ab10-ffffffff8182ab3c: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2bf0)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
ffffffff818b2bf0-ffffffff818b2c1c: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_unregister_set_opp_helper(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818ceea0)
Location: drivers/opp/core.c:1793
Inline: False
```
**Symbols:**

```
ffffffff818ceea0-ffffffff818ceecc: dev_pm_opp_unregister_set_opp_helper (STB_GLOBAL)
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
