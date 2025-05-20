# Function: <code>watchdog_register_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8168ad20)
Location: drivers/watchdog/watchdog_core.c:219
Inline: False
```
**Symbols:**

```
ffffffff8168ad20-ffffffff8168ad8b: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff816ebb20)
Location: drivers/watchdog/watchdog_core.c:283
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff816ebb20-ffffffff816ebb8b: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8171ca40)
Location: drivers/watchdog/watchdog_core.c:283
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff8171ca40-ffffffff8171caab: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81734cb0)
Location: drivers/watchdog/watchdog_core.c:283
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff81734cb0-ffffffff81734d1b: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff817a6920)
Location: drivers/watchdog/watchdog_core.c:251
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff817a6920-ffffffff817a698b: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff817ee360)
Location: drivers/watchdog/watchdog_core.c:252
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff817ee360-ffffffff817ee3cb: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8181a230)
Location: drivers/watchdog/watchdog_core.c:252
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff8181a230-ffffffff8181a29b: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:261
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff8185c561-ffffffff8185c596: watchdog_register_device.cold (STB_LOCAL)
ffffffff8185c390-ffffffff8185c416: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff8188e155-ffffffff8188e18a: watchdog_register_device.cold (STB_LOCAL)
ffffffff8188df50-ffffffff8188dfd6: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:305
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff8195cd55-ffffffff8195cd8a: watchdog_register_device.cold (STB_LOCAL)
ffffffff8195cb50-ffffffff8195cbd6: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:309
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff81c25e4e-ffffffff81c25e83: watchdog_register_device.cold (STB_LOCAL)
ffffffff81963600-ffffffff81963686: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:309
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff81c17fd3-ffffffff81c18008: watchdog_register_device.cold (STB_LOCAL)
ffffffff81947a20-ffffffff81947aa6: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:346
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff81d27391-ffffffff81d273db: watchdog_register_device.cold (STB_LOCAL)
ffffffff819ec960-ffffffff819ec9f5: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:346
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff81ef322d-ffffffff81ef3277: watchdog_register_device.cold (STB_LOCAL)
ffffffff81b530a0-ffffffff81b53140: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:350
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff820a7d49-ffffffff820a7d5e: watchdog_register_device.cold (STB_LOCAL)
ffffffff81cebad0-ffffffff81cebbca: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:350
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff82129127-ffffffff8212913c: watchdog_register_device.cold (STB_LOCAL)
ffffffff81d54720-ffffffff81d5481a: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:350
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff8220ab10-ffffffff8220ab25: watchdog_register_device.cold (STB_LOCAL)
ffffffff81e0b5f0-ffffffff81e0b6ea: watchdog_register_device (STB_GLOBAL)
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
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffff800010adea48)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffff800010adea48-ffff800010adeb04: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (c0bc054c)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
c0bc054c-c0bc0610: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (c000000000bc64c0)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
c000000000bc64c0-c000000000bc65c8: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffe0006d6afa)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffe0006d6afa-ffffffe0006d6ba6: watchdog_register_device (STB_GLOBAL)
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
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff81833fd5-ffffffff8183400a: watchdog_register_device.cold (STB_LOCAL)
ffffffff81833dd0-ffffffff81833e56: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff817fb665-ffffffff817fb69a: watchdog_register_device.cold (STB_LOCAL)
ffffffff817fb460-ffffffff817fb4e6: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff81883605-ffffffff8188363a: watchdog_register_device.cold (STB_LOCAL)
ffffffff81883400-ffffffff81883486: watchdog_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:293
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
**Symbols:**

```
ffffffff8189f0c5-ffffffff8189f0fa: watchdog_register_device.cold (STB_LOCAL)
ffffffff8189eec0-ffffffff8189ef46: watchdog_register_device (STB_GLOBAL)
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
