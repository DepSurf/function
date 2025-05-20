# Function: <code>thermal_register_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816882a0)
Location: drivers/thermal/thermal_core.c:133
Inline: False
Direct callers:
  - drivers/thermal/fair_share.c:thermal_gov_fair_share_register
  - drivers/thermal/gov_bang_bang.c:thermal_gov_bang_bang_register
  - drivers/thermal/step_wise.c:thermal_gov_step_wise_register
  - drivers/thermal/user_space.c:thermal_gov_user_space_register
  - drivers/thermal/power_allocator.c:thermal_gov_power_allocator_register
```
**Symbols:**

```
ffffffff816882a0-ffffffff81688407: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e8f70)
Location: drivers/thermal/thermal_core.c:133
Inline: False
Direct callers:
  - drivers/thermal/fair_share.c:thermal_gov_fair_share_register
  - drivers/thermal/gov_bang_bang.c:thermal_gov_bang_bang_register
  - drivers/thermal/step_wise.c:thermal_gov_step_wise_register
  - drivers/thermal/user_space.c:thermal_gov_user_space_register
  - drivers/thermal/power_allocator.c:thermal_gov_power_allocator_register
```
**Symbols:**

```
ffffffff816e8f70-ffffffff816e90f7: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81717f10)
Location: drivers/thermal/thermal_core.c:127
Inline: False
Direct callers:
  - drivers/thermal/fair_share.c:thermal_gov_fair_share_register
  - drivers/thermal/gov_bang_bang.c:thermal_gov_bang_bang_register
  - drivers/thermal/step_wise.c:thermal_gov_step_wise_register
  - drivers/thermal/user_space.c:thermal_gov_user_space_register
  - drivers/thermal/power_allocator.c:thermal_gov_power_allocator_register
```
**Symbols:**

```
ffffffff81717f10-ffffffff8171808f: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817301c0)
Location: drivers/thermal/thermal_core.c:128
Inline: False
Direct callers:
  - drivers/thermal/fair_share.c:thermal_gov_fair_share_register
  - drivers/thermal/gov_bang_bang.c:thermal_gov_bang_bang_register
  - drivers/thermal/step_wise.c:thermal_gov_step_wise_register
  - drivers/thermal/user_space.c:thermal_gov_user_space_register
  - drivers/thermal/power_allocator.c:thermal_gov_power_allocator_register
```
**Symbols:**

```
ffffffff817301c0-ffffffff8173033f: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817a1230)
Location: drivers/thermal/thermal_core.c:128
Inline: False
Direct callers:
  - drivers/thermal/fair_share.c:thermal_gov_fair_share_register
  - drivers/thermal/gov_bang_bang.c:thermal_gov_bang_bang_register
  - drivers/thermal/step_wise.c:thermal_gov_step_wise_register
  - drivers/thermal/user_space.c:thermal_gov_user_space_register
  - drivers/thermal/power_allocator.c:thermal_gov_power_allocator_register
```
**Symbols:**

```
ffffffff817a1230-ffffffff817a13af: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e87d0)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/fair_share.c:thermal_gov_fair_share_register
  - drivers/thermal/gov_bang_bang.c:thermal_gov_bang_bang_register
  - drivers/thermal/step_wise.c:thermal_gov_step_wise_register
  - drivers/thermal/user_space.c:thermal_gov_user_space_register
  - drivers/thermal/power_allocator.c:thermal_gov_power_allocator_register
```
**Symbols:**

```
ffffffff817e87d0-ffffffff817e8936: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81814680)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/fair_share.c:thermal_gov_fair_share_register
  - drivers/thermal/gov_bang_bang.c:thermal_gov_bang_bang_register
  - drivers/thermal/step_wise.c:thermal_gov_step_wise_register
  - drivers/thermal/user_space.c:thermal_gov_user_space_register
  - drivers/thermal/power_allocator.c:thermal_gov_power_allocator_register
```
**Symbols:**

```
ffffffff81814680-ffffffff818147e6: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff81856ef2-ffffffff81856f11: thermal_register_governor.cold (STB_LOCAL)
ffffffff81856860-ffffffff818569b1: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff818889aa-ffffffff818889c9: thermal_register_governor.cold (STB_LOCAL)
ffffffff818882b0-ffffffff81888401: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:119
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff819573cc-ffffffff819573eb: thermal_register_governor.cold (STB_LOCAL)
ffffffff81956d10-ffffffff81956e4a: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:119
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff81c25c25-ffffffff81c25c44: thermal_register_governor.cold (STB_LOCAL)
ffffffff8195c4a0-ffffffff8195c5da: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:119
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff81c17d24-ffffffff81c17d43: thermal_register_governor.cold (STB_LOCAL)
ffffffff8193fcd0-ffffffff8193fe00: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:117
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff81d26eb7-ffffffff81d26ed6: thermal_register_governor.cold (STB_LOCAL)
ffffffff819e45f0-ffffffff819e4720: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:117
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff81ef2cee-ffffffff81ef2d0d: thermal_register_governor.cold (STB_LOCAL)
ffffffff81b497b0-ffffffff81b498e9: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce0e80)
Location: drivers/thermal/thermal_core.c:117
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff81ce0e80-ffffffff81ce0fd0: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d49110)
Location: drivers/thermal/thermal_core.c:117
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff81d49110-ffffffff81d49260: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dffe60)
Location: drivers/thermal/thermal_core.c:115
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff81dffe60-ffffffff81dfffb0: thermal_register_governor (STB_GLOBAL)
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
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad59f0)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffff800010ad59f0-ffff800010ad5b68: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb6224)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
c0bb6224-c0bb6384: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bbb950)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
c000000000bbb950-c000000000bbbb5c: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006d0de8)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffe0006d0de8-ffffffe0006d0f3e: thermal_register_governor (STB_GLOBAL)
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
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff8182e82a-ffffffff8182e849: thermal_register_governor.cold (STB_LOCAL)
ffffffff8182e130-ffffffff8182e281: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff817f5eba-ffffffff817f5ed9: thermal_register_governor.cold (STB_LOCAL)
ffffffff817f57c0-ffffffff817f5911: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff8187de5a-ffffffff8187de79: thermal_register_governor.cold (STB_LOCAL)
ffffffff8187d760-ffffffff8187d8b1: thermal_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int thermal_register_governor(struct thermal_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:125
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
```
**Symbols:**

```
ffffffff8189988a-ffffffff818998a9: thermal_register_governor.cold (STB_LOCAL)
ffffffff81899190-ffffffff818992e1: thermal_register_governor (STB_GLOBAL)
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
