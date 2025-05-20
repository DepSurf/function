# Function: <code>security_prepare_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e270)
Location: security/security.c:877
Inline: False
Direct callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff8133e270-ffffffff8133e2cb: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813738d0)
Location: security/security.c:899
Inline: False
Direct callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff813738d0-ffffffff8137392b: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a200)
Location: security/security.c:920
Inline: False
Direct callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff8138a200-ffffffff8138a25b: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f6c0)
Location: security/security.c:1552
Inline: False
Direct callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff8139f6c0-ffffffff8139f744: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5240)
Location: security/security.c:1511
Inline: False
Direct callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff813c5240-ffffffff813c52fb: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f53c0)
Location: security/security.c:1016
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff813f53c0-ffffffff813f540e: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410900)
Location: security/security.c:1595
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff81410900-ffffffff814109e4: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e0a0)
Location: security/security.c:1614
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff8143e0a0-ffffffff8143e189: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457b40)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff81457b40-ffffffff81457c22: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aaa00)
Location: security/security.c:1826
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff814aaa00-ffffffff814aaa96: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8000)
Location: security/security.c:1828
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff814c8000-ffffffff814c8096: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce640)
Location: security/security.c:1878
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff814ce640-ffffffff814ce6d6: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527300)
Location: security/security.c:1886
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff81527300-ffffffff81527396: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc020)
Location: security/security.c:1891
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff815bc020-ffffffff815bc104: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81667f20)
Location: security/security.c:1938
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff81667f20-ffffffff81668004: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0540)
Location: security/security.c:3081
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff816a0540-ffffffff816a0624: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dcf50)
Location: security/security.c:3147
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff816dcf50-ffffffff816dd043: security_prepare_creds (STB_GLOBAL)
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
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543810)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffff800010543810-ffff8000105438f4: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9788)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
c06f9788-c06f9860: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697a60)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
c000000000697a60-c000000000697bc8: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039fcce)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffe00039fcce-ffffffe00039fd86: security_prepare_creds (STB_GLOBAL)
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
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450120)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff81450120-ffffffff81450202: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440b70)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff81440b70-ffffffff81440c52: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c1c0)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff8144c1c0-ffffffff8144c2a2: security_prepare_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_prepare_creds(struct cred *new, const struct cred *old, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463590)
Location: security/security.c:1653
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
**Symbols:**

```
ffffffff81463590-ffffffff81463672: security_prepare_creds (STB_GLOBAL)
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
