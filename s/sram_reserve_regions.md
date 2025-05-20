# Function: <code>sram_reserve_regions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff8157998f)
Location: drivers/misc/sram.c:178
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff815cea4c)
Location: drivers/misc/sram.c:178
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff815fb6ac)
Location: drivers/misc/sram.c:183
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff8160f40a)
Location: drivers/misc/sram.c:169
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff81677c8a)
Location: drivers/misc/sram.c:169
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff816b373d)
Location: drivers/misc/sram.c:169
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff816d49fd)
Location: drivers/misc/sram.c:169
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81710110-ffffffff817103eb: sram_reserve_regions (STB_LOCAL)
ffffffff817105c0-ffffffff81710600: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81734400-ffffffff817346db: sram_reserve_regions (STB_LOCAL)
ffffffff817348b0-ffffffff817348f0: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff817f1b30-ffffffff817f1cdb: sram_reserve_regions (STB_LOCAL)
ffffffff817f1e80-ffffffff817f1ea4: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81806160-ffffffff8180630b: sram_reserve_regions (STB_LOCAL)
ffffffff81c0fe2e-ffffffff81c0fe52: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff817eac70-ffffffff817eaf41: sram_reserve_regions (STB_LOCAL)
ffffffff81c01fb6-ffffffff81c01ff6: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:173
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff818776e0-ffffffff8187787f: sram_reserve_regions (STB_LOCAL)
ffffffff81d05dc9-ffffffff81d05dee: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:173
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff819bf9a0-ffffffff819bfb55: sram_reserve_regions (STB_LOCAL)
ffffffff81ece6e6-ffffffff81ece70b: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff81b351f0)
Location: drivers/misc/sram.c:173
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81b351f0-ffffffff81b353d2: sram_reserve_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff81b886b0)
Location: drivers/misc/sram.c:173
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81b886b0-ffffffff81b88892: sram_reserve_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffff81bdc580)
Location: drivers/misc/sram.c:173
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81bdc580-ffffffff81bdc791: sram_reserve_regions (STB_LOCAL)
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
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffff80001092b108)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffff80001092b108-ffff80001092b768: sram_reserve_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (c0a09874)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
c0a09874-c0a09f9c: sram_reserve_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (c0000000009ca250)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
c0000000009ca250-c0000000009caa8c: sram_reserve_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/misc/sram.c (ffffffe0005a2a74)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffe0005a2a74-ffffffe0005a30ae: sram_reserve_regions (STB_LOCAL)
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
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff816fa490-ffffffff816fa76b: sram_reserve_regions (STB_LOCAL)
ffffffff816fa940-ffffffff816fa980: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff816ce2a0-ffffffff816ce57b: sram_reserve_regions (STB_LOCAL)
ffffffff816ce750-ffffffff816ce790: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff817278c0-ffffffff81727b9b: sram_reserve_regions (STB_LOCAL)
ffffffff81727d70-ffffffff81727db0: sram_reserve_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sram_reserve_regions(struct sram_dev *sram, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:156
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81742d00-ffffffff81742fdb: sram_reserve_regions (STB_LOCAL)
ffffffff817431b0-ffffffff817431f0: sram_reserve_regions.cold (STB_LOCAL)
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
