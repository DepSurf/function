# Function: <code>setuid_policy_lookup</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814991c0)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
ffffffff814991c0-ffffffff81499212: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814b30f0)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
ffffffff814b30f0-ffffffff814b313f: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8151253c)
Location: security/safesetid/lsm.c:50
Inline: True
Inline callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
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
<summary>In <code>arm64</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffff8000105aace0)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
ffff8000105aace0-ffff8000105aad60: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c075a8d8)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
c075a8d8-c075a95c: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c000000000728850)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
c000000000728850-c0000000007288d8: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffe0003f3984)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
ffffffe0003f3984-ffffffe0003f39e6: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814ab6d0)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
ffffffff814ab6d0-ffffffff814ab71f: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8149c0f0)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
ffffffff8149c0f0-ffffffff8149c13f: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814a7770)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
ffffffff814a7770-ffffffff814a77bf: setuid_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum sid_policy_type setuid_policy_lookup(kuid_t src, kuid_t dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814c00e0)
Location: security/safesetid/lsm.c:50
Inline: False
Direct callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
**Symbols:**

```
ffffffff814c00e0-ffffffff814c0149: setuid_policy_lookup (STB_LOCAL)
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
