# Function: <code>posix_clock_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, dev_t devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff810f9dd0)
Location: kernel/time/posix-clock.c:209
Inline: False
```
**Symbols:**

```
ffffffff810f9dd0-ffffffff810f9e3f: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, dev_t devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81101070)
Location: kernel/time/posix-clock.c:209
Inline: False
```
**Symbols:**

```
ffffffff81101070-ffffffff811010df: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, dev_t devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81108d30)
Location: kernel/time/posix-clock.c:209
Inline: False
```
**Symbols:**

```
ffffffff81108d30-ffffffff81108d9f: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, dev_t devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff8110af50)
Location: kernel/time/posix-clock.c:177
Inline: False
```
**Symbols:**

```
ffffffff8110af50-ffffffff8110afbc: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, dev_t devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff811160b0)
Location: kernel/time/posix-clock.c:177
Inline: False
```
**Symbols:**

```
ffffffff811160b0-ffffffff8111611c: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, dev_t devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81122960)
Location: kernel/time/posix-clock.c:177
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81122960-ffffffff811229c9: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, dev_t devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff8112e040)
Location: kernel/time/posix-clock.c:164
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff8112e040-ffffffff8112e0a9: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, dev_t devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81138a50)
Location: kernel/time/posix-clock.c:164
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81138a50-ffffffff81138ab9: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81144e1f-ffffffff81144e55: posix_clock_register.cold (STB_LOCAL)
ffffffff811446c0-ffffffff81144732: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff811546f4-ffffffff8115472a: posix_clock_register.cold (STB_LOCAL)
ffffffff81154030-ffffffff811540a2: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81be3b53-ffffffff81be3b89: posix_clock_register.cold (STB_LOCAL)
ffffffff811502b0-ffffffff81150322: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81bd5a72-ffffffff81bd5aa8: posix_clock_register.cold (STB_LOCAL)
ffffffff811516e0-ffffffff81151752: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81cb1d46-ffffffff81cb1d7c: posix_clock_register.cold (STB_LOCAL)
ffffffff81175b10-ffffffff81175b82: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81e632f2-ffffffff81e63328: posix_clock_register.cold (STB_LOCAL)
ffffffff811aab00-ffffffff811aab7e: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff811eac10)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff811eac10-ffffffff811eacdb: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff811ff4f0)
Location: kernel/time/posix-clock.c:162
Inline: True
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff811ff4f0-ffffffff811ff5bb: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81215860)
Location: kernel/time/posix-clock.c:180
Inline: True
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81215860-ffffffff8121592b: posix_clock_register (STB_GLOBAL)
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
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffff8000101aed20)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffff8000101aed20-ffff8000101aedcc: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (c03f9d54)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
c03f9d54-c03f9dec: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (c000000000213280)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
c000000000213280-c00000000021335c: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffe0001385c6)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffe0001385c6-ffffffe000138668: posix_clock_register (STB_GLOBAL)
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
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff8113d5cf-ffffffff8113d605: posix_clock_register.cold (STB_LOCAL)
ffffffff8113ce70-ffffffff8113cee2: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff8113011f-ffffffff81130155: posix_clock_register.cold (STB_LOCAL)
ffffffff8112f9c0-ffffffff8112fa32: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff8113b2ef-ffffffff8113b325: posix_clock_register.cold (STB_LOCAL)
ffffffff8113ab90-ffffffff8113ac02: posix_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int posix_clock_register(struct posix_clock *clk, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:162
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
**Symbols:**

```
ffffffff81147d9f-ffffffff81147dd5: posix_clock_register.cold (STB_LOCAL)
ffffffff81147640-ffffffff811476b2: posix_clock_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>dev_t devid</code>
</li>
</ul>
</details>
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
