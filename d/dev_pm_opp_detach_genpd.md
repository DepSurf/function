# Function: <code>dev_pm_opp_detach_genpd</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188b9b0)
Location: drivers/opp/core.c:1872
Inline: False
```
**Symbols:**

```
ffffffff8188b9b0-ffffffff8188b9fa: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bda90)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
ffffffff818bda90-ffffffff818bdada: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198e0a0)
Location: drivers/opp/core.c:2035
Inline: False
```
**Symbols:**

```
ffffffff8198e0a0-ffffffff8198e0f2: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81991d90)
Location: drivers/opp/core.c:2132
Inline: False
```
**Symbols:**

```
ffffffff81991d90-ffffffff81991df2: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81978c9d)
Location: drivers/opp/core.c:2417
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81976490-ffffffff819764f2: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a21c1d)
Location: drivers/opp/core.c:2427
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81a1f2a0-ffffffff81a1f302: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8ac5e)
Location: drivers/opp/core.c:2567
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81b87cd0-ffffffff81b87d46: dev_pm_opp_detach_genpd (STB_GLOBAL)
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
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b188c8)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
ffff800010b188c8-ffff800010b18914: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf36b4)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
c0bf36b4-c0bf36f4: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09e60)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
c000000000c09e60-c000000000c09ec8: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe0007012ea)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
ffffffe0007012ea-ffffffe00070133a: dev_pm_opp_detach_genpd (STB_GLOBAL)
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
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818621b0)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
ffffffff818621b0-ffffffff818621fa: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182ae60)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
ffffffff8182ae60-ffffffff8182aeaa: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2f40)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
ffffffff818b2f40-ffffffff818b2f8a: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cf1f0)
Location: drivers/opp/core.c:1921
Inline: False
```
**Symbols:**

```
ffffffff818cf1f0-ffffffff818cf23a: dev_pm_opp_detach_genpd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
