# Function: <code>aa_put_pdb</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81705d25)
Location: security/apparmor/include/policy.h:125
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170aa9d)
Location: security/apparmor/include/policy.h:125
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
```
```
In security/apparmor/lsm.c (ffffffff836f8bdf)
Location: security/apparmor/include/policy.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/notify.c (ffffffff81724f36)
Location: security/apparmor/include/policy.h:125
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff81743625)
Location: security/apparmor/include/policy.h:130
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff817494de)
Location: security/apparmor/include/policy.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_pdb
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/lsm.c (ffffffff8392c14e)
Location: security/apparmor/include/policy.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/lsm.c:aa_setup_dfa_engine
```
```
In security/apparmor/notify.c (ffffffff81766066)
Location: security/apparmor/include/policy.h:130
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
```
**Symbols:**

```
ffffffff81747100-ffffffff81747149: aa_put_pdb.part.0 (STB_LOCAL)
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
