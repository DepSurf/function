# Function: <code>compute_fperms</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_perms *compute_fperms(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff81632390)
Location: security/apparmor/policy_compat.c:149
Inline: False
Direct callers:
  - security/apparmor/policy_compat.c:aa_compat_map_file
```
**Symbols:**

```
ffffffff81632390-ffffffff816326fe: compute_fperms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_perms *compute_fperms(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff816e7160)
Location: security/apparmor/policy_compat.c:149
Inline: False
Direct callers:
  - security/apparmor/policy_compat.c:aa_compat_map_file
```
**Symbols:**

```
ffffffff816e7160-ffffffff816e74ce: compute_fperms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_perms *compute_fperms(struct aa_dfa *dfa, u32 *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff817208a0)
Location: security/apparmor/policy_compat.c:149
Inline: False
Direct callers:
  - security/apparmor/policy_compat.c:aa_compat_map_file
```
**Symbols:**

```
ffffffff817208a0-ffffffff81720c16: compute_fperms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_perms *compute_fperms(struct aa_dfa *dfa, u32 *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff8175f170)
Location: security/apparmor/policy_compat.c:152
Inline: False
Direct callers:
  - security/apparmor/policy_compat.c:aa_compat_map_file
```
**Symbols:**

```
ffffffff8175f170-ffffffff8175f4ab: compute_fperms (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
