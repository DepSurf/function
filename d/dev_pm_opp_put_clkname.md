# Function: <code>dev_pm_opp_put_clkname</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3cf0)
Location: drivers/opp/core.c:1494
Inline: False
```
**Symbols:**

```
ffffffff817d3cf0-ffffffff817d3d30: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cab0)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
ffffffff8181cab0-ffffffff8181caf0: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848640)
Location: drivers/opp/core.c:1618
Inline: False
```
**Symbols:**

```
ffffffff81848640-ffffffff81848680: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1689
Inline: False
```
**Symbols:**

```
ffffffff8188d570-ffffffff8188d583: dev_pm_opp_put_clkname.cold (STB_LOCAL)
ffffffff8188b6a0-ffffffff8188b6e4: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bd770)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
ffffffff818bd770-ffffffff818bd7b4: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198e150)
Location: drivers/opp/core.c:1852
Inline: False
```
**Symbols:**

```
ffffffff8198e150-ffffffff8198e1ad: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81991ed0)
Location: drivers/opp/core.c:1943
Inline: False
```
**Symbols:**

```
ffffffff81991ed0-ffffffff81991f33: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819788cd)
Location: drivers/opp/core.c:2157
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81976360-ffffffff819763b1: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a2184d)
Location: drivers/opp/core.c:2167
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81a1f040-ffffffff81a1f091: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8a838)
Location: drivers/opp/core.c:2307
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81b87af0-ffffffff81b87b53: dev_pm_opp_put_clkname (STB_GLOBAL)
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
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b184e0)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
ffff800010b184e0-ffff800010b18534: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3488)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
c0bf3488-c0bf34e8: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09b00)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
c000000000c09b00-c000000000c09b34: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe0007010c0)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
ffffffe0007010c0-ffffffe00070110a: dev_pm_opp_put_clkname (STB_GLOBAL)
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
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81861e90)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
ffffffff81861e90-ffffffff81861ed4: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182ab40)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
ffffffff8182ab40-ffffffff8182ab84: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2c20)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
ffffffff818b2c20-ffffffff818b2c64: dev_pm_opp_put_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_put_clkname(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818ceed0)
Location: drivers/opp/core.c:1738
Inline: False
```
**Symbols:**

```
ffffffff818ceed0-ffffffff818cef14: dev_pm_opp_put_clkname (STB_GLOBAL)
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
