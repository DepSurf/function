# Function: <code>is_module_sig_enforced</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811201d0)
Location: kernel/module.c:285
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_read_file
```
**Symbols:**

```
ffffffff811201d0-ffffffff811201e2: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81132558)
Location: kernel/module.c:284
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_read_file
```
**Symbols:**

```
ffffffff8112dc60-ffffffff8112dc72: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139550)
Location: kernel/module.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff81139550-ffffffff81139562: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811498df)
Location: kernel/module.c:275
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff81144720-ffffffff81144732: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81155557)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff81150200-ffffffff81150212: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81166aba)
Location: kernel/module.c:280
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff81160bf0-ffffffff81160c02: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163147)
Location: kernel/module.c:282
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8115cd20-ffffffff8115cd32: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163b6c)
Location: kernel/module.c:285
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8115df30-ffffffff8115df42: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8118923c)
Location: kernel/module.c:286
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff81cb2427-ffffffff81cb2447: is_module_sig_enforced.cold (STB_LOCAL)
ffffffff81183f60-ffffffff81183f78: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/signing.c (ffffffff811909af)
Location: kernel/module/signing.c:29
Inline: True
Inline callers:
  - kernel/module/signing.c:module_sig_check
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff81e61b96-ffffffff81e61bc0: is_module_sig_enforced.cold (STB_LOCAL)
ffffffff81190840-ffffffff81190862: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/signing.c (ffffffff811cdf1f)
Location: kernel/module/signing.c:29
Inline: True
Inline callers:
  - kernel/module/signing.c:module_sig_check
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8205abee-ffffffff8205ac18: is_module_sig_enforced.cold (STB_LOCAL)
ffffffff811cdd70-ffffffff811cdd92: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/signing.c (ffffffff811e1fcf)
Location: kernel/module/signing.c:29
Inline: True
Inline callers:
  - kernel/module/signing.c:module_sig_check
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff820d9490-ffffffff820d94ba: is_module_sig_enforced.cold (STB_LOCAL)
ffffffff811e1e20-ffffffff811e1e42: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/signing.c (ffffffff811f7d2f)
Location: kernel/module/signing.c:29
Inline: True
Inline callers:
  - kernel/module/signing.c:module_sig_check
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff821b4d11-ffffffff821b4d3b: is_module_sig_enforced.cold (STB_LOCAL)
ffffffff811f7b80-ffffffff811f7ba2: is_module_sig_enforced (STB_GLOBAL)
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
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c491c)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffff8000101bee98-ffff8000101beeb8: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040bcd4)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
c040674c-c0406770: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022bc30)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
c000000000223f10-c000000000223f2c: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001452a0)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffe000141096-ffffffe0001410b8: is_module_sig_enforced (STB_GLOBAL)
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
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114db77)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff81148820-ffffffff81148832: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81140e27)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8113bad0-ffffffff8113bae2: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114ba27)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff811466d0-ffffffff811466e2: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_module_sig_enforced();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81158717)
Location: kernel/module.c:277
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff811532e0-ffffffff811532f2: is_module_sig_enforced (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
