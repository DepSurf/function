# Function: <code>reset_control_acquire</code>

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

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff8165ef9d)
Location: drivers/reset/core.c:481
Inline: True
```
**Symbols:**

```
ffffffff8165f7df-ffffffff8165f7f8: reset_control_acquire.cold (STB_LOCAL)
ffffffff8165ef70-ffffffff8165f06e: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681650)
Location: drivers/reset/core.c:480
Inline: True
```
**Symbols:**

```
ffffffff81681650-ffffffff81681758: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732740)
Location: drivers/reset/core.c:481
Inline: True
```
**Symbols:**

```
ffffffff81732740-ffffffff81732848: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174e900)
Location: drivers/reset/core.c:555
Inline: True
```
**Symbols:**

```
ffffffff8174e900-ffffffff8174ea08: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817324f0)
Location: drivers/reset/core.c:639
Inline: True
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_acquire
```
**Symbols:**

```
ffffffff817324f0-ffffffff817325f9: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff817b2ddd)
Location: drivers/reset/core.c:639
Inline: True
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_acquire
```
**Symbols:**

```
ffffffff81cf85c2-ffffffff81cf85ff: reset_control_acquire.cold (STB_LOCAL)
ffffffff817b2da0-ffffffff817b2ee1: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:640
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_acquire
  - drivers/reset/core.c:reset_control_acquire
```
**Symbols:**

```
ffffffff81ec06bf-ffffffff81ec06fc: reset_control_acquire.cold (STB_LOCAL)
ffffffff818ee7b0-ffffffff818ee917: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:640
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_acquire
  - drivers/reset/core.c:reset_control_acquire
```
**Symbols:**

```
ffffffff82094e25-ffffffff82094e62: reset_control_acquire.cold (STB_LOCAL)
ffffffff81a463f0-ffffffff81a46557: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:640
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_acquire
  - drivers/reset/core.c:reset_control_acquire
```
**Symbols:**

```
ffffffff82115c4a-ffffffff82115c87: reset_control_acquire.cold (STB_LOCAL)
ffffffff81a905a0-ffffffff81a9070c: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:640
Inline: False
Direct callers:
  - drivers/reset/core.c:reset_control_bulk_acquire
  - drivers/reset/core.c:reset_control_acquire
```
**Symbols:**

```
ffffffff821f3950-ffffffff821f398d: reset_control_acquire.cold (STB_LOCAL)
ffffffff81ae2fe0-ffffffff81ae314c: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084ca28)
Location: drivers/reset/core.c:480
Inline: True
```
**Symbols:**

```
ffff80001084ca28-ffff80001084cb78: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958e78)
Location: drivers/reset/core.c:480
Inline: True
Direct callers:
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_off
```
**Symbols:**

```
c0958e78-c0958fd8: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008eafc0)
Location: drivers/reset/core.c:480
Inline: True
```
**Symbols:**

```
c0000000008eafc0-c0000000008eb1f8: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052c236)
Location: drivers/reset/core.c:480
Inline: True
```
**Symbols:**

```
ffffffe00052c236-ffffffe00052c34a: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816470d0)
Location: drivers/reset/core.c:480
Inline: True
```
**Symbols:**

```
ffffffff816470d0-ffffffff816471d8: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627530)
Location: drivers/reset/core.c:480
Inline: True
```
**Symbols:**

```
ffffffff81627530-ffffffff81627638: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81675490)
Location: drivers/reset/core.c:480
Inline: True
```
**Symbols:**

```
ffffffff81675490-ffffffff81675598: reset_control_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int reset_control_acquire(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168faf0)
Location: drivers/reset/core.c:480
Inline: True
```
**Symbols:**

```
ffffffff8168faf0-ffffffff8168fbf8: reset_control_acquire (STB_GLOBAL)
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
