# Function: <code>pwm_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8142c9c0)
Location: drivers/pwm/core.c:679
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff8142c9c0-ffffffff8142cbca: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81477950)
Location: drivers/pwm/core.c:756
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81477950-ffffffff81477b54: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81498cb0)
Location: drivers/pwm/core.c:758
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81498cb0-ffffffff81498eb4: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814a2ad0)
Location: drivers/pwm/core.c:762
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff814a2ad0-ffffffff814a2c99: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814e1840)
Location: drivers/pwm/core.c:762
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff814e1840-ffffffff814e1a09: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81511030)
Location: drivers/pwm/core.c:762
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81511030-ffffffff815111fa: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff815266e0)
Location: drivers/pwm/core.c:762
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff815266e0-ffffffff815268aa: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:869
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81556038-ffffffff8155607d: pwm_get.cold (STB_LOCAL)
ffffffff815556d0-ffffffff81555941: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:870
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81577662-ffffffff815776a7: pwm_get.cold (STB_LOCAL)
ffffffff81576d10-ffffffff81576f81: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:998
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff8161c5ce-ffffffff8161c610: pwm_get.cold (STB_LOCAL)
ffffffff8161c0f0-ffffffff8161c392: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:998
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81bf6cbb-ffffffff81bf6cfd: pwm_get.cold (STB_LOCAL)
ffffffff816428c0-ffffffff81642b66: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:968
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81be8b27-ffffffff81be8b6c: pwm_get.cold (STB_LOCAL)
ffffffff816256e0-ffffffff81625982: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:927
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81ce2d18-ffffffff81ce2d5c: pwm_get.cold (STB_LOCAL)
ffffffff81694fb0-ffffffff8169526b: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:981
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81ea980b-ffffffff81ea984d: pwm_get.cold (STB_LOCAL)
ffffffff817b5c10-ffffffff817b5ed0: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818cffe0)
Location: drivers/pwm/core.c:909
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff818cffe0-ffffffff818d02dd: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81912f70)
Location: drivers/pwm/core.c:852
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff81912f70-ffffffff8191326d: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8195aeb0)
Location: drivers/pwm/core.c:836
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff8195aeb0-ffffffff8195b1a9: pwm_get (STB_GLOBAL)
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
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffff8000106d8c50)
Location: drivers/pwm/core.c:870
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffff8000106d8c50-ffff8000106d8f1c: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c08754bc)
Location: drivers/pwm/core.c:870
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
c08754bc-c08756fc: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c00000000084fa50)
Location: drivers/pwm/core.c:870
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
c00000000084fa50-c000000000850024: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffe0004b1b40)
Location: drivers/pwm/core.c:870
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffe0004b1b40-ffffffe0004b1cf4: pwm_get (STB_GLOBAL)
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
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:870
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff8156c472-ffffffff8156c4b7: pwm_get.cold (STB_LOCAL)
ffffffff8156bb20-ffffffff8156bd91: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:870
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff8156b3b2-ffffffff8156b3f7: pwm_get.cold (STB_LOCAL)
ffffffff8156aa60-ffffffff8156acd1: pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pwm_device *pwm_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:870
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_get
```
**Symbols:**

```
ffffffff815858b2-ffffffff815858f7: pwm_get.cold (STB_LOCAL)
ffffffff81584f60-ffffffff815851d1: pwm_get (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
