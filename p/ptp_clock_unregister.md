# Function: <code>ptp_clock_unregister</code>

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
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817dedf0)
Location: drivers/ptp/ptp_clock.c:303
Inline: False
```
**Symbols:**

```
ffffffff817dedf0-ffffffff817dee76: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8180a230)
Location: drivers/ptp/ptp_clock.c:305
Inline: False
```
**Symbols:**

```
ffffffff8180a230-ffffffff8180a2b6: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8184bf10)
Location: drivers/ptp/ptp_clock.c:293
Inline: False
```
**Symbols:**

```
ffffffff8184bf10-ffffffff8184bf9e: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8187d740)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
```
**Symbols:**

```
ffffffff8187d740-ffffffff8187d7a0: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8194bbc0)
Location: drivers/ptp/ptp_clock.c:304
Inline: False
```
**Symbols:**

```
ffffffff8194bbc0-ffffffff8194bc22: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff819515d0)
Location: drivers/ptp/ptp_clock.c:304
Inline: False
```
**Symbols:**

```
ffffffff819515d0-ffffffff81951632: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81935450)
Location: drivers/ptp/ptp_clock.c:304
Inline: False
```
**Symbols:**

```
ffffffff81935450-ffffffff819354b2: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:323
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
**Symbols:**

```
ffffffff81d260d0-ffffffff81d260e4: ptp_clock_unregister.cold (STB_LOCAL)
ffffffff819d90a0-ffffffff819d916f: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:354
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
**Symbols:**

```
ffffffff81ef1f03-ffffffff81ef1f18: ptp_clock_unregister.cold (STB_LOCAL)
ffffffff81b3c580-ffffffff81b3c652: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:351
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
**Symbols:**

```
ffffffff820a7799-ffffffff820a77ae: ptp_clock_unregister.cold (STB_LOCAL)
ffffffff81cd2510-ffffffff81cd25e2: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:355
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
**Symbols:**

```
ffffffff82128b94-ffffffff82128ba9: ptp_clock_unregister.cold (STB_LOCAL)
ffffffff81d39f90-ffffffff81d3a062: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:387
Inline: False
Direct callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
**Symbols:**

```
ffffffff8220a526-ffffffff8220a53b: ptp_clock_unregister.cold (STB_LOCAL)
ffffffff81df0540-ffffffff81df0612: ptp_clock_unregister (STB_GLOBAL)
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
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffff800010ac7348)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_stop
```
**Symbols:**

```
ffff800010ac7348-ffff800010ac73b0: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c0ba6db0)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_stop
  - drivers/net/ethernet/ti/cpts.c:cpts_unregister
```
**Symbols:**

```
c0ba6db0-c0ba6e18: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c000000000ba8780)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
```
**Symbols:**

```
c000000000ba8780-c000000000ba880c: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffe0006c5a2c)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
```
**Symbols:**

```
ffffffe0006c5a2c-ffffffe0006c5aa0: ptp_clock_unregister (STB_GLOBAL)
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
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81825cb0)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
```
**Symbols:**

```
ffffffff81825cb0-ffffffff81825d10: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817ed340)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
```
**Symbols:**

```
ffffffff817ed340-ffffffff817ed3a0: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81872bf0)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
```
**Symbols:**

```
ffffffff81872bf0-ffffffff81872c50: ptp_clock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptp_clock_unregister(struct ptp_clock *ptp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8188e5a0)
Location: drivers/ptp/ptp_clock.c:295
Inline: False
```
**Symbols:**

```
ffffffff8188e5a0-ffffffff8188e600: ptp_clock_unregister (STB_GLOBAL)
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
