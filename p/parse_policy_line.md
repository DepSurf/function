# Function: <code>parse_policy_line</code>

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
In security/safesetid/securityfs.c (ffffffff814995bd)
Location: security/safesetid/securityfs.c:30
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
In security/safesetid/securityfs.c (ffffffff814b34dd)
Location: security/safesetid/securityfs.c:30
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_policy_line(struct file *file, char *buf, struct setuid_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81512850)
Location: security/safesetid/securityfs.c:30
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff81512850-ffffffff8151292c: parse_policy_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_policy_line(struct file *file, char *buf, struct setid_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8152f890)
Location: security/safesetid/securityfs.c:31
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff8152f890-ffffffff8152f9c4: parse_policy_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81535c2f)
Location: security/safesetid/securityfs.c:31
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8159422f)
Location: security/safesetid/securityfs.c:31
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8163628e)
Location: security/safesetid/securityfs.c:31
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff816ed28c)
Location: security/safesetid/securityfs.c:31
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff817276ac)
Location: security/safesetid/securityfs.c:31
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff817689a8)
Location: security/safesetid/securityfs.c:31
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
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
In security/safesetid/securityfs.c (ffff8000105ab1b8)
Location: security/safesetid/securityfs.c:30
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
In security/safesetid/securityfs.c (c075ad6c)
Location: security/safesetid/securityfs.c:30
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
In security/safesetid/securityfs.c (c000000000728ec8)
Location: security/safesetid/securityfs.c:30
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
In security/safesetid/securityfs.c (ffffffe0003f3dba)
Location: security/safesetid/securityfs.c:30
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
In security/safesetid/securityfs.c (ffffffff814ababd)
Location: security/safesetid/securityfs.c:30
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
In security/safesetid/securityfs.c (ffffffff8149c4dd)
Location: security/safesetid/securityfs.c:30
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
In security/safesetid/securityfs.c (ffffffff814a7b5d)
Location: security/safesetid/securityfs.c:30
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
In security/safesetid/securityfs.c (ffffffff814c04ed)
Location: security/safesetid/securityfs.c:30
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
<b>Param type changed. </b>
<code>struct setuid_rule *rule</code> ➡️ <code>struct setid_rule *rule</code>
</li>
</ul>
</details>
</li>
</ul>
