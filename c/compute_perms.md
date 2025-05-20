# Function: <code>compute_perms</code>

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
struct aa_perms *compute_perms(struct aa_dfa *dfa, u32 version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff81632170)
Location: security/apparmor/policy_compat.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_compat.c:aa_compat_map_policy
```
**Symbols:**

```
ffffffff81632170-ffffffff81632389: compute_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_perms *compute_perms(struct aa_dfa *dfa, u32 version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff816e6f30)
Location: security/apparmor/policy_compat.c:242
Inline: False
Direct callers:
  - security/apparmor/policy_compat.c:aa_compat_map_policy
```
**Symbols:**

```
ffffffff816e6f30-ffffffff816e7149: compute_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_perms *compute_perms(struct aa_dfa *dfa, u32 version, u32 *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff81720670)
Location: security/apparmor/policy_compat.c:248
Inline: False
Direct callers:
  - security/apparmor/policy_compat.c:aa_compat_map_policy
```
**Symbols:**

```
ffffffff81720670-ffffffff8172088f: compute_perms (STB_LOCAL)
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
In security/apparmor/policy_compat.c (ffffffff8175f7ab)
Location: security/apparmor/policy_compat.c:253
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_policy
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
</ul>
