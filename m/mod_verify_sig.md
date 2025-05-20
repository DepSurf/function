# Function: <code>mod_verify_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, long unsigned int *_modlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff8110ac40)
Location: kernel/module_signing.c:41
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8110ac40-ffffffff8110acf1: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, long unsigned int *_modlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff81112300)
Location: kernel/module_signing.c:48
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81112300-ffffffff81112424: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, long unsigned int *_modlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff81119a80)
Location: kernel/module_signing.c:48
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81119a80-ffffffff81119b49: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, long unsigned int *_modlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff8111b590)
Location: kernel/module_signing.c:48
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8111b590-ffffffff8111b649: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, long unsigned int *_modlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff81126b10)
Location: kernel/module_signing.c:48
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81126b10-ffffffff81126bc9: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mod_verify_sig(const void *mod, long unsigned int *_modlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signing.c (0)
Location: kernel/module_signing.c:48
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81134a90-ffffffff81134abc: mod_verify_sig.cold.0 (STB_LOCAL)
ffffffff811349f0-ffffffff81134a90: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signing.c (0)
Location: kernel/module_signing.c:48
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81140275-ffffffff811402a7: mod_verify_sig.cold.0 (STB_LOCAL)
ffffffff811401d0-ffffffff81140275: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signing.c (0)
Location: kernel/module_signing.c:44
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8114b650-ffffffff8114b682: mod_verify_sig.cold (STB_LOCAL)
ffffffff8114b560-ffffffff8114b650: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff811571f0)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811571f0-ffffffff811572d6: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff81167d70)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81167d70-ffffffff81167e57: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff81164390)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81164390-ffffffff81164476: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff81165170)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81165170-ffffffff81165256: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff8118a890)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8118a890-ffffffff8118a976: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/signing.c (ffffffff81190890)
Location: kernel/module/signing.c:43
Inline: False
Direct callers:
  - kernel/module/signing.c:module_sig_check
```
**Symbols:**

```
ffffffff81190890-ffffffff81190990: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/signing.c (ffffffff811cdde0)
Location: kernel/module/signing.c:43
Inline: False
Direct callers:
  - kernel/module/signing.c:module_sig_check
```
**Symbols:**

```
ffffffff811cdde0-ffffffff811cdee1: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/signing.c (ffffffff811e1e90)
Location: kernel/module/signing.c:43
Inline: False
Direct callers:
  - kernel/module/signing.c:module_sig_check
```
**Symbols:**

```
ffffffff811e1e90-ffffffff811e1f91: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/signing.c (ffffffff811f7bf0)
Location: kernel/module/signing.c:43
Inline: False
Direct callers:
  - kernel/module/signing.c:module_sig_check
```
**Symbols:**

```
ffffffff811f7bf0-ffffffff811f7cf1: mod_verify_sig (STB_GLOBAL)
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
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffff8000101c64f8)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffff8000101c64f8-ffff8000101c6604: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (c040d46c)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
c040d46c-c040d580: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (c00000000022e1d0)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
c00000000022e1d0-c00000000022e334: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffe000146a2c)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffe000146a2c-ffffffe000146b5a: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff8114f810)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8114f810-ffffffff8114f8f6: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff81142ac0)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81142ac0-ffffffff81142ba6: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff8114d6c0)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8114d6c0-ffffffff8114d7a6: mod_verify_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mod_verify_sig(const void *mod, struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signing.c (ffffffff8115a4a0)
Location: kernel/module_signing.c:20
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8115a4a0-ffffffff8115a586: mod_verify_sig (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct load_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *_modlen</code>
</li>
</ul>
</details>
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
