# Function: <code>compute_fperms_allow</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff816324c8)
Location: security/apparmor/policy_compat.c:100
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
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
In security/apparmor/policy_compat.c (ffffffff816e7298)
Location: security/apparmor/policy_compat.c:100
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
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
In security/apparmor/policy_compat.c (ffffffff817209e1)
Location: security/apparmor/policy_compat.c:100
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void compute_fperms_allow(struct aa_perms *perms, struct aa_dfa *dfa, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff8175f0f0)
Location: security/apparmor/policy_compat.c:100
Inline: False
Direct callers:
  - security/apparmor/policy_compat.c:compute_fperms
  - security/apparmor/policy_compat.c:compute_fperms
```
**Symbols:**

```
ffffffff8175f0f0-ffffffff8175f157: compute_fperms_allow (STB_LOCAL)
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
</ul>
