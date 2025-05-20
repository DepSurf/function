# Function: <code>mls_convert_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8135c4c0)
Location: security/selinux/ss/mls.c:462
Inline: False
```
**Symbols:**

```
ffffffff8135c4c0-ffffffff8135c67b: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81392480)
Location: security/selinux/ss/mls.c:462
Inline: False
```
**Symbols:**

```
ffffffff81392480-ffffffff81392667: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813a90b0)
Location: security/selinux/ss/mls.c:462
Inline: False
```
**Symbols:**

```
ffffffff813a90b0-ffffffff813a9297: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813bfb60)
Location: security/selinux/ss/mls.c:462
Inline: False
```
**Symbols:**

```
ffffffff813bfb60-ffffffff813bfd1d: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813e5d00)
Location: security/selinux/ss/mls.c:463
Inline: False
```
**Symbols:**

```
ffffffff813e5d00-ffffffff813e5ebd: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814168e0)
Location: security/selinux/ss/mls.c:466
Inline: False
```
**Symbols:**

```
ffffffff814168e0-ffffffff81416ab7: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81432e10)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff81432e10-ffffffff81432fae: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81460850)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff81460850-ffffffff814609e6: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8147a600)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff8147a600-ffffffff8147a796: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814cfba0)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff814cfba0-ffffffff814cfd34: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814ed0d0)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff814ed0d0-ffffffff814ed264: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814f3e70)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff814f3e70-ffffffff814f400c: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8154e820)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff8154e820-ffffffff8154e9ba: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff815e7900)
Location: security/selinux/ss/mls.c:446
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff815e7900-ffffffff815e7ad6: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81696ff0)
Location: security/selinux/ss/mls.c:446
Inline: False
Direct callers:
  - security/selinux/ss/services.c:services_convert_context
```
**Symbols:**

```
ffffffff81696ff0-ffffffff816971b8: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff816cf500)
Location: security/selinux/ss/mls.c:446
Inline: False
Direct callers:
  - security/selinux/ss/services.c:services_convert_context
```
**Symbols:**

```
ffffffff816cf500-ffffffff816cf6c4: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8170bb20)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:services_convert_context
```
**Symbols:**

```
ffffffff8170bb20-ffffffff8170bce4: mls_convert_context (STB_GLOBAL)
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
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffff80001056abb0)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffff80001056abb0-ffff80001056ad70: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (c071e75c)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
c071e75c-c071e8e0: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (c0000000006ce820)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
c0000000006ce820-c0000000006cea98: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffe0003bfa3e)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffe0003bfa3e-ffffffe0003bfb84: mls_convert_context (STB_GLOBAL)
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
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81472be0)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff81472be0-ffffffff81472d76: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81463600)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff81463600-ffffffff81463796: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8146ec80)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff8146ec80-ffffffff8146ee16: mls_convert_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mls_convert_context(struct policydb *oldp, struct policydb *newp, struct context *oldc, struct context *newc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814864f0)
Location: security/selinux/ss/mls.c:447
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff814864f0-ffffffff81486686: mls_convert_context (STB_GLOBAL)
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
<code>struct context *oldc</code>
</li>
<li>
<b>Param added. </b>
<code>struct context *newc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct context *c</code>
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
