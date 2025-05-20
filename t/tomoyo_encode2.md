# Function: <code>tomoyo_encode2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff81372930)
Location: security/tomoyo/realpath.c:21
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff81372930-ffffffff81372a37: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813a8d50)
Location: security/tomoyo/realpath.c:21
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff813a8d50-ffffffff813a8e57: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813bf8d0)
Location: security/tomoyo/realpath.c:21
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff813bf8d0-ffffffff813bf9d7: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813d62d7)
Location: security/tomoyo/realpath.c:21
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff813d61a0-ffffffff813d629e: tomoyo_encode2.part.2 (STB_LOCAL)
ffffffff813d62a0-ffffffff813d62b8: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813fc7f7)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff813fc6c0-ffffffff813fc7be: tomoyo_encode2.part.2 (STB_LOCAL)
ffffffff813fc7c0-ffffffff813fc7d8: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8142d727)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff8142d5f0-ffffffff8142d6ee: tomoyo_encode2.part.2 (STB_LOCAL)
ffffffff8142d6f0-ffffffff8142d708: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8144a077)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff81449f40-ffffffff8144a03e: tomoyo_encode2.part.2 (STB_LOCAL)
ffffffff8144a040-ffffffff8144a058: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff81477cee)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff81477bb0-ffffffff81477cae: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff81477cb0-ffffffff81477cc8: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff81491a8e)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff81491950-ffffffff81491a4e: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff81491a50-ffffffff81491a68: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff814e8e7e)
Location: security/tomoyo/realpath.c:23
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff814e8d40-ffffffff814e8e3c: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff814e8e40-ffffffff814e8e58: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff815061be)
Location: security/tomoyo/realpath.c:23
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff81506080-ffffffff8150617c: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff81506180-ffffffff81506198: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8150ccf8)
Location: security/tomoyo/realpath.c:23
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff8150cbc0-ffffffff8150ccb5: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff8150ccc0-ffffffff8150ccd8: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8156a828)
Location: security/tomoyo/realpath.c:23
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff8156a6f0-ffffffff8156a7e5: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff8156a7f0-ffffffff8156a808: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff816066a0)
Location: security/tomoyo/realpath.c:23
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff816066a0-ffffffff816067b6: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff816b7b40)
Location: security/tomoyo/realpath.c:23
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff816b7b40-ffffffff816b7c56: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff816f0510)
Location: security/tomoyo/realpath.c:23
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff816f0510-ffffffff816f0626: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8172d2e0)
Location: security/tomoyo/realpath.c:23
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff8172d2e0-ffffffff8172d3f6: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffff8000105861dc)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffff800010586030-ffff800010586174: tomoyo_encode2.part.0 (STB_LOCAL)
ffff800010586178-ffff8000105861b8: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (c0737ae0)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
c0737994-c0737a94: tomoyo_encode2.part.0 (STB_LOCAL)
c0737a94-c0737ac0: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (c0000000006f5ec0)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
c0000000006f5cd0-c0000000006f5e70: tomoyo_encode2.part.0 (STB_LOCAL)
c0000000006f5e70-c0000000006f5e8c: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffe0003d5b9c)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffe0003d5a28-ffffffe0003d5b40: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffe0003d5b40-ffffffe0003d5b78: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8148a06e)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff81489f30-ffffffff8148a02e: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff8148a030-ffffffff8148a048: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8147aa8e)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff8147a950-ffffffff8147aa4e: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff8147aa50-ffffffff8147aa68: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8148610e)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff81485fd0-ffffffff814860ce: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff814860d0-ffffffff814860e8: tomoyo_encode2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *tomoyo_encode2(const char *str, int str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8149dc4e)
Location: security/tomoyo/realpath.c:22
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_encode
Direct callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/realpath.c:tomoyo_encode
```
**Symbols:**

```
ffffffff8149db10-ffffffff8149dc0e: tomoyo_encode2.part.0 (STB_LOCAL)
ffffffff8149dc10-ffffffff8149dc28: tomoyo_encode2 (STB_GLOBAL)
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
