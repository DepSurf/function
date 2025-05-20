# Function: <code>symtab_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int symtab_insert(struct symtab *s, char *name, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814dd430)
Location: security/selinux/ss/symtab.c:46
Inline: False
Direct callers:
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
ffffffff814dd430-ffffffff814dd4f5: symtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int symtab_insert(struct symtab *s, char *name, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814e3da0)
Location: security/selinux/ss/symtab.c:46
Inline: False
Direct callers:
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
ffffffff814e3da0-ffffffff814e3e65: symtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int symtab_insert(struct symtab *s, char *name, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff8153d1c0)
Location: security/selinux/ss/symtab.c:46
Inline: False
Direct callers:
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
ffffffff8153d1c0-ffffffff8153d285: symtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int symtab_insert(struct symtab *s, char *name, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff815d4c50)
Location: security/selinux/ss/symtab.c:46
Inline: False
Direct callers:
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
ffffffff815d4c50-ffffffff815d4d31: symtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int symtab_insert(struct symtab *s, char *name, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81682e00)
Location: security/selinux/ss/symtab.c:46
Inline: False
Direct callers:
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
ffffffff81682e00-ffffffff81682ee1: symtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int symtab_insert(struct symtab *s, char *name, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff816baf80)
Location: security/selinux/ss/symtab.c:46
Inline: False
Direct callers:
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
ffffffff816baf80-ffffffff816bb061: symtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int symtab_insert(struct symtab *s, char *name, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff816f7980)
Location: security/selinux/ss/symtab.c:46
Inline: False
Direct callers:
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
ffffffff816f7980-ffffffff816f7a61: symtab_insert (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
