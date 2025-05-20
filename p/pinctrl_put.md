# Function: <code>pinctrl_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141dfd6)
Location: drivers/pinctrl/core.c:950
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8141e1d0-ffffffff8141e1ef: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814666ea)
Location: drivers/pinctrl/core.c:963
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81466900-ffffffff8146691f: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814859da)
Location: drivers/pinctrl/core.c:963
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81485bf0-ffffffff81485c0f: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148e680)
Location: drivers/pinctrl/core.c:1160
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8148e680-ffffffff8148e69d: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814cb896)
Location: drivers/pinctrl/core.c:1160
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff814cb870-ffffffff814cb890: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fc845)
Location: drivers/pinctrl/core.c:1160
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff814fc810-ffffffff814fc835: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815112a5)
Location: drivers/pinctrl/core.c:1188
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81511270-ffffffff81511295: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8153f8a5)
Location: drivers/pinctrl/core.c:1164
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8153f870-ffffffff8153f894: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81560745)
Location: drivers/pinctrl/core.c:1192
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81560710-ffffffff81560734: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81602d7e)
Location: drivers/pinctrl/core.c:1193
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81602d30-ffffffff81602d6d: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81627c8e)
Location: drivers/pinctrl/core.c:1194
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81627c40-ffffffff81627c7d: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8160b76e)
Location: drivers/pinctrl/core.c:1194
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8160b720-ffffffff8160b75d: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8167a47e)
Location: drivers/pinctrl/core.c:1194
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8167a430-ffffffff8167a46d: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81795a7e)
Location: drivers/pinctrl/core.c:1194
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81795a00-ffffffff81795a61: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818aad7e)
Location: drivers/pinctrl/core.c:1194
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff818aacf0-ffffffff818aad51: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818edc5e)
Location: drivers/pinctrl/core.c:1198
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff818edbd0-ffffffff818edc31: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8193542e)
Location: drivers/pinctrl/core.c:1212
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff819353a0-ffffffff81935401: pinctrl_put (STB_GLOBAL)
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
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068bcb0)
Location: drivers/pinctrl/core.c:1192
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffff80001068bcb0-ffff80001068bcf0: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082df9c)
Location: drivers/pinctrl/core.c:1192
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
c082df9c-c082dfd4: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000824900)
Location: drivers/pinctrl/core.c:1192
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
c000000000824900-c000000000824940: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000499450)
Location: drivers/pinctrl/core.c:1192
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffe0004993f0-ffffffe000499438: pinctrl_put (STB_GLOBAL)
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
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81558d35)
Location: drivers/pinctrl/core.c:1192
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81558d00-ffffffff81558d24: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815491f5)
Location: drivers/pinctrl/core.c:1192
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff815491c0-ffffffff815491e4: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81554a75)
Location: drivers/pinctrl/core.c:1192
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81554a40-ffffffff81554a64: pinctrl_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_put(struct pinctrl *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156e905)
Location: drivers/pinctrl/core.c:1192
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8156e8d0-ffffffff8156e8f4: pinctrl_put (STB_GLOBAL)
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
