# Function: <code>aa_lookup_fperms</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct aa_perms *aa_lookup_fperms(struct aa_policydb *file_rules, unsigned int state, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81628168)
Location: security/apparmor/file.c:190
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_str_perms
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
```
**Symbols:**

```
ffffffff816280b0-ffffffff81628135: aa_lookup_fperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct aa_perms *aa_lookup_fperms(struct aa_policydb *file_rules, unsigned int state, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff816dc878)
Location: security/apparmor/file.c:313
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_str_perms
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
```
**Symbols:**

```
ffffffff816dc7b0-ffffffff816dc835: aa_lookup_fperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct aa_perms *aa_lookup_fperms(struct aa_policydb *file_rules, unsigned int state, struct path_cond *cond);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81715e8a)
Location: security/apparmor/file.c:333
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_str_perms
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
```
**Symbols:**

```
ffffffff81715dc0-ffffffff81715e46: aa_lookup_fperms (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
