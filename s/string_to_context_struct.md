# Function: <code>string_to_context_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, u32 scontext_len, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81356050)
Location: security/selinux/ss/services.c:1315
Inline: False
```
**Symbols:**

```
ffffffff81356050-ffffffff81356299: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, u32 scontext_len, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138bd70)
Location: security/selinux/ss/services.c:1309
Inline: False
```
**Symbols:**

```
ffffffff8138bd70-ffffffff8138bfb9: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, u32 scontext_len, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a2980)
Location: security/selinux/ss/services.c:1309
Inline: False
```
**Symbols:**

```
ffffffff813a2980-ffffffff813a2bc9: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, u32 scontext_len, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813b8eb0)
Location: security/selinux/ss/services.c:1321
Inline: False
```
**Symbols:**

```
ffffffff813b8eb0-ffffffff813b90fd: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, u32 scontext_len, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813df030)
Location: security/selinux/ss/services.c:1326
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff813df030-ffffffff813df27d: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, u32 scontext_len, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8140f3e0)
Location: security/selinux/ss/services.c:1367
Inline: False
```
**Symbols:**

```
ffffffff8140f3e0-ffffffff8140f62e: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142c190)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff8142c190-ffffffff8142c382: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81459200)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff81459200-ffffffff8145940b: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81472fa0)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff81472fa0-ffffffff814731ab: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814c8720)
Location: security/selinux/ss/services.c:1415
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff814c8720-ffffffff814c892f: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e6510)
Location: security/selinux/ss/services.c:1432
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff814e6510-ffffffff814e6719: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ec9a0)
Location: security/selinux/ss/services.c:1434
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff814ec9a0-ffffffff814ecba9: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81546b10)
Location: security/selinux/ss/services.c:1438
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff81546b10-ffffffff81546d19: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815df390)
Location: security/selinux/ss/services.c:1436
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff815df390-ffffffff815df5a0: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8168f870)
Location: security/selinux/ss/services.c:1430
Inline: False
Direct callers:
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff8168f870-ffffffff8168fa7e: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c7cf0)
Location: security/selinux/ss/services.c:1415
Inline: False
Direct callers:
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff816c7cf0-ffffffff816c7efe: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81704900)
Location: security/selinux/ss/services.c:1426
Inline: False
Direct callers:
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff81704900-ffffffff81704b0e: string_to_context_struct (STB_LOCAL)
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
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010562818)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffff800010562818-ffff8000105629d8: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0716d4c)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
c0716d4c-c0716f24: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c3c70)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
c0000000006c3c70-c0000000006c3f50: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003b920a)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffe0003b920a-ffffffe0003b939a: string_to_context_struct (STB_LOCAL)
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
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146b580)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff8146b580-ffffffff8146b78b: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145bfb0)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff8145bfb0-ffffffff8145c1bb: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81467620)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff81467620-ffffffff8146782b: string_to_context_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int string_to_context_struct(struct policydb *pol, struct sidtab *sidtabp, char *scontext, struct context *ctx, u32 def_sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8147ee00)
Location: security/selinux/ss/services.c:1374
Inline: False
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff8147ee00-ffffffff8147f00b: string_to_context_struct (STB_LOCAL)
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
<b>Param removed. </b>
<code>u32 scontext_len</code>
</li>
<li>
<b>Param reordered. </b>
<code>pol, sidtabp, scontext, scontext_len, ctx, def_sid</code> ➡️ <code>pol, sidtabp, scontext, ctx, def_sid</code>
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
