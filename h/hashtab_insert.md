# Function: <code>hashtab_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8134e3f0)
Location: security/selinux/ss/hashtab.c:39
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff8134e3f0-ffffffff8134e54a: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813843f0)
Location: security/selinux/ss/hashtab.c:39
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff813843f0-ffffffff8138453f: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8139ae80)
Location: security/selinux/ss/hashtab.c:39
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff8139ae80-ffffffff8139afcf: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813b1580)
Location: security/selinux/ss/hashtab.c:39
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff813b1580-ffffffff813b16d4: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813d7670)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff813d7670-ffffffff813d77c0: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81407ce0)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81407ce0-ffffffff81407e30: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81423830)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81423830-ffffffff8142398d: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81451390)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81451390-ffffffff814514ed: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8146b170)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff8146b170-ffffffff8146b2cd: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814bf6e0)
Location: security/selinux/ss/hashtab.c:49
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff814bf6e0-ffffffff814bf83b: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum, struct hashtab_key_params key_params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814dd447)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/policydb.c (ffffffff814e245f)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814dfdd0-ffffffff814dfead: hashtab_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum, struct hashtab_key_params key_params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814e3db7)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/policydb.c (ffffffff814e8654)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814e6650-ffffffff814e672d: hashtab_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum, struct hashtab_key_params key_params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff8153d1d7)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/policydb.c (ffffffff81541f94)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8153fee0-ffffffff8153ffbd: hashtab_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum, struct hashtab_key_params key_params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff815d4c68)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/policydb.c (ffffffff815d9d74)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff815d7ef0-ffffffff815d7fed: hashtab_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum, struct hashtab_key_params key_params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81682e18)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/policydb.c (ffffffff81688849)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816865f0-ffffffff816866ed: hashtab_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum, struct hashtab_key_params key_params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff816baf98)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/policydb.c (ffffffff816c1fac)
Location: security/selinux/ss/hashtab.h:61
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816be960-ffffffff816bea5f: hashtab_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum, struct hashtab_key_params key_params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff816f7998)
Location: security/selinux/ss/hashtab.h:62
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/policydb.c (ffffffff816fea6f)
Location: security/selinux/ss/hashtab.h:62
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816fb180-ffffffff816fb27f: hashtab_insert (STB_LOCAL)
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
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffff800010559ed0)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffff800010559ed0-ffff80001055a024: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (c070e770)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
c070e770-c070e8d8: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (c0000000006b8290)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
c0000000006b8290-c0000000006b848c: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffe0003b0ff8)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffe0003b0ff8-ffffffe0003b1126: hashtab_insert (STB_GLOBAL)
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
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81463750)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81463750-ffffffff814638ad: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81454180)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81454180-ffffffff814542dd: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8145f7f0)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff8145f7f0-ffffffff8145f94d: hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab *h, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81477000)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81477000-ffffffff81477151: hashtab_insert (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hashtab_key_params key_params</code>
</li>
</ul>
</details>
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
