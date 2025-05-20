# Function: <code>sidtab_entry_to_string</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sidtab_entry_to_string(struct policydb *p, struct sidtab *sidtab, struct sidtab_entry *entry, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814c7e00)
Location: security/selinux/ss/services.c:1265
Inline: True
Direct callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validtrans_handle_fail
  - security/selinux/ss/services.c:security_validtrans_handle_fail
  - security/selinux/ss/services.c:security_validtrans_handle_fail
```
**Symbols:**

```
ffffffff814c7e00-ffffffff814c7e8c: sidtab_entry_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sidtab_entry_to_string(struct policydb *p, struct sidtab *sidtab, struct sidtab_entry *entry, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e5c20)
Location: security/selinux/ss/services.c:1278
Inline: True
Direct callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validtrans_handle_fail
  - security/selinux/ss/services.c:security_validtrans_handle_fail
  - security/selinux/ss/services.c:security_validtrans_handle_fail
```
**Symbols:**

```
ffffffff814e5c20-ffffffff814e5cac: sidtab_entry_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sidtab_entry_to_string(struct policydb *p, struct sidtab *sidtab, struct sidtab_entry *entry, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ec4f0)
Location: security/selinux/ss/services.c:1280
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff814ec4f0-ffffffff814ec57c: sidtab_entry_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sidtab_entry_to_string(struct policydb *p, struct sidtab *sidtab, struct sidtab_entry *entry, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81546140)
Location: security/selinux/ss/services.c:1282
Inline: True
Direct callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff81546140-ffffffff815461cc: sidtab_entry_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sidtab_entry_to_string(struct policydb *p, struct sidtab *sidtab, struct sidtab_entry *entry, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815dea70)
Location: security/selinux/ss/services.c:1280
Inline: True
Direct callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff815dea70-ffffffff815deb1b: sidtab_entry_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sidtab_entry_to_string(struct policydb *p, struct sidtab *sidtab, struct sidtab_entry *entry, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8168d7b0)
Location: security/selinux/ss/services.c:1274
Inline: True
Direct callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff8168d7b0-ffffffff8168d85b: sidtab_entry_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sidtab_entry_to_string(struct policydb *p, struct sidtab *sidtab, struct sidtab_entry *entry, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c5a80)
Location: security/selinux/ss/services.c:1263
Inline: True
Direct callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff816c5a80-ffffffff816c5b2b: sidtab_entry_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sidtab_entry_to_string(struct policydb *p, struct sidtab *sidtab, struct sidtab_entry *entry, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff817026d0)
Location: security/selinux/ss/services.c:1263
Inline: True
Direct callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff817026d0-ffffffff8170277b: sidtab_entry_to_string (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
