# Function: <code>_setid_policy_lookup</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setid_policy_lookup(struct setid_ruleset *policy, kid_t src, kid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8152f3e5)
Location: security/safesetid/lsm.c:32
Inline: True
Direct callers:
  - security/safesetid/lsm.c:id_permitted_for_cred
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:verify_ruleset
```
**Symbols:**

```
ffffffff8152f4b0-ffffffff8152f53d: _setid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setid_policy_lookup(struct setid_ruleset *policy, kid_t src, kid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81535675)
Location: security/safesetid/lsm.c:32
Inline: True
Direct callers:
  - security/safesetid/lsm.c:id_permitted_for_cred
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff81535740-ffffffff815357cf: _setid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setid_policy_lookup(struct setid_ruleset *policy, kid_t src, kid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81593c44)
Location: security/safesetid/lsm.c:32
Inline: True
Direct callers:
  - security/safesetid/lsm.c:id_permitted_for_cred
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff81593d20-ffffffff81593db7: _setid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setid_policy_lookup(struct setid_ruleset *policy, kid_t src, kid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81635ec0)
Location: security/safesetid/lsm.c:32
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_security_capable
  - security/safesetid/lsm.c:safesetid_security_capable
Direct callers:
  - security/safesetid/lsm.c:id_permitted_for_cred
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff81635cd0-ffffffff81635d92: _setid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setid_policy_lookup(struct setid_ruleset *policy, kid_t src, kid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff816eca76)
Location: security/safesetid/lsm.c:33
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_security_capable
  - security/safesetid/lsm.c:safesetid_security_capable
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff816ecc50-ffffffff816ecd12: _setid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setid_policy_lookup(struct setid_ruleset *policy, kid_t src, kid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81726ea6)
Location: security/safesetid/lsm.c:33
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_security_capable
  - security/safesetid/lsm.c:safesetid_security_capable
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff81727070-ffffffff81727132: _setid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setid_policy_lookup(struct setid_ruleset *policy, kid_t src, kid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff817680f6)
Location: security/safesetid/lsm.c:33
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_security_capable
  - security/safesetid/lsm.c:safesetid_security_capable
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff81768310-ffffffff817683d2: _setid_policy_lookup (STB_GLOBAL)
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
