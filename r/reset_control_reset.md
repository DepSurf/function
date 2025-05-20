# Function: <code>reset_control_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff814df250)
Location: drivers/reset/core.c:93
Inline: True
```
**Symbols:**

```
ffffffff814df250-ffffffff814df277: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81530490)
Location: drivers/reset/core.c:139
Inline: False
```
**Symbols:**

```
ffffffff81530490-ffffffff815304d7: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8155ca60)
Location: drivers/reset/core.c:147
Inline: False
```
**Symbols:**

```
ffffffff8155ca60-ffffffff8155caff: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81571540)
Location: drivers/reset/core.c:151
Inline: True
```
**Symbols:**

```
ffffffff81571540-ffffffff815715c3: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d58e0)
Location: drivers/reset/core.c:223
Inline: True
```
**Symbols:**

```
ffffffff815d58e0-ffffffff815d59aa: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160e640)
Location: drivers/reset/core.c:253
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8160e640-ffffffff8160e708: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b580)
Location: drivers/reset/core.c:253
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8162b580-ffffffff8162b648: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff8165eedd)
Location: drivers/reset/core.c:290
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8165f7af-ffffffff8165f7df: reset_control_reset.cold (STB_LOCAL)
ffffffff8165eea0-ffffffff8165ef69: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681570)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff81681570-ffffffff8168164b: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732660)
Location: drivers/reset/core.c:292
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff81732660-ffffffff8173273b: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174e7b0)
Location: drivers/reset/core.c:326
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8174e7b0-ffffffff8174e88b: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817322d0)
Location: drivers/reset/core.c:326
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:reset_control_bulk_reset
```
**Symbols:**

```
ffffffff817322d0-ffffffff817323a3: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff817b2ab2)
Location: drivers/reset/core.c:326
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:reset_control_bulk_reset
```
**Symbols:**

```
ffffffff81cf84e4-ffffffff81cf853e: reset_control_reset.cold (STB_LOCAL)
ffffffff817b2a70-ffffffff817b2b98: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:327
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:reset_control_bulk_reset
  - drivers/reset/core.c:reset_control_reset
```
**Symbols:**

```
ffffffff81ec05e1-ffffffff81ec063b: reset_control_reset.cold (STB_LOCAL)
ffffffff818ee460-ffffffff818ee5a1: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:327
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:reset_control_bulk_reset
  - drivers/reset/core.c:reset_control_reset
```
**Symbols:**

```
ffffffff82094d47-ffffffff82094da1: reset_control_reset.cold (STB_LOCAL)
ffffffff81a46070-ffffffff81a461b1: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:327
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:reset_control_bulk_reset
  - drivers/reset/core.c:reset_control_reset
```
**Symbols:**

```
ffffffff82115b6c-ffffffff82115bc6: reset_control_reset.cold (STB_LOCAL)
ffffffff81a90220-ffffffff81a90366: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:327
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:reset_control_bulk_reset
  - drivers/reset/core.c:reset_control_reset
```
**Symbols:**

```
ffffffff821f3872-ffffffff821f38cc: reset_control_reset.cold (STB_LOCAL)
ffffffff81ae2c60-ffffffff81ae2da6: reset_control_reset (STB_GLOBAL)
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
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084cea0)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffff80001084cea0-ffff80001084cfdc: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958d08)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
c0958d08-c0958e78: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008eadc0)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
c0000000008eadc0-c0000000008eafc0: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052c172)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffe00052c172-ffffffe00052c236: reset_control_reset (STB_GLOBAL)
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
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81646ff0)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff81646ff0-ffffffff816470cb: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627450)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff81627450-ffffffff8162752b: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816753b0)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff816753b0-ffffffff8167548b: reset_control_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int reset_control_reset(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168fa10)
Location: drivers/reset/core.c:289
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8168fa10-ffffffff8168faeb: reset_control_reset (STB_GLOBAL)
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
