# Function: <code>aa_setprocattr_changehat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int test);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffff81382fe0)
Location: security/apparmor/procattr.c:105
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81382fe0-ffffffff8138322c: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int test);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffff813bd350)
Location: security/apparmor/procattr.c:105
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff813bd350-ffffffff813bd59c: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int test);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffff813d4780)
Location: security/apparmor/procattr.c:105
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff813d4780-ffffffff813d49cc: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffff813e74a0)
Location: security/apparmor/procattr.c:106
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff813e74a0-ffffffff813e771f: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffff8140e700)
Location: security/apparmor/procattr.c:106
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8140e700-ffffffff8140e971: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:106
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8144053d-ffffffff81440573: aa_setprocattr_changehat.cold.5 (STB_LOCAL)
ffffffff814402e0-ffffffff8144053d: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:106
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8145d422-ffffffff8145d458: aa_setprocattr_changehat.cold.5 (STB_LOCAL)
ffffffff8145d1d0-ffffffff8145d422: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8148a9a8-ffffffff8148a9de: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff8148a750-ffffffff8148a9a8: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff814a4868-ffffffff814a489e: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff814a4610-ffffffff814a4868: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff814ff79e-ffffffff814ff7d4: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff814ff540-ffffffff814ff79e: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81bf16e9-ffffffff81bf171f: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff8151c790-ffffffff8151c9ee: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81be36f9-ffffffff81be372f: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff81522fa0-ffffffff815231fe: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81cd659d-ffffffff81cd6608: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff81581210-ffffffff81581475: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81e8943e-ffffffff81e8949f: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff816203a0-ffffffff81620631: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffff816d37f0)
Location: security/apparmor/procattr.c:99
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff816d37f0-ffffffff816d3a8f: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffff8170c6c0)
Location: security/apparmor/procattr.c:99
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8170c6c0-ffffffff8170c92d: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffff8174a450)
Location: security/apparmor/procattr.c:101
Inline: False
Direct callers:
  - security/apparmor/lsm.c:do_setattr
  - security/apparmor/lsm.c:do_setattr
```
**Symbols:**

```
ffffffff8174a450-ffffffff8174a6bd: aa_setprocattr_changehat (STB_GLOBAL)
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
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffff80001059a3e0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffff80001059a3e0-ffff80001059a68c: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (c074b4f8)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
c074b4f8-c074b7d4: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (c0000000007119c0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
c0000000007119c0-c000000000711d6c: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/procattr.c (ffffffe0003e68f8)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffe0003e68f8-ffffffe0003e6b04: aa_setprocattr_changehat (STB_GLOBAL)
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
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8149ce48-ffffffff8149ce7e: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff8149cbf0-ffffffff8149ce48: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8148d868-ffffffff8148d89e: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff8148d610-ffffffff8148d868: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81498ee8-ffffffff81498f1e: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff81498c90-ffffffff81498ee8: aa_setprocattr_changehat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int aa_setprocattr_changehat(char *args, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/procattr.c (0)
Location: security/apparmor/procattr.c:102
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff814b1068-ffffffff814b109e: aa_setprocattr_changehat.cold (STB_LOCAL)
ffffffff814b0e10-ffffffff814b1068: aa_setprocattr_changehat (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int test</code>
</li>
</ul>
</details>
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
