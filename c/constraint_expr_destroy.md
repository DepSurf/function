# Function: <code>constraint_expr_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void constraint_expr_destroy(struct constraint_expr *expr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813504f0)
Location: security/selinux/ss/policydb.c:630
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff813504f0-ffffffff8135053b: constraint_expr_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void constraint_expr_destroy(struct constraint_expr *expr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81386530)
Location: security/selinux/ss/policydb.c:630
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff81386530-ffffffff8138657b: constraint_expr_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void constraint_expr_destroy(struct constraint_expr *expr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139cfc0)
Location: security/selinux/ss/policydb.c:630
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff8139cfc0-ffffffff8139d00b: constraint_expr_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b38e3)
Location: security/selinux/ss/policydb.c:634
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff813b3840-ffffffff813b3885: constraint_expr_destroy.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813d9a33)
Location: security/selinux/ss/policydb.c:634
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff813d9990-ffffffff813d99d5: constraint_expr_destroy.part.5 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff8140a003)
Location: security/selinux/ss/policydb.c:634
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff81409f60-ffffffff81409fa5: constraint_expr_destroy.part.7 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff814262b3)
Location: security/selinux/ss/policydb.c:636
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff81426210-ffffffff81426255: constraint_expr_destroy.part.7 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81453eb6)
Location: security/selinux/ss/policydb.c:597
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff81453e10-ffffffff81453e5a: constraint_expr_destroy.part.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff8146dc56)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff8146dbb0-ffffffff8146dbfa: constraint_expr_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c2717)
Location: security/selinux/ss/policydb.c:205
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e0247)
Location: security/selinux/ss/policydb.c:205
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e6b27)
Location: security/selinux/ss/policydb.c:205
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815403b7)
Location: security/selinux/ss/policydb.c:205
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815d82b8)
Location: security/selinux/ss/policydb.c:201
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81686cd8)
Location: security/selinux/ss/policydb.c:201
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816bfc58)
Location: security/selinux/ss/policydb.c:201
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fc558)
Location: security/selinux/ss/policydb.c:201
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
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
In security/selinux/ss/policydb.c (ffff80001055cf58)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffff80001055cea0-ffff80001055cef4: constraint_expr_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (c07115d0)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
c0711520-c0711570: constraint_expr_destroy.part.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (c0000000006bc9f8)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
c0000000006bc8f0-c0000000006bc970: constraint_expr_destroy.part.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffe0003b4628)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffe0003b4572-ffffffe0003b45ca: constraint_expr_destroy.part.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81466236)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff81466190-ffffffff814661da: constraint_expr_destroy.part.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81456c66)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff81456bc0-ffffffff81456c0a: constraint_expr_destroy.part.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff814622d6)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff81462230-ffffffff8146227a: constraint_expr_destroy.part.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81479ad6)
Location: security/selinux/ss/policydb.c:206
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
Direct callers:
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
```
**Symbols:**

```
ffffffff81479a30-ffffffff81479a7a: constraint_expr_destroy.part.0 (STB_LOCAL)
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
</ul>
