# Function: <code>verify_ruleset</code>

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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
int verify_ruleset(struct setuid_ruleset *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff815127e0-ffffffff81512842: verify_ruleset (STB_LOCAL)
ffffffff81512c06-ffffffff81512c79: verify_ruleset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int verify_ruleset(struct setid_ruleset *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:98
Inline: False
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
**Symbols:**

```
ffffffff8152fa10-ffffffff8152fa8e: verify_ruleset (STB_LOCAL)
ffffffff81bf18a9-ffffffff81bf1932: verify_ruleset.cold (STB_LOCAL)
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:98
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:98
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:98
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:98
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:98
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:98
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
In security/safesetid/securityfs.c (ffffffe0003f3ed0)
Location: security/safesetid/securityfs.c:84
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:84
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
<code>struct setuid_ruleset *pol</code> ➡️ <code>struct setid_ruleset *pol</code>
</li>
</ul>
</details>
</li>
</ul>
