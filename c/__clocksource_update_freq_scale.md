# Function: <code>__clocksource_update_freq_scale</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810f7c10)
Location: kernel/time/clocksource.c:661
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff810f7c10-ffffffff810f7e19: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810fed40)
Location: kernel/time/clocksource.c:693
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff810fed40-ffffffff810fef35: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81101bb0)
Location: kernel/time/clocksource.c:703
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81101bb0-ffffffff81101da5: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81103cf0)
Location: kernel/time/clocksource.c:710
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81103cf0-ffffffff81103f1e: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8110ed80)
Location: kernel/time/clocksource.c:709
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff8110ed80-ffffffff8110efae: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:731
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff8111b7a4-ffffffff8111b7ec: __clocksource_update_freq_scale.cold.11 (STB_LOCAL)
ffffffff8111a790-ffffffff8111a95e: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:851
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81126f94-ffffffff81126fd8: __clocksource_update_freq_scale.cold.12 (STB_LOCAL)
ffffffff81125c90-ffffffff81125e80: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:851
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81131945-ffffffff811319a7: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff81130700-ffffffff811308a1: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff8113d895-ffffffff8113d8f7: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff8113c640-ffffffff8113c7e1: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff8114ca99-ffffffff8114cafb: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff8114c1f0-ffffffff8114c396: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:850
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81be39d0-ffffffff81be3a32: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff81148650-ffffffff811487f6: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:951
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81bd590e-ffffffff81bd5951: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff81149af0-ffffffff81149ce3: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:1063
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81cb1777-ffffffff81cb181c: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff8116d3d0-ffffffff8116d5c0: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:1069
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81e62d51-ffffffff81e62dc9: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff811a1450-ffffffff811a1682: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:1088
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff8205b8f9-ffffffff8205b93e: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff811dfc70-ffffffff811dfee2: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:1099
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff820da10b-ffffffff820da150: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff811f4170-ffffffff811f43d6: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:1122
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff821b5a0a-ffffffff821b5a4f: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff8120a2b0-ffffffff8120a516: __clocksource_update_freq_scale (STB_GLOBAL)
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
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffff8000101a6860)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffff8000101a6860-ffff8000101a6a88: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c03f2350)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
c03f2350-c03f2550: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c000000000208ee0)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
c000000000208ee0-c00000000020918c: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffe0001329d0)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffe0001329d0-ffffffe000132bb4: __clocksource_update_freq_scale (STB_GLOBAL)
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
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81136045-ffffffff811360a7: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff81134df0-ffffffff81134f91: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81128a95-ffffffff81128af7: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff81127850-ffffffff811279f1: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81133d65-ffffffff81133dc7: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff81132b10-ffffffff81132cb1: __clocksource_update_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __clocksource_update_freq_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:858
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
```
**Symbols:**

```
ffffffff81140785-ffffffff811407e7: __clocksource_update_freq_scale.cold (STB_LOCAL)
ffffffff8113f530-ffffffff8113f6d1: __clocksource_update_freq_scale (STB_GLOBAL)
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
