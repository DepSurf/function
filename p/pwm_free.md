# Function: <code>pwm_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8142c800)
Location: drivers/pwm/core.c:425
Inline: False
```
**Symbols:**

```
ffffffff8142c800-ffffffff8142c810: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814777c0)
Location: drivers/pwm/core.c:443
Inline: False
```
**Symbols:**

```
ffffffff814777c0-ffffffff814777d0: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81498b20)
Location: drivers/pwm/core.c:445
Inline: False
```
**Symbols:**

```
ffffffff81498b20-ffffffff81498b30: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814a2e30)
Location: drivers/pwm/core.c:454
Inline: False
```
**Symbols:**

```
ffffffff814a2e30-ffffffff814a2e47: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814e1ba0)
Location: drivers/pwm/core.c:454
Inline: False
```
**Symbols:**

```
ffffffff814e1ba0-ffffffff814e1bb7: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81511390)
Location: drivers/pwm/core.c:454
Inline: False
```
**Symbols:**

```
ffffffff81511390-ffffffff815113a6: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81526aa0)
Location: drivers/pwm/core.c:454
Inline: False
```
**Symbols:**

```
ffffffff81526aa0-ffffffff81526ab6: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81555905)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81555690-ffffffff815556a6: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81576f45)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81576cd0-ffffffff81576ce6: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8161c359)
Location: drivers/pwm/core.c:461
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff8161b5c0-ffffffff8161b5d6: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81642b2d)
Location: drivers/pwm/core.c:461
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81641d30-ffffffff81641d46: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8162594c)
Location: drivers/pwm/core.c:431
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81624c10-ffffffff81624c26: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81694f6b)
Location: drivers/pwm/core.c:418
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81694460-ffffffff81694476: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b5bbc)
Location: drivers/pwm/core.c:444
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff817b52d0-ffffffff817b52f2: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818cff7c)
Location: drivers/pwm/core.c:440
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff818cf620-ffffffff818cf642: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffff8000106d8ef0)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
```
**Symbols:**

```
ffff8000106d8300-ffff8000106d8330: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c08756c8)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
```
**Symbols:**

```
c0875164-c0875188: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c000000000850004)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
```
**Symbols:**

```
c00000000084f480-c00000000084f49c: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffe0004b1ce0)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
```
**Symbols:**

```
ffffffe0004b17a4-ffffffe0004b17d0: pwm_free (STB_GLOBAL)
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
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156bd55)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff8156bae0-ffffffff8156baf6: pwm_free (STB_GLOBAL)
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
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156ac95)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff8156aa20-ffffffff8156aa36: pwm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pwm_free(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81585195)
Location: drivers/pwm/core.c:442
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81584f20-ffffffff81584f36: pwm_free (STB_GLOBAL)
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
