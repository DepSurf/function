# Function: <code>landlock_find_rule</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct landlock_rule *landlock_find_rule(const const struct landlock_ruleset * ruleset, const const struct landlock_object * object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff815383a0)
Location: security/landlock/ruleset.c:452
Inline: False
```
**Symbols:**

```
ffffffff815383a0-ffffffff815383d5: landlock_find_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct landlock_rule *landlock_find_rule(const const struct landlock_ruleset * ruleset, const const struct landlock_object * object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81596b90)
Location: security/landlock/ruleset.c:452
Inline: False
```
**Symbols:**

```
ffffffff81596b90-ffffffff81596bc5: landlock_find_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct landlock_rule *landlock_find_rule(const const struct landlock_ruleset * ruleset, const const struct landlock_object * object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81638f90)
Location: security/landlock/ruleset.c:455
Inline: False
Direct callers:
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
```
**Symbols:**

```
ffffffff81638f90-ffffffff81638fd9: landlock_find_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct landlock_rule *landlock_find_rule(const const struct landlock_ruleset * ruleset, const const struct landlock_object * object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff816f04c0)
Location: security/landlock/ruleset.c:455
Inline: False
Direct callers:
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
```
**Symbols:**

```
ffffffff816f04c0-ffffffff816f0509: landlock_find_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct landlock_rule *landlock_find_rule(const const struct landlock_ruleset * ruleset, const const struct landlock_object * object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8172a960)
Location: security/landlock/ruleset.c:455
Inline: False
Direct callers:
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
```
**Symbols:**

```
ffffffff8172a960-ffffffff8172a9a9: landlock_find_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct landlock_rule *landlock_find_rule(const const struct landlock_ruleset * ruleset, const struct landlock_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8176bfd0)
Location: security/landlock/ruleset.c:590
Inline: False
Direct callers:
  - security/landlock/fs.c:find_rule
  - security/landlock/net.c:current_check_access_socket
```
**Symbols:**

```
ffffffff8176bfd0-ffffffff8176c03b: landlock_find_rule (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct landlock_id id</code>
</li>
<li>
<b>Param removed. </b>
<code>const const struct landlock_object * object</code>
</li>
</ul>
</details>
</li>
</ul>
