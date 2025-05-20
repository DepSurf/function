# Function: <code>mls_context_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char **scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8135be50)
Location: security/selinux/ss/mls.c:234
Inline: True
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff8135be50-ffffffff8135c17c: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char **scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81391e10)
Location: security/selinux/ss/mls.c:234
Inline: True
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff81391e10-ffffffff81392143: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char **scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813a8a40)
Location: security/selinux/ss/mls.c:234
Inline: True
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff813a8a40-ffffffff813a8d73: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char **scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813bf500)
Location: security/selinux/ss/mls.c:234
Inline: False
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff813bf500-ffffffff813bf835: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char **scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813e56a0)
Location: security/selinux/ss/mls.c:235
Inline: False
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff813e56a0-ffffffff813e59d5: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char **scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81416280)
Location: security/selinux/ss/mls.c:236
Inline: False
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff81416280-ffffffff814165b3: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff81432b3e)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff81432240-ffffffff81432445: mls_context_to_sid.part.5 (STB_LOCAL)
ffffffff81432a50-ffffffff81432b0d: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8146056f)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff8145fc80-ffffffff8145fe76: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff81460480-ffffffff81460534: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8147a31f)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff81479a30-ffffffff81479c26: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff8147a230-ffffffff8147a2e4: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814cf8bf)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff814cef80-ffffffff814cf20f: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff814cf860-ffffffff814cf88c: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814ecdef)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff814ec4c0-ffffffff814ec74f: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff814ecd90-ffffffff814ecdbc: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814f3b8f)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff814f3240-ffffffff814f34cf: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff814f3b30-ffffffff814f3b5c: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8154e53f)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff8154db40-ffffffff8154ddd4: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff8154e4e0-ffffffff8154e50c: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff815e72f0)
Location: security/selinux/ss/mls.c:233
Inline: False
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff815e72f0-ffffffff815e75db: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff816969a0)
Location: security/selinux/ss/mls.c:233
Inline: False
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff816969a0-ffffffff81696c8b: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff816ceea0)
Location: security/selinux/ss/mls.c:233
Inline: False
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff816ceea0-ffffffff816cf186: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8170b4c0)
Location: security/selinux/ss/mls.c:233
Inline: False
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff8170b4c0-ffffffff8170b7a9: mls_context_to_sid (STB_GLOBAL)
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
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffff80001056a8ac)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffff800010569ee0-ffff80001056a0f4: mls_context_to_sid.part.0 (STB_LOCAL)
ffff80001056a760-ffff80001056a864: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (c071e4b4)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
c071db90-c071dd94: mls_context_to_sid.part.0 (STB_LOCAL)
c071e398-c071e478: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (c0000000006ce418)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
c0000000006cd640-c0000000006cd92c: mls_context_to_sid.part.0 (STB_LOCAL)
c0000000006ce260-c0000000006ce3b4: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffe0003bf7ee)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffe0003bef64-ffffffe0003bf0ec: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffe0003bf6f4-ffffffe0003bf7b8: mls_context_to_sid (STB_GLOBAL)
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
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff814728ff)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff81472010-ffffffff81472206: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff81472810-ffffffff814728c4: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8146331f)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff81462a30-ffffffff81462c26: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff81463230-ffffffff814632e4: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8146e99f)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff8146e0b0-ffffffff8146e2a6: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff8146e8b0-ffffffff8146e964: mls_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mls_context_to_sid(struct policydb *pol, char oldc, char *scontext, struct context *context, struct sidtab *s, u32 def_sid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff8148620f)
Location: security/selinux/ss/mls.c:234
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_from_string
Direct callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_from_string
```
**Symbols:**

```
ffffffff81485920-ffffffff81485b16: mls_context_to_sid.part.0 (STB_LOCAL)
ffffffff81486120-ffffffff814861d4: mls_context_to_sid (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>char **scontext</code> ➡️ <code>char *scontext</code>
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
