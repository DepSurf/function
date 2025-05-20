# Function: <code>reset_control_release</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:527
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffff8165f79c-ffffffff8165f7af: reset_control_release.cold (STB_LOCAL)
ffffffff8165eca0-ffffffff8165ecf7: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681390)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffff81681390-ffffffff816813e7: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817324d0)
Location: drivers/reset/core.c:527
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffff817324d0-ffffffff81732527: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174e620)
Location: drivers/reset/core.c:601
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffff8174e620-ffffffff8174e677: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732100)
Location: drivers/reset/core.c:715
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_release
  - drivers/reset/core.c:reset_control_release
  - drivers/reset/core.c:reset_control_bulk_acquire
```
**Symbols:**

```
ffffffff81732100-ffffffff81732157: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:715
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_release
  - drivers/reset/core.c:reset_control_release
  - drivers/reset/core.c:reset_control_bulk_acquire
```
**Symbols:**

```
ffffffff81cf84cf-ffffffff81cf84e4: reset_control_release.cold (STB_LOCAL)
ffffffff817b29c0-ffffffff817b2a26: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:716
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_release
  - drivers/reset/core.c:reset_control_release
  - drivers/reset/core.c:reset_control_bulk_acquire
  - drivers/reset/core.c:reset_control_acquire
```
**Symbols:**

```
ffffffff81ec05cc-ffffffff81ec05e1: reset_control_release.cold (STB_LOCAL)
ffffffff818ee380-ffffffff818ee404: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:716
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_release
  - drivers/reset/core.c:reset_control_release
  - drivers/reset/core.c:reset_control_bulk_acquire
  - drivers/reset/core.c:reset_control_acquire
```
**Symbols:**

```
ffffffff82094d32-ffffffff82094d47: reset_control_release.cold (STB_LOCAL)
ffffffff81a45f70-ffffffff81a45ff4: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:716
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_release
  - drivers/reset/core.c:reset_control_release
  - drivers/reset/core.c:reset_control_bulk_acquire
  - drivers/reset/core.c:reset_control_acquire
```
**Symbols:**

```
ffffffff82115b57-ffffffff82115b6c: reset_control_release.cold (STB_LOCAL)
ffffffff81a90120-ffffffff81a901a5: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:716
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_release
  - drivers/reset/core.c:reset_control_release
  - drivers/reset/core.c:reset_control_bulk_acquire
  - drivers/reset/core.c:reset_control_acquire
```
**Symbols:**

```
ffffffff821f385d-ffffffff821f3872: reset_control_release.cold (STB_LOCAL)
ffffffff81ae2b60-ffffffff81ae2be5: reset_control_release (STB_GLOBAL)
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
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c2a8)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffff80001084c2a8-ffff80001084c320: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c09585f0)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_off
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_on
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
c09585f0-c0958674: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008ea920)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
c0000000008ea920-c0000000008ea9e0: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052bb38)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffe00052bb38-ffffffe00052bba2: reset_control_release (STB_GLOBAL)
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
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81646e10)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffff81646e10-ffffffff81646e67: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627270)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffff81627270-ffffffff816272c7: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816751d0)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffff816751d0-ffffffff81675227: reset_control_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reset_control_release(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168f830)
Location: drivers/reset/core.c:526
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_release
```
**Symbols:**

```
ffffffff8168f830-ffffffff8168f887: reset_control_release (STB_GLOBAL)
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
