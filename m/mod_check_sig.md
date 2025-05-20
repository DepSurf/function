# Function: <code>mod_check_sig</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff8115732c-ffffffff8115735e: mod_check_sig.cold (STB_LOCAL)
ffffffff811572e0-ffffffff8115732c: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81167eac-ffffffff81167ede: mod_check_sig.cold (STB_LOCAL)
ffffffff81167e60-ffffffff81167eac: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81be43f2-ffffffff81be4424: mod_check_sig.cold (STB_LOCAL)
ffffffff81164480-ffffffff811644cc: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81bd6313-ffffffff81bd6345: mod_check_sig.cold (STB_LOCAL)
ffffffff81165260-ffffffff811652ac: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81cb2b3b-ffffffff81cb2b6d: mod_check_sig.cold (STB_LOCAL)
ffffffff8118a980-ffffffff8118a9cc: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module/signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81e63971-ffffffff81e639a3: mod_check_sig.cold (STB_LOCAL)
ffffffff811b9a70-ffffffff811b9ac4: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signature.c (ffffffff811fb0b0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module/signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff811fb0b0-ffffffff811fb140: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signature.c (ffffffff81210450)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module/signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81210450-ffffffff812104e0: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signature.c (ffffffff81227ad0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module/signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81227ad0-ffffffff81227b60: mod_check_sig (STB_GLOBAL)
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
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signature.c (ffff8000101c6608)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffff8000101c6608-ffff8000101c66ac: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signature.c (c040d580)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
c040d580-c040d610: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signature.c (c00000000022e340)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
c00000000022e340-c00000000022e410: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module_signature.c (ffffffe000146b5a)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffe000146b5a-ffffffe000146c0a: mod_check_sig (STB_GLOBAL)
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
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff8114f94c-ffffffff8114f97e: mod_check_sig.cold (STB_LOCAL)
ffffffff8114f900-ffffffff8114f94c: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81142bfc-ffffffff81142c2e: mod_check_sig.cold (STB_LOCAL)
ffffffff81142bb0-ffffffff81142bfc: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff8114d7fc-ffffffff8114d82e: mod_check_sig.cold (STB_LOCAL)
ffffffff8114d7b0-ffffffff8114d7fc: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mod_check_sig(const struct module_signature *ms, size_t file_len, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module_signature.c (0)
Location: kernel/module_signature.c:21
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff8115a5dc-ffffffff8115a60e: mod_check_sig.cold (STB_LOCAL)
ffffffff8115a590-ffffffff8115a5dc: mod_check_sig (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
