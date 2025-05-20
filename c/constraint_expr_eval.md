# Function: <code>constraint_expr_eval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int constraint_expr_eval(struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81356510)
Location: security/selinux/ss/services.c:272
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:security_validate_transition
```
**Symbols:**

```
ffffffff81356510-ffffffff813569d8: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int constraint_expr_eval(struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138c240)
Location: security/selinux/ss/services.c:272
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff8138c240-ffffffff8138c787: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int constraint_expr_eval(struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a2e50)
Location: security/selinux/ss/services.c:272
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff813a2e50-ffffffff813a3397: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int constraint_expr_eval(struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813b9100)
Location: security/selinux/ss/services.c:284
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff813b9100-ffffffff813b95cc: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int constraint_expr_eval(struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813df280)
Location: security/selinux/ss/services.c:286
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff813df280-ffffffff813df758: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8140f630)
Location: security/selinux/ss/services.c:268
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff8140f630-ffffffff8140fb1f: constraint_expr_eval.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142b9d0)
Location: security/selinux/ss/services.c:265
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff8142b9d0-ffffffff8142bef7: constraint_expr_eval.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81458ca0)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff81458ca0-ffffffff814591f3: constraint_expr_eval.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81472a40)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff81472a40-ffffffff81472f93: constraint_expr_eval.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814c8930)
Location: security/selinux/ss/services.c:267
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff814c8930-ffffffff814c8e87: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e6fb0)
Location: security/selinux/ss/services.c:268
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff814e6fb0-ffffffff814e7507: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ecbb0)
Location: security/selinux/ss/services.c:270
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff814ecbb0-ffffffff814ed107: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81546d20)
Location: security/selinux/ss/services.c:270
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff81546d20-ffffffff8154753b: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e0040)
Location: security/selinux/ss/services.c:270
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff815e0040-ffffffff815e0894: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8168e8e0)
Location: security/selinux/ss/services.c:264
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff8168e8e0-ffffffff8168f134: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c64c0)
Location: security/selinux/ss/services.c:264
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff816c64c0-ffffffff816c6d1e: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81702f20)
Location: security/selinux/ss/services.c:264
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff81702f20-ffffffff8170377e: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105622d8)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffff8000105622d8-ffff800010562814: constraint_expr_eval.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int constraint_expr_eval(struct policydb *policydb, struct context *scontext, struct context *tcontext, struct context *xcontext, struct constraint_expr *cexpr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0716784)
Location: security/selinux/ss/services.c:262
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
c0716784-c0716d4c: constraint_expr_eval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c34a0)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
c0000000006c34a0-c0000000006c3c70: constraint_expr_eval.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003b9de2)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffe0003b9de2-ffffffe0003ba244: constraint_expr_eval.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146b020)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff8146b020-ffffffff8146b573: constraint_expr_eval.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145ba50)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff8145ba50-ffffffff8145bfa3: constraint_expr_eval.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814670c0)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff814670c0-ffffffff81467613: constraint_expr_eval.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8147e8a0)
Location: security/selinux/ss/services.c:262
Inline: True
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
```
**Symbols:**

```
ffffffff8147e8a0-ffffffff8147edf3: constraint_expr_eval.isra.0 (STB_LOCAL)
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
</ul>
