# Function: <code>aa_compat_map_xmatch</code>

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
int aa_compat_map_xmatch(struct aa_policydb *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff81632700)
Location: security/apparmor/policy_compat.c:287
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81632700-ffffffff816327d6: aa_compat_map_xmatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_compat_map_xmatch(struct aa_policydb *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff816e74e0)
Location: security/apparmor/policy_compat.c:287
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff816e74e0-ffffffff816e75b6: aa_compat_map_xmatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_compat_map_xmatch(struct aa_policydb *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff81720c30)
Location: security/apparmor/policy_compat.c:295
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81720c30-ffffffff81720d2e: aa_compat_map_xmatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_compat_map_xmatch(struct aa_policydb *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_compat.c (ffffffff8175f660)
Location: security/apparmor/policy_compat.c:300
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff8175f660-ffffffff8175f75d: aa_compat_map_xmatch (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
