# Function: <code>id_permitted_for_cred</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool id_permitted_for_cred(const struct cred *old, kid_t new_id, enum setid_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:156
Inline: False
```
**Symbols:**

```
ffffffff8152f540-ffffffff8152f5f4: id_permitted_for_cred (STB_LOCAL)
ffffffff81bf1865-ffffffff81bf18a9: id_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool id_permitted_for_cred(const struct cred *old, kid_t new_id, enum setid_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:153
Inline: False
```
**Symbols:**

```
ffffffff815357d0-ffffffff8153587a: id_permitted_for_cred (STB_LOCAL)
ffffffff81be3877-ffffffff81be38c0: id_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool id_permitted_for_cred(const struct cred *old, kid_t new_id, enum setid_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:153
Inline: False
```
**Symbols:**

```
ffffffff81593dc0-ffffffff81593e6a: id_permitted_for_cred (STB_LOCAL)
ffffffff81cd69ae-ffffffff81cd69f7: id_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool id_permitted_for_cred(const struct cred *old, kid_t new_id, enum setid_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:153
Inline: False
Direct callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
```
**Symbols:**

```
ffffffff81635da0-ffffffff81635e71: id_permitted_for_cred (STB_LOCAL)
ffffffff81e8990f-ffffffff81e89931: id_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool id_permitted_for_cred(const struct cred *old, kid_t new_id, enum setid_type new_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff816ecadc)
Location: security/safesetid/lsm.c:148
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
Direct callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
```
**Symbols:**

```
ffffffff816ecd30-ffffffff816ece25: id_permitted_for_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool id_permitted_for_cred(const struct cred *old, kid_t new_id, enum setid_type new_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81726f09)
Location: security/safesetid/lsm.c:148
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
Direct callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
```
**Symbols:**

```
ffffffff81727150-ffffffff81727241: id_permitted_for_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool id_permitted_for_cred(const struct cred *old, kid_t new_id, enum setid_type new_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81768172)
Location: security/safesetid/lsm.c:148
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
Direct callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
```
**Symbols:**

```
ffffffff817683f0-ffffffff817684e1: id_permitted_for_cred (STB_LOCAL)
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
