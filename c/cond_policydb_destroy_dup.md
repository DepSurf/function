# Function: <code>cond_policydb_destroy_dup</code>

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
void cond_policydb_destroy_dup(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814ec320)
Location: security/selinux/ss/conditional.c:737
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff814ec320-ffffffff814ec3cb: cond_policydb_destroy_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cond_policydb_destroy_dup(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814f2ef0)
Location: security/selinux/ss/conditional.c:737
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff814f2ef0-ffffffff814f2f9b: cond_policydb_destroy_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cond_policydb_destroy_dup(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8154d9c0)
Location: security/selinux/ss/conditional.c:740
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff8154d880-ffffffff8154d8d8: cond_policydb_destroy_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cond_policydb_destroy_dup(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff815e6a61)
Location: security/selinux/ss/conditional.c:738
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff815e6920-ffffffff815e6980: cond_policydb_destroy_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cond_policydb_destroy_dup(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff816960f1)
Location: security/selinux/ss/conditional.c:738
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff81695fa0-ffffffff81696000: cond_policydb_destroy_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cond_policydb_destroy_dup(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff816ce601)
Location: security/selinux/ss/conditional.c:738
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff816ce4b0-ffffffff816ce510: cond_policydb_destroy_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cond_policydb_destroy_dup(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8170ac21)
Location: security/selinux/ss/conditional.c:738
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff8170aad0-ffffffff8170ab30: cond_policydb_destroy_dup (STB_GLOBAL)
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
