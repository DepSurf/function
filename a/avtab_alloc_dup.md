# Function: <code>avtab_alloc_dup</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int avtab_alloc_dup(struct avtab *new, const struct avtab *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff814e5aa0)
Location: security/selinux/ss/avtab.c:350
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff814e5aa0-ffffffff814e5b03: avtab_alloc_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int avtab_alloc_dup(struct avtab *new, const struct avtab *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8153f1a0)
Location: security/selinux/ss/avtab.c:352
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff8153f1a0-ffffffff8153f203: avtab_alloc_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int avtab_alloc_dup(struct avtab *new, const struct avtab *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff815d6e50)
Location: security/selinux/ss/avtab.c:352
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff815d6e50-ffffffff815d6ea9: avtab_alloc_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int avtab_alloc_dup(struct avtab *new, const struct avtab *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81685300)
Location: security/selinux/ss/avtab.c:352
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff81685300-ffffffff81685359: avtab_alloc_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int avtab_alloc_dup(struct avtab *new, const struct avtab *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816bd660)
Location: security/selinux/ss/avtab.c:352
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff816bd660-ffffffff816bd6bc: avtab_alloc_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int avtab_alloc_dup(struct avtab *new, const struct avtab *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816f9ff0)
Location: security/selinux/ss/avtab.c:290
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff816f9ff0-ffffffff816fa04c: avtab_alloc_dup (STB_GLOBAL)
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
