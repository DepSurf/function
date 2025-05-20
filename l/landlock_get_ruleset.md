# Function: <code>landlock_get_ruleset</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff815372c5)
Location: security/landlock/ruleset.h:159
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/cred.c (ffffffff81538433)
Location: security/landlock/ruleset.h:159
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff81595a45)
Location: security/landlock/ruleset.h:159
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/cred.c (ffffffff81596c23)
Location: security/landlock/ruleset.h:159
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff81637d27)
Location: security/landlock/ruleset.h:174
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/cred.c (ffffffff81639043)
Location: security/landlock/ruleset.h:174
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff816ef127)
Location: security/landlock/ruleset.h:174
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/cred.c (ffffffff816f0593)
Location: security/landlock/ruleset.h:174
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff817295ca)
Location: security/landlock/ruleset.h:174
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/cred.c (ffffffff8172aa33)
Location: security/landlock/ruleset.h:174
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff8176ac1a)
Location: security/landlock/ruleset.h:253
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/cred.c (ffffffff8176c416)
Location: security/landlock/ruleset.h:253
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
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
