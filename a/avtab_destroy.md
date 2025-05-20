# Function: <code>avtab_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8134f7d0)
Location: security/selinux/ss/avtab.c:279
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff8134f7d0-ffffffff8134f882: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81385810)
Location: security/selinux/ss/avtab.c:279
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff81385810-ffffffff813858c2: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8139c2a0)
Location: security/selinux/ss/avtab.c:279
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff8139c2a0-ffffffff8139c352: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff813b321f)
Location: security/selinux/ss/avtab.c:279
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff813b2490-ffffffff813b2521: avtab_destroy.part.2 (STB_LOCAL)
ffffffff813b2a70-ffffffff813b2a8d: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff813d936f)
Location: security/selinux/ss/avtab.c:279
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff813d85d0-ffffffff813d8661: avtab_destroy.part.2 (STB_LOCAL)
ffffffff813d8bb0-ffffffff813d8bcd: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81409877)
Location: security/selinux/ss/avtab.c:279
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff81408be0-ffffffff81408c71: avtab_destroy.part.3 (STB_LOCAL)
ffffffff814091d0-ffffffff814091ec: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81425bb7)
Location: security/selinux/ss/avtab.c:279
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff81424ea0-ffffffff81424f31: avtab_destroy.part.3 (STB_LOCAL)
ffffffff81425490-ffffffff814254ac: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff814535eb)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff81452a10-ffffffff81452aa1: avtab_destroy.part.0 (STB_LOCAL)
ffffffff81452f50-ffffffff81452f66: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8146d38b)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff8146c7b0-ffffffff8146c841: avtab_destroy.part.0 (STB_LOCAL)
ffffffff8146ccf0-ffffffff8146cd06: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff814c1b8b)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff814c0e60-ffffffff814c0ef1: avtab_destroy.part.0 (STB_LOCAL)
ffffffff814c14c0-ffffffff814c14d6: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff814df7bb)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_duplicate
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_duplicate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy_dup
  - security/selinux/ss/conditional.c:duplicate_policydb_cond_list
```
**Symbols:**

```
ffffffff814de910-ffffffff814de9a1: avtab_destroy.part.0 (STB_LOCAL)
ffffffff814def70-ffffffff814def86: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff814e60bb)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_destroy_dup
```
**Symbols:**

```
ffffffff814e52e0-ffffffff814e5379: avtab_destroy.part.0 (STB_LOCAL)
ffffffff814e5980-ffffffff814e5996: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8153f91b)
Location: security/selinux/ss/avtab.c:279
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff8153e9d0-ffffffff8153ea69: avtab_destroy.part.0 (STB_LOCAL)
ffffffff8153f070-ffffffff8153f086: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff815d7659)
Location: security/selinux/ss/avtab.c:279
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff815d6680-ffffffff815d6723: avtab_destroy.part.0 (STB_LOCAL)
ffffffff815d6d20-ffffffff815d6d42: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81685bad)
Location: security/selinux/ss/avtab.c:279
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff81684aa0-ffffffff81684b43: avtab_destroy.part.0 (STB_LOCAL)
ffffffff816851a0-ffffffff816851c2: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816bdf0d)
Location: security/selinux/ss/avtab.c:279
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff816bce10-ffffffff816bceb3: avtab_destroy.part.0 (STB_LOCAL)
ffffffff816bd520-ffffffff816bd542: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816fa7bd)
Location: security/selinux/ss/avtab.c:223
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff816f98e0-ffffffff816f9980: avtab_destroy.part.0 (STB_LOCAL)
ffffffff816f9e80-ffffffff816f9ea2: avtab_destroy (STB_GLOBAL)
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
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffff80001055c508)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffff80001055b6d0-ffff80001055b788: avtab_destroy.part.0 (STB_LOCAL)
ffff80001055bda8-ffff80001055bdd8: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (c0710ca0)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
c070fd64-c070fe0c: avtab_destroy.part.0 (STB_LOCAL)
c0710500-c0710524: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (c0000000006bbc34)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
c0000000006ba9b0-c0000000006baac4: avtab_destroy.part.0 (STB_LOCAL)
c0000000006bb260-c0000000006bb27c: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffe0003b31f6)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffe0003b23ac-ffffffe0003b2470: avtab_destroy.part.0 (STB_LOCAL)
ffffffe0003b2aec-ffffffe0003b2b18: avtab_destroy (STB_GLOBAL)
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
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8146596b)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff81464d90-ffffffff81464e21: avtab_destroy.part.0 (STB_LOCAL)
ffffffff814652d0-ffffffff814652e6: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8145639b)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff814557c0-ffffffff81455851: avtab_destroy.part.0 (STB_LOCAL)
ffffffff81455d00-ffffffff81455d16: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81461a0b)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff81460e30-ffffffff81460ec1: avtab_destroy.part.0 (STB_LOCAL)
ffffffff81461370-ffffffff81461386: avtab_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void avtab_destroy(struct avtab *h);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8147920b)
Location: security/selinux/ss/avtab.c:277
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/conditional.c:cond_policydb_destroy
```
**Symbols:**

```
ffffffff81478630-ffffffff814786c1: avtab_destroy.part.0 (STB_LOCAL)
ffffffff81478b70-ffffffff81478b86: avtab_destroy (STB_GLOBAL)
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
