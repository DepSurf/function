# Function: <code>free_ruleset</code>

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
void free_ruleset(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff815379d0)
Location: security/landlock/ruleset.c:356
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset_work
```
**Symbols:**

```
ffffffff815379d0-ffffffff81537aa7: free_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_ruleset(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff815961d0)
Location: security/landlock/ruleset.c:356
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset_work
```
**Symbols:**

```
ffffffff815961d0-ffffffff815962a7: free_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_ruleset(struct aa_ruleset *rules);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8161a552)
Location: security/apparmor/policy.c:207
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/landlock/ruleset.c (ffffffff81638570)
Location: security/landlock/ruleset.c:359
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset_work
```
**Symbols:**

```
ffffffff81638570-ffffffff81638639: free_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_ruleset(struct aa_ruleset *rules);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff816ccfbc)
Location: security/apparmor/policy.c:209
Inline: True
```
```
In security/landlock/ruleset.c (ffffffff816ef9f0)
Location: security/landlock/ruleset.c:359
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset_work
```
**Symbols:**

```
ffffffff816ef9f0-ffffffff816efab9: free_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_ruleset(struct aa_ruleset *rules);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81705d86)
Location: security/apparmor/policy.c:246
Inline: True
```
```
In security/landlock/ruleset.c (ffffffff81729ea0)
Location: security/landlock/ruleset.c:359
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset_work
```
**Symbols:**

```
ffffffff81729ea0-ffffffff81729f69: free_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_ruleset(struct aa_ruleset *rules);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81743686)
Location: security/apparmor/policy.c:247
Inline: True
```
```
In security/landlock/ruleset.c (ffffffff8176b270)
Location: security/landlock/ruleset.c:486
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset_work
```
**Symbols:**

```
ffffffff8176b270-ffffffff8176b36b: free_ruleset (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_ruleset *rules</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct landlock_ruleset * ruleset</code>
</li>
</ul>
</details>
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
