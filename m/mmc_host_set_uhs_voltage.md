# Function: <code>mmc_host_set_uhs_voltage</code>

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
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817ea290)
Location: drivers/mmc/core/core.c:1685
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff817ea290-ffffffff817ea425: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818331f0)
Location: drivers/mmc/core/core.c:1495
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818331f0-ffffffff8183338d: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185f180)
Location: drivers/mmc/core/core.c:1498
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff8185f180-ffffffff8185f31d: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a2d00)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818a2d00-ffffffff818a2ebb: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d4ff0)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818d4ff0-ffffffff818d51ab: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7dbc)
Location: drivers/mmc/core/core.c:1163
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff819a77d0-ffffffff819a798b: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819ab01c)
Location: drivers/mmc/core/core.c:1163
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff819aaa30-ffffffff819aabeb: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198f2d0)
Location: drivers/mmc/core/core.c:1169
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff8198f2d0-ffffffff8198f48b: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1170
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81d2d15a-ffffffff81d2d1aa: mmc_host_set_uhs_voltage.cold (STB_LOCAL)
ffffffff81a3a9d0-ffffffff81a3aba8: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1170
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81ef9517-ffffffff81ef9564: mmc_host_set_uhs_voltage.cold (STB_LOCAL)
ffffffff81ba7830-ffffffff81ba7a15: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1177
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff820a966a-ffffffff820a96b7: mmc_host_set_uhs_voltage.cold (STB_LOCAL)
ffffffff81d49ec0-ffffffff81d4a0a5: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1177
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff8212aa69-ffffffff8212aab6: mmc_host_set_uhs_voltage.cold (STB_LOCAL)
ffffffff81db4730-ffffffff81db4904: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1182
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff8220c7e3-ffffffff8220c830: mmc_host_set_uhs_voltage.cold (STB_LOCAL)
ffffffff81e6c7d0-ffffffff81e6c9a4: mmc_host_set_uhs_voltage (STB_GLOBAL)
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
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2e800)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffff800010b2e800-ffff800010b2e978: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c09d18)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
c0c09d18-c0c09ea4: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c280a0)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
c000000000c280a0-c000000000c282a8: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000708054)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffe000708054-ffffffe00070818c: mmc_host_set_uhs_voltage (STB_GLOBAL)
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
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818789b0)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818789b0-ffffffff81878b6b: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c9e50)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818c9e50-ffffffff818ca00b: mmc_host_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_host_set_uhs_voltage(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e6970)
Location: drivers/mmc/core/core.c:1180
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff818e6970-ffffffff818e6b2b: mmc_host_set_uhs_voltage (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
