# Function: <code>ptp_clock_register</code>

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
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:203
Inline: False
```
**Symbols:**

```
ffffffff817df471-ffffffff817df4cd: ptp_clock_register.cold.5 (STB_LOCAL)
ffffffff817df0d0-ffffffff817df471: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:206
Inline: False
```
**Symbols:**

```
ffffffff8180a857-ffffffff8180a8b2: ptp_clock_register.cold.5 (STB_LOCAL)
ffffffff8180a510-ffffffff8180a857: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:194
Inline: False
```
**Symbols:**

```
ffffffff8184c55d-ffffffff8184c5bb: ptp_clock_register.cold (STB_LOCAL)
ffffffff8184c1f0-ffffffff8184c55d: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
```
**Symbols:**

```
ffffffff8187dd6c-ffffffff8187ddbe: ptp_clock_register.cold (STB_LOCAL)
ffffffff8187d9f0-ffffffff8187dd6c: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:207
Inline: False
```
**Symbols:**

```
ffffffff8194c1ef-ffffffff8194c241: ptp_clock_register.cold (STB_LOCAL)
ffffffff8194bdf0-ffffffff8194c16f: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:207
Inline: False
```
**Symbols:**

```
ffffffff81c252ac-ffffffff81c252fe: ptp_clock_register.cold (STB_LOCAL)
ffffffff81951800-ffffffff81951b7f: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:207
Inline: False
```
**Symbols:**

```
ffffffff81c1734e-ffffffff81c173a0: ptp_clock_register.cold (STB_LOCAL)
ffffffff81935680-ffffffff819359ff: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:199
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
**Symbols:**

```
ffffffff81d26075-ffffffff81d260bb: ptp_clock_register.cold (STB_LOCAL)
ffffffff819d8b00-ffffffff819d8f82: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:207
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
**Symbols:**

```
ffffffff81ef1ebd-ffffffff81ef1f03: ptp_clock_register.cold (STB_LOCAL)
ffffffff81b3c070-ffffffff81b3c574: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:204
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
**Symbols:**

```
ffffffff820a7785-ffffffff820a7799: ptp_clock_register.cold (STB_LOCAL)
ffffffff81cd1fc0-ffffffff81cd24f1: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:208
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
**Symbols:**

```
ffffffff82128b80-ffffffff82128b94: ptp_clock_register.cold (STB_LOCAL)
ffffffff81d39a40-ffffffff81d39f71: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:221
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
**Symbols:**

```
ffffffff8220a512-ffffffff8220a526: ptp_clock_register.cold (STB_LOCAL)
ffffffff81defe00-ffffffff81df052c: ptp_clock_register (STB_GLOBAL)
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
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffff800010ac7000)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
```
**Symbols:**

```
ffff800010ac7000-ffff800010ac7348: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c0ba6a80)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/ethernet/ti/cpts.c:cpts_register
```
**Symbols:**

```
c0ba6a80-c0ba6db0: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c000000000ba8b90)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
```
**Symbols:**

```
c000000000ba8b90-c000000000ba8f80: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffe0006c5cc8)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
```
**Symbols:**

```
ffffffe0006c5cc8-ffffffe0006c6008: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
```
**Symbols:**

```
ffffffff818262dc-ffffffff8182632e: ptp_clock_register.cold (STB_LOCAL)
ffffffff81825f60-ffffffff818262dc: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
```
**Symbols:**

```
ffffffff817ed96c-ffffffff817ed9be: ptp_clock_register.cold (STB_LOCAL)
ffffffff817ed5f0-ffffffff817ed96c: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
```
**Symbols:**

```
ffffffff8187321c-ffffffff8187326e: ptp_clock_register.cold (STB_LOCAL)
ffffffff81872ea0-ffffffff8187321c: ptp_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct ptp_clock *ptp_clock_register(struct ptp_clock_info *info, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:198
Inline: False
```
**Symbols:**

```
ffffffff8188ebcc-ffffffff8188ec1e: ptp_clock_register.cold (STB_LOCAL)
ffffffff8188e850-ffffffff8188ebcc: ptp_clock_register (STB_GLOBAL)
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
