# Function: <code>mmc_set_signal_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c07d0)
Location: drivers/mmc/core/core.c:1561
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff816c07d0-ffffffff816c0b1c: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81723500)
Location: drivers/mmc/core/core.c:1577
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81723500-ffffffff8172384b: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81756370)
Location: drivers/mmc/core/core.c:1649
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81756370-ffffffff8175669c: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817744ee)
Location: drivers/mmc/core/core.c:1465
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81774050-ffffffff8177409b: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817ea2d6)
Location: drivers/mmc/core/core.c:1669
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff817ea240-ffffffff817ea28e: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81833236)
Location: drivers/mmc/core/core.c:1468
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81832e20-ffffffff81832e6c: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185f1c6)
Location: drivers/mmc/core/core.c:1471
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff8185eef0-ffffffff8185ef3c: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a2d47)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff818a2a70-ffffffff818a2abc: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d5037)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff818d4d60-ffffffff818d4dac: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7df0)
Location: drivers/mmc/core/core.c:1136
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff819a7380-ffffffff819a73cc: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819ab050)
Location: drivers/mmc/core/core.c:1136
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff819aa5d0-ffffffff819aa61c: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198f317)
Location: drivers/mmc/core/core.c:1142
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff8198ee70-ffffffff8198eebc: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3aa1b)
Location: drivers/mmc/core/core.c:1143
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81a3a560-ffffffff81a3a5ac: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba787a)
Location: drivers/mmc/core/core.c:1143
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81ba7370-ffffffff81ba73d1: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d49f0a)
Location: drivers/mmc/core/core.c:1150
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81d499a0-ffffffff81d49a01: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db477a)
Location: drivers/mmc/core/core.c:1150
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81db4220-ffffffff81db4276: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6c81a)
Location: drivers/mmc/core/core.c:1155
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81e6c5f0-ffffffff81e6c646: mmc_set_signal_voltage (STB_GLOBAL)
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
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2e844)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffff800010b2e500-ffff800010b2e55c: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c09d70)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
c0c09a3c-c0c09a88: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c28104)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
c000000000c27c50-c000000000c27d00: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe00070809e)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffe000707d7a-ffffffe000707dc4: mmc_set_signal_voltage (STB_GLOBAL)
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
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818789f7)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff81878720-ffffffff8187876c: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c9e97)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff818c9bc0-ffffffff818c9c0c: mmc_set_signal_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mmc_set_signal_voltage(struct mmc_host *host, int signal_voltage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e69b7)
Location: drivers/mmc/core/core.c:1153
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_initial_signal_voltage
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff818e66e0-ffffffff818e672c: mmc_set_signal_voltage (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 ocr</code>
</li>
</ul>
</details>
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
