# Function: <code>landlock_create_ruleset</code>

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
struct landlock_ruleset *landlock_create_ruleset(const u32 fs_access_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81538060)
Location: security/landlock/ruleset.c:47
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff81538060-ffffffff815380f4: landlock_create_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct landlock_ruleset *landlock_create_ruleset(const u32 fs_access_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81596720)
Location: security/landlock/ruleset.c:47
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff81596720-ffffffff815967b4: landlock_create_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct landlock_ruleset *landlock_create_ruleset(const access_mask_t fs_access_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81638bd0)
Location: security/landlock/ruleset.c:49
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff81638bd0-ffffffff81638c73: landlock_create_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct landlock_ruleset *landlock_create_ruleset(const access_mask_t fs_access_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff816f00b0)
Location: security/landlock/ruleset.c:49
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff816f00b0-ffffffff816f0153: landlock_create_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct landlock_ruleset *landlock_create_ruleset(const access_mask_t fs_access_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8172a450)
Location: security/landlock/ruleset.c:49
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff8172a450-ffffffff8172a4f3: landlock_create_ruleset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct landlock_ruleset *landlock_create_ruleset(const access_mask_t fs_access_mask, const access_mask_t net_access_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8176bab0)
Location: security/landlock/ruleset.c:54
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__do_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff8176bab0-ffffffff8176bba6: landlock_create_ruleset (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>const u32 fs_access_mask</code> ➡️ <code>const access_mask_t fs_access_mask</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const access_mask_t net_access_mask</code>
</li>
</ul>
</details>
</li>
</ul>
