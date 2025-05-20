# Function: <code>aa_pdb_free_kref</code>

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
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void aa_pdb_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81705f99)
Location: security/apparmor/policy.c:120
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
```
**Symbols:**

```
ffffffff81706070-ffffffff817060eb: aa_pdb_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void aa_pdb_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff817438a9)
Location: security/apparmor/policy.c:121
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
```
**Symbols:**

```
ffffffff81743980-ffffffff81743a03: aa_pdb_free_kref (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
