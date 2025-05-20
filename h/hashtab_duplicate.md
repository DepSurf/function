# Function: <code>hashtab_duplicate</code>

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
int hashtab_duplicate(struct hashtab *new, struct hashtab *orig, int (*copy)(struct hashtab_node *, struct hashtab_node *, void *), int (*destroy)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814dd200)
Location: security/selinux/ss/hashtab.c:125
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff814dd200-ffffffff814dd3a8: hashtab_duplicate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hashtab_duplicate(struct hashtab *new, struct hashtab *orig, int (*copy)(struct hashtab_node *, struct hashtab_node *, void *), int (*destroy)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814e3b70)
Location: security/selinux/ss/hashtab.c:125
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff814e3b70-ffffffff814e3d18: hashtab_duplicate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hashtab_duplicate(struct hashtab *new, struct hashtab *orig, int (*copy)(struct hashtab_node *, struct hashtab_node *, void *), int (*destroy)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8153cf90)
Location: security/selinux/ss/hashtab.c:132
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff8153cf90-ffffffff8153d138: hashtab_duplicate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hashtab_duplicate(struct hashtab *new, struct hashtab *orig, int (*copy)(struct hashtab_node *, struct hashtab_node *, void *), int (*destroy)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff815d49f0)
Location: security/selinux/ss/hashtab.c:133
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff815d49f0-ffffffff815d4baf: hashtab_duplicate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hashtab_duplicate(struct hashtab *new, struct hashtab *orig, int (*copy)(struct hashtab_node *, struct hashtab_node *, void *), int (*destroy)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81682b60)
Location: security/selinux/ss/hashtab.c:133
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff81682b60-ffffffff81682d1f: hashtab_duplicate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hashtab_duplicate(struct hashtab *new, struct hashtab *orig, int (*copy)(struct hashtab_node *, struct hashtab_node *, void *), int (*destroy)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff816bace0)
Location: security/selinux/ss/hashtab.c:133
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff816bace0-ffffffff816bae9f: hashtab_duplicate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hashtab_duplicate(struct hashtab *new, struct hashtab *orig, int (*copy)(struct hashtab_node *, struct hashtab_node *, void *), int (*destroy)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff816f76d0)
Location: security/selinux/ss/hashtab.c:139
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff816f76d0-ffffffff816f7895: hashtab_duplicate (STB_GLOBAL)
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
