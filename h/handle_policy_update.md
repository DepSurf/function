# Function: <code>handle_policy_update</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814994e5)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814b3405)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t handle_policy_update(struct file *file, const char *ubuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:110
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
**Symbols:**

```
ffffffff81512930-ffffffff81512b2e: handle_policy_update (STB_LOCAL)
ffffffff81512c79-ffffffff81512c91: handle_policy_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t handle_policy_update(struct file *file, const char *ubuf, size_t len, enum setid_type policy_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:139
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
```
**Symbols:**

```
ffffffff8152fa90-ffffffff8152fcb5: handle_policy_update (STB_LOCAL)
ffffffff81bf1932-ffffffff81bf1951: handle_policy_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t handle_policy_update(struct file *file, const char *ubuf, size_t len, enum setid_type policy_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:139
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
```
**Symbols:**

```
ffffffff81535b20-ffffffff81535ebb: handle_policy_update (STB_LOCAL)
ffffffff81be38c0-ffffffff81be396e: handle_policy_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t handle_policy_update(struct file *file, const char *ubuf, size_t len, enum setid_type policy_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:139
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
```
**Symbols:**

```
ffffffff81594120-ffffffff815944d4: handle_policy_update (STB_LOCAL)
ffffffff81cd69f7-ffffffff81cd6aa5: handle_policy_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t handle_policy_update(struct file *file, const char *ubuf, size_t len, enum setid_type policy_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:139
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
```
**Symbols:**

```
ffffffff81636170-ffffffff81636564: handle_policy_update (STB_LOCAL)
ffffffff81e89931-ffffffff81e899e1: handle_policy_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t handle_policy_update(struct file *file, const char *ubuf, size_t len, enum setid_type policy_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff816ed170)
Location: security/safesetid/securityfs.c:139
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
```
**Symbols:**

```
ffffffff816ed170-ffffffff816ed601: handle_policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t handle_policy_update(struct file *file, const char *ubuf, size_t len, enum setid_type policy_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81727590)
Location: security/safesetid/securityfs.c:139
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
```
**Symbols:**

```
ffffffff81727590-ffffffff81727a15: handle_policy_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t handle_policy_update(struct file *file, const char *ubuf, size_t len, enum setid_type policy_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81768830)
Location: security/safesetid/securityfs.c:139
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
```
**Symbols:**

```
ffffffff81768830-ffffffff81768d4e: handle_policy_update (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffff8000105ab110)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (c075ac9c)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (c000000000728dc0)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffe0003f3d04)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814ab9e5)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8149c405)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814a7a85)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814c0415)
Location: security/safesetid/securityfs.c:110
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum setid_type policy_type</code>
</li>
</ul>
</details>
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
