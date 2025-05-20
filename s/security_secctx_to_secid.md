# Function: <code>security_secctx_to_secid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133b670)
Location: security/security.c:1161
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff8133b670-ffffffff8133b6d1: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370bf0)
Location: security/security.c:1185
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff81370bf0-ffffffff81370c51: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387520)
Location: security/security.c:1206
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff81387520-ffffffff81387581: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139c200)
Location: security/security.c:2124
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff8139c200-ffffffff8139c261: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c1930)
Location: security/security.c:1982
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff813c1930-ffffffff813c1997: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2f00)
Location: security/security.c:1310
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff813f2f00-ffffffff813f2f54: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f040)
Location: security/security.c:2061
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff8140f040-ffffffff8140f08e: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c420)
Location: security/security.c:2080
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff8143c420-ffffffff8143c46e: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455fa0)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff81455fa0-ffffffff81455fee: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8680)
Location: security/security.c:2379
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff814a8680-ffffffff814a871a: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5c10)
Location: security/security.c:2396
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff814c5c10-ffffffff814c5cab: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbef0)
Location: security/security.c:2459
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff814cbef0-ffffffff814cbf84: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524e70)
Location: security/security.c:2467
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff81524e70-ffffffff81524f04: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8e30)
Location: security/security.c:2497
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff815b8e30-ffffffff815b8ef9: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664520)
Location: security/security.c:2477
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff81664520-ffffffff816645e9: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c9f0)
Location: security/security.c:4153
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff8169c9f0-ffffffff8169cac5: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d7fe0)
Location: security/security.c:4323
Inline: False
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff816d7fe0-ffffffff816d8021: security_secctx_to_secid (STB_GLOBAL)
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
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541718)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffff800010541718-ffff800010541790: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7700)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
c06f7700-c06f7774: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693f90)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
c000000000693f90-c000000000694024: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e3b2)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffe00039e3b2-ffffffe00039e406: security_secctx_to_secid (STB_GLOBAL)
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
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e580)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff8144e580-ffffffff8144e5ce: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143efd0)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff8143efd0-ffffffff8143f01e: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a620)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff8144a620-ffffffff8144a66e: security_secctx_to_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int security_secctx_to_secid(const char *secdata, u32 seclen, u32 *secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814619f0)
Location: security/security.c:2119
Inline: True
Direct callers:
  - kernel/cred.c:set_security_override_from_ctx
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
**Symbols:**

```
ffffffff814619f0-ffffffff81461a3e: security_secctx_to_secid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *secid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *secid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lsmblob *blob</code>
</li>
</ul>
</details>
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
