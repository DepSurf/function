# Function: <code>aa_audit_data_cmp</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int aa_audit_data_cmp(struct apparmor_audit_data *lhs, struct apparmor_audit_data *rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816c1990)
Location: security/apparmor/audit.c:305
Inline: True
Direct callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
```
**Symbols:**

```
ffffffff816c1990-ffffffff816c1a74: aa_audit_data_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int aa_audit_data_cmp(struct apparmor_audit_data *lhs, struct apparmor_audit_data *rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/audit.c (ffffffff816fa9cb)
Location: security/apparmor/audit.c:307
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
Direct callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
```
**Symbols:**

```
ffffffff816f9f60-ffffffff816fa055: aa_audit_data_cmp.part.0 (STB_LOCAL)
ffffffff816fa5b0-ffffffff816fa5e3: aa_audit_data_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int aa_audit_data_cmp(struct apparmor_audit_data *lhs, struct apparmor_audit_data *rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/audit.c (ffffffff817375db)
Location: security/apparmor/audit.c:316
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
Direct callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
```
**Symbols:**

```
ffffffff81736d00-ffffffff81736df5: aa_audit_data_cmp.part.0 (STB_LOCAL)
ffffffff817371c0-ffffffff817371f3: aa_audit_data_cmp (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
