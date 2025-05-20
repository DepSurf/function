# Function: <code>param_set_copystring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8109eee0)
Location: kernel/params.c:545
Inline: False
```
**Symbols:**

```
ffffffff8109eee0-ffffffff8109ef3c: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a25a0)
Location: kernel/params.c:545
Inline: False
```
**Symbols:**

```
ffffffff810a25a0-ffffffff810a25fc: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a7660)
Location: kernel/params.c:545
Inline: False
```
**Symbols:**

```
ffffffff810a7660-ffffffff810a76bc: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a4650)
Location: kernel/params.c:493
Inline: False
```
**Symbols:**

```
ffffffff810a4650-ffffffff810a46ac: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810aaca0)
Location: kernel/params.c:502
Inline: False
```
**Symbols:**

```
ffffffff810aaca0-ffffffff810aacfc: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:502
Inline: False
```
**Symbols:**

```
ffffffff810b28e8-ffffffff810b2905: param_set_copystring.cold.14 (STB_LOCAL)
ffffffff810b1860-ffffffff810b18a6: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:502
Inline: False
```
**Symbols:**

```
ffffffff810bba18-ffffffff810bba35: param_set_copystring.cold.13 (STB_LOCAL)
ffffffff810ba9a0-ffffffff810ba9e6: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:490
Inline: False
```
**Symbols:**

```
ffffffff810c18d8-ffffffff810c18f4: param_set_copystring.cold (STB_LOCAL)
ffffffff810c08c0-ffffffff810c0905: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
ffffffff810c7cc8-ffffffff810c7ce4: param_set_copystring.cold (STB_LOCAL)
ffffffff810c6cc0-ffffffff810c6d05: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:491
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
**Symbols:**

```
ffffffff810cfd78-ffffffff810cfd94: param_set_copystring.cold (STB_LOCAL)
ffffffff810cecc0-ffffffff810ced05: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:492
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
**Symbols:**

```
ffffffff81bdc148-ffffffff81bdc164: param_set_copystring.cold (STB_LOCAL)
ffffffff810c97f0-ffffffff810c9835: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:492
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
**Symbols:**

```
ffffffff81bce26d-ffffffff81bce289: param_set_copystring.cold (STB_LOCAL)
ffffffff810cb300-ffffffff810cb345: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:510
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
**Symbols:**

```
ffffffff81ca54f0-ffffffff81ca550c: param_set_copystring.cold (STB_LOCAL)
ffffffff810de460-ffffffff810de4a5: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:510
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
**Symbols:**

```
ffffffff81e54dec-ffffffff81e54e09: param_set_copystring.cold (STB_LOCAL)
ffffffff810f8240-ffffffff810f8291: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111ac50)
Location: kernel/params.c:510
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
**Symbols:**

```
ffffffff8111ac50-ffffffff8111acb7: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81127ec0)
Location: kernel/params.c:511
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
**Symbols:**

```
ffffffff81127ec0-ffffffff81127f27: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff811324a0)
Location: kernel/params.c:513
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
**Symbols:**

```
ffffffff811324a0-ffffffff81132526: param_set_copystring (STB_GLOBAL)
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
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffff800010125b48)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
ffff800010125b48-ffff800010125bc0: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c0378860)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
c0378860-c03788c4: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c00000000016fbf0)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
c00000000016fbf0-c00000000016fc80: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffe0000dd77a)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
ffffffe0000dd77a-ffffffe0000dd7f0: param_set_copystring (STB_GLOBAL)
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
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
ffffffff810c2048-ffffffff810c2064: param_set_copystring.cold (STB_LOCAL)
ffffffff810c1040-ffffffff810c1085: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
ffffffff810b0868-ffffffff810b0884: param_set_copystring.cold (STB_LOCAL)
ffffffff810af830-ffffffff810af875: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
ffffffff810c1598-ffffffff810c15b4: param_set_copystring.cold (STB_LOCAL)
ffffffff810c0590-ffffffff810c05d5: param_set_copystring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int param_set_copystring(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:491
Inline: False
```
**Symbols:**

```
ffffffff810c99c8-ffffffff810c99e4: param_set_copystring.cold (STB_LOCAL)
ffffffff810c8a60-ffffffff810c8aa5: param_set_copystring (STB_GLOBAL)
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
