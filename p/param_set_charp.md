# Function: <code>param_set_charp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8109f280)
Location: kernel/params.c:300
Inline: True
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff8109f280-ffffffff8109f374: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a29d0)
Location: kernel/params.c:300
Inline: True
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810a29d0-ffffffff810a2ac9: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a7a90)
Location: kernel/params.c:300
Inline: True
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810a7a90-ffffffff810a7b89: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a46b0)
Location: kernel/params.c:248
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810a46b0-ffffffff810a47aa: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810aad00)
Location: kernel/params.c:256
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810aad00-ffffffff810aadfa: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:256
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810b2965-ffffffff810b297f: param_set_charp.cold.17 (STB_LOCAL)
ffffffff810b2120-ffffffff810b2203: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:256
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810bba5b-ffffffff810bba75: param_set_charp.cold.15 (STB_LOCAL)
ffffffff810bb240-ffffffff810bb31f: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:244
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810c191a-ffffffff810c1933: param_set_charp.cold (STB_LOCAL)
ffffffff810c1140-ffffffff810c121c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810c7d44-ffffffff810c7d5d: param_set_charp.cold (STB_LOCAL)
ffffffff810c7650-ffffffff810c772c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810cfdfa-ffffffff810cfe13: param_set_charp.cold (STB_LOCAL)
ffffffff810cf570-ffffffff810cf64c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:246
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff81bdc1ca-ffffffff81bdc1e3: param_set_charp.cold (STB_LOCAL)
ffffffff810ca0c0-ffffffff810ca19c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:246
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff81bce302-ffffffff81bce31b: param_set_charp.cold (STB_LOCAL)
ffffffff810cbc80-ffffffff810cbd5c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:264
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff81ca5640-ffffffff81ca5659: param_set_charp.cold (STB_LOCAL)
ffffffff810dee80-ffffffff810def5c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:264
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff81e54e09-ffffffff81e54e22: param_set_charp.cold (STB_LOCAL)
ffffffff810f82a0-ffffffff810f8379: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111acd0)
Location: kernel/params.c:264
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff8111acd0-ffffffff8111adbf: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81127f40)
Location: kernel/params.c:265
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff81127f40-ffffffff8112802f: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81132540)
Location: kernel/params.c:262
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff81132540-ffffffff8113264f: param_set_charp (STB_GLOBAL)
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
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffff8000101267b8)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffff8000101267b8-ffff80001012691c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c0378e5c)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
c0378e5c-c0378f54: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c0000000001706e0)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
c0000000001706e0-c00000000017088c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffe0000de194)
Location: kernel/params.c:245
Inline: True
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffe0000de194-ffffffe0000de2d2: param_set_charp (STB_GLOBAL)
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
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810c20c4-ffffffff810c20dd: param_set_charp.cold (STB_LOCAL)
ffffffff810c19d0-ffffffff810c1aac: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810b08e4-ffffffff810b08fd: param_set_charp.cold (STB_LOCAL)
ffffffff810b01c0-ffffffff810b029c: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810c1614-ffffffff810c162d: param_set_charp.cold (STB_LOCAL)
ffffffff810c0f20-ffffffff810c0ffc: param_set_charp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int param_set_charp(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:245
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
**Symbols:**

```
ffffffff810c99e4-ffffffff810c99fd: param_set_charp.cold (STB_LOCAL)
ffffffff810c8e10-ffffffff810c8eea: param_set_charp (STB_GLOBAL)
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
