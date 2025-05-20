# Function: <code>mmc_gpio_set_cd_wake</code>

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
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff81840fc0)
Location: drivers/mmc/core/slot-gpio.c:165
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81840fc0-ffffffff8184102b: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff8186cf10)
Location: drivers/mmc/core/slot-gpio.c:138
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff8186cf10-ffffffff8186cf7b: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff818b0d80)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff818b0d80-ffffffff818b0de7: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff818e3210)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff818e3210-ffffffff818e3277: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff819b62f0)
Location: drivers/mmc/core/slot-gpio.c:122
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff819b62f0-ffffffff819b6357: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff819b8830)
Location: drivers/mmc/core/slot-gpio.c:122
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff819b8830-ffffffff819b8897: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff8199cf60)
Location: drivers/mmc/core/slot-gpio.c:122
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff8199cf60-ffffffff8199cfc7: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff81a49b02)
Location: drivers/mmc/core/slot-gpio.c:122
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81d2e860-ffffffff81d2e875: mmc_gpio_set_cd_wake.cold (STB_LOCAL)
ffffffff81a49ac0-ffffffff81a49b41: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (0)
Location: drivers/mmc/core/slot-gpio.c:122
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81efacd1-ffffffff81eface6: mmc_gpio_set_cd_wake.cold (STB_LOCAL)
ffffffff81bb7ea0-ffffffff81bb7f3d: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (0)
Location: drivers/mmc/core/slot-gpio.c:122
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff820a9bd7-ffffffff820a9bec: mmc_gpio_set_cd_wake.cold (STB_LOCAL)
ffffffff81d5cb60-ffffffff81d5cbfd: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (0)
Location: drivers/mmc/core/slot-gpio.c:137
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff8212afb0-ffffffff8212afc5: mmc_gpio_set_cd_wake.cold (STB_LOCAL)
ffffffff81dc7630-ffffffff81dc76cd: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (0)
Location: drivers/mmc/core/slot-gpio.c:141
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff8220cd6d-ffffffff8220cd82: mmc_gpio_set_cd_wake.cold (STB_LOCAL)
ffffffff81e7ff90-ffffffff81e8002d: mmc_gpio_set_cd_wake (STB_GLOBAL)
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
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffff800010b3dad0)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffff800010b3dad0-ffff800010b3db64: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (c0c180bc)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
c0c180bc-c0c18134: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (c000000000c3b190)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
c000000000c3b190-c000000000c3b298: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffe000714b1e)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffe000714b1e-ffffffe000714ba2: mmc_gpio_set_cd_wake (STB_GLOBAL)
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
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff81886bd0)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81886bd0-ffffffff81886c37: mmc_gpio_set_cd_wake (STB_GLOBAL)
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
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff818d8070)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff818d8070-ffffffff818d80d7: mmc_gpio_set_cd_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_gpio_set_cd_wake(struct mmc_host *host, bool on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/slot-gpio.c (ffffffff818f4b90)
Location: drivers/mmc/core/slot-gpio.c:130
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff818f4b90-ffffffff818f4bf7: mmc_gpio_set_cd_wake (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
