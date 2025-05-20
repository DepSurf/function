# Function: <code>avtab_search_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8134f650)
Location: security/selinux/ss/avtab.c:219
Inline: False
Direct callers:
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/conditional.c:cond_insertf
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_compute_av
```
**Symbols:**

```
ffffffff8134f650-ffffffff8134f747: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81385690)
Location: security/selinux/ss/avtab.c:219
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81385690-ffffffff81385790: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8139c120)
Location: security/selinux/ss/avtab.c:219
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff8139c120-ffffffff8139c220: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff813b28f0)
Location: security/selinux/ss/avtab.c:219
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff813b28f0-ffffffff813b29f0: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff813d8a30)
Location: security/selinux/ss/avtab.c:219
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff813d8a30-ffffffff813d8b30: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81409050)
Location: security/selinux/ss/avtab.c:219
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81409050-ffffffff81409150: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81425310)
Location: security/selinux/ss/avtab.c:219
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81425310-ffffffff81425410: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81452de0)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81452de0-ffffffff81452ec7: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8146cb80)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff8146cb80-ffffffff8146cc67: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff814c1340)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff814c1340-ffffffff814c1435: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff814dedf0)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_dup_av_list
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff814dedf0-ffffffff814deee5: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff814e57f0)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff814e57f0-ffffffff814e58f2: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, const struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8153eee0)
Location: security/selinux/ss/avtab.c:218
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff8153eee0-ffffffff8153efe2: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, const struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff815d6b50)
Location: security/selinux/ss/avtab.c:218
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff815d6b50-ffffffff815d6c8b: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, const struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81684fb0)
Location: security/selinux/ss/avtab.c:218
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81684fb0-ffffffff816850eb: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, const struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816bd330)
Location: security/selinux/ss/avtab.c:218
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff816bd330-ffffffff816bd46d: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, const struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816f9ca0)
Location: security/selinux/ss/avtab.c:180
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
  - security/selinux/ss/conditional.c:cond_insertf
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff816f9ca0-ffffffff816f9dd6: avtab_search_node (STB_GLOBAL)
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
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffff80001055bba0)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffff80001055bba0-ffff80001055bce0: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (c0710300)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
c0710300-c0710434: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (c0000000006baff0)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
c0000000006baff0-c0000000006bb154: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffe0003b28e8)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffe0003b28e8-ffffffe0003b2a3e: avtab_search_node (STB_GLOBAL)
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
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81465160)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81465160-ffffffff81465247: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81455b90)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81455b90-ffffffff81455c77: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81461200)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81461200-ffffffff814612e7: avtab_search_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct avtab_node *avtab_search_node(struct avtab *h, struct avtab_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81478a00)
Location: security/selinux/ss/avtab.c:217
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/conditional.c:cond_compute_av
  - security/selinux/ss/conditional.c:cond_compute_xperms
  - security/selinux/ss/conditional.c:cond_insertf
```
**Symbols:**

```
ffffffff81478a00-ffffffff81478ae7: avtab_search_node (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct avtab_key *key</code> ➡️ <code>const struct avtab_key *key</code>
</li>
</ul>
</details>
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
