# Function: <code>landlock_put_ruleset</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void landlock_put_ruleset(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81538308)
Location: security/landlock/ruleset.c:368
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:fop_ruleset_release
```
**Symbols:**

```
ffffffff81538150-ffffffff815381a2: landlock_put_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void landlock_put_ruleset(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81596a83)
Location: security/landlock/ruleset.c:368
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:fop_ruleset_release
```
**Symbols:**

```
ffffffff81596810-ffffffff81596862: landlock_put_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void landlock_put_ruleset(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81638ef2)
Location: security/landlock/ruleset.c:370
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:fop_ruleset_release
```
**Symbols:**

```
ffffffff81638ce0-ffffffff81638d42: landlock_put_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void landlock_put_ruleset(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff816f0412)
Location: security/landlock/ruleset.c:370
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:fop_ruleset_release
```
**Symbols:**

```
ffffffff816f01e0-ffffffff816f0242: landlock_put_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void landlock_put_ruleset(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8172a7ad)
Location: security/landlock/ruleset.c:370
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:fop_ruleset_release
```
**Symbols:**

```
ffffffff8172a580-ffffffff8172a5e2: landlock_put_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void landlock_put_ruleset(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8176be55)
Location: security/landlock/ruleset.c:505
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/syscalls.c:__do_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:fop_ruleset_release
```
**Symbols:**

```
ffffffff8176bc30-ffffffff8176bc92: landlock_put_ruleset (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
