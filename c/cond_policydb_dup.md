# Function: <code>cond_policydb_dup</code>

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
int cond_policydb_dup(struct policydb *new, struct policydb *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814ec3d0)
Location: security/selinux/ss/conditional.c:744
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff814ec3d0-ffffffff814ec4be: cond_policydb_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cond_policydb_dup(struct policydb *new, struct policydb *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814f2fa0)
Location: security/selinux/ss/conditional.c:744
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff814f2fa0-ffffffff814f3235: cond_policydb_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cond_policydb_dup(struct policydb *new, struct policydb *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8154d8e0)
Location: security/selinux/ss/conditional.c:747
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff8154d8e0-ffffffff8154db38: cond_policydb_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cond_policydb_dup(struct policydb *new, struct policydb *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff815e6980)
Location: security/selinux/ss/conditional.c:745
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff815e6980-ffffffff815e6bc8: cond_policydb_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cond_policydb_dup(struct policydb *new, struct policydb *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff81696010)
Location: security/selinux/ss/conditional.c:745
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff81696010-ffffffff81696258: cond_policydb_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cond_policydb_dup(struct policydb *new, struct policydb *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff816ce520)
Location: security/selinux/ss/conditional.c:745
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff816ce520-ffffffff816ce765: cond_policydb_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cond_policydb_dup(struct policydb *new, struct policydb *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8170ab40)
Location: security/selinux/ss/conditional.c:745
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff8170ab40-ffffffff8170ad85: cond_policydb_dup (STB_GLOBAL)
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
