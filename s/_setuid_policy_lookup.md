# Function: <code>_setuid_policy_lookup</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814991d8)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffffffff81499320-ffffffff81499366: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814b3108)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffffffff814b3240-ffffffff814b3286: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81512548)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:verify_ruleset
```
**Symbols:**

```
ffffffff815126e0-ffffffff81512726: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffff8000105aad0c)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffff8000105aaf00-ffff8000105aaf88: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c075a904)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
c075aad8-c075ab48: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c000000000728880)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
c000000000728b10-c000000000728b88: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffe0003f39ac)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffffffe0003f3b50-ffffffe0003f3bc2: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814ab6e8)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffffffff814ab820-ffffffff814ab866: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8149c108)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffffffff8149c240-ffffffff8149c286: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814a7788)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffffffff814a78c0-ffffffff814a7906: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum sid_policy_type _setuid_policy_lookup(struct setuid_ruleset *policy, kuid_t src, kuid_t dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814c0107)
Location: security/safesetid/lsm.c:30
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffffffff814c0250-ffffffff814c0296: _setuid_policy_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
