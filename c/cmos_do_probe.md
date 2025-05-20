# Function: <code>cmos_do_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81676bb0)
Location: drivers/rtc/rtc-cmos.c:590
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81676bb0-ffffffff81676fdc: cmos_do_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff816d7790)
Location: drivers/rtc/rtc-cmos.c:587
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff816d7790-ffffffff816d7b93: cmos_do_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff817076c0)
Location: drivers/rtc/rtc-cmos.c:668
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff817076c0-ffffffff81707adf: cmos_do_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff8171d2b0)
Location: drivers/rtc/rtc-cmos.c:671
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8171d2b0-ffffffff8171d6f5: cmos_do_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff8178e530)
Location: drivers/rtc/rtc-cmos.c:671
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8178e530-ffffffff8178e975: cmos_do_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff817d0ac0)
Location: drivers/rtc/rtc-cmos.c:692
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff817d0ac0-ffffffff817d0fd8: cmos_do_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff817f7df0)
Location: drivers/rtc/rtc-cmos.c:710
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff817f7df0-ffffffff817f8310: cmos_do_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:706
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81838ad0-ffffffff81838f38: cmos_do_probe (STB_LOCAL)
ffffffff81839c77-ffffffff81839d34: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:706
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8186a440-ffffffff8186a8a5: cmos_do_probe (STB_LOCAL)
ffffffff8186b5e7-ffffffff8186b6a4: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:707
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8193e070-ffffffff8193e524: cmos_do_probe (STB_LOCAL)
ffffffff8193f338-ffffffff8193f3b1: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:707
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81944e70-ffffffff8194534a: cmos_do_probe (STB_LOCAL)
ffffffff81c246a0-ffffffff81c24705: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:700
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81928660-ffffffff81928b49: cmos_do_probe (STB_LOCAL)
ffffffff81c1675d-ffffffff81c167c2: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:697
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff819cb000-ffffffff819cb502: cmos_do_probe (STB_LOCAL)
ffffffff81d2534e-ffffffff81d253f2: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:755
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81b2cca0-ffffffff81b2d1a4: cmos_do_probe (STB_LOCAL)
ffffffff81ef1151-ffffffff81ef1217: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:917
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81cc0df0-ffffffff81cc1509: cmos_do_probe (STB_LOCAL)
ffffffff820a7595-ffffffff820a7600: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:917
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81d287b0-ffffffff81d28ed7: cmos_do_probe (STB_LOCAL)
ffffffff82128998-ffffffff82128a03: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:927
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81dde5d0-ffffffff81dded52: cmos_do_probe (STB_LOCAL)
ffffffff8220a32a-ffffffff8220a395: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:706
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8181d0f0-ffffffff8181d555: cmos_do_probe (STB_LOCAL)
ffffffff8181e297-ffffffff8181e354: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:706
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff817e47e0-ffffffff817e4c3f: cmos_do_probe (STB_LOCAL)
ffffffff817e5937-ffffffff817e59f4: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:706
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8185e5d0-ffffffff8185ea35: cmos_do_probe (STB_LOCAL)
ffffffff8185f777-ffffffff8185f834: cmos_do_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cmos_do_probe(struct device *dev, struct resource *ports, int rtc_irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:706
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8187a410-ffffffff8187a880: cmos_do_probe (STB_LOCAL)
ffffffff8187a998-ffffffff8187aa55: cmos_do_probe.cold (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
