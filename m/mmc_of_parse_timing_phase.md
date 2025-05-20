# Function: <code>mmc_of_parse_timing_phase</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81991295)
Location: drivers/mmc/core/host.c:205
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmc_of_parse_timing_phase(struct device *dev, const char *prop, struct mmc_clk_phase *phase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81a3c690)
Location: drivers/mmc/core/host.c:223
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
```
**Symbols:**

```
ffffffff81a3c690-ffffffff81a3c6f9: mmc_of_parse_timing_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmc_of_parse_timing_phase(struct device *dev, const char *prop, struct mmc_clk_phase *phase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81ba9700)
Location: drivers/mmc/core/host.c:223
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
```
**Symbols:**

```
ffffffff81ba9700-ffffffff81ba9777: mmc_of_parse_timing_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mmc_of_parse_timing_phase(struct device *dev, const char *prop, struct mmc_clk_phase *phase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81d4c480)
Location: drivers/mmc/core/host.c:223
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
```
**Symbols:**

```
ffffffff81d4c480-ffffffff81d4c4f7: mmc_of_parse_timing_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mmc_of_parse_timing_phase(struct device *dev, const char *prop, struct mmc_clk_phase *phase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81db6d50)
Location: drivers/mmc/core/host.c:223
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
```
**Symbols:**

```
ffffffff81db6d50-ffffffff81db6dc7: mmc_of_parse_timing_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mmc_of_parse_timing_phase(struct device *dev, const char *prop, struct mmc_clk_phase *phase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81e6f220)
Location: drivers/mmc/core/host.c:222
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
```
**Symbols:**

```
ffffffff81e6f220-ffffffff81e6f297: mmc_of_parse_timing_phase (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
