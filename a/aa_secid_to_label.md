# Function: <code>aa_secid_to_label</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81444535)
Location: security/apparmor/secid.c:65
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
```
**Symbols:**

```
ffffffff81444510-ffffffff81444529: aa_secid_to_label (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81505b75)
Location: security/apparmor/secid.c:61
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
```
**Symbols:**

```
ffffffff81505b50-ffffffff81505b69: aa_secid_to_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81522cb5)
Location: security/apparmor/secid.c:61
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
```
**Symbols:**

```
ffffffff81522c80-ffffffff81522caa: aa_secid_to_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81528ea5)
Location: security/apparmor/secid.c:61
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
```
**Symbols:**

```
ffffffff81528e70-ffffffff81528e9a: aa_secid_to_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81587245)
Location: security/apparmor/secid.c:61
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
```
**Symbols:**

```
ffffffff81587210-ffffffff8158723a: aa_secid_to_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff816276c5)
Location: security/apparmor/secid.c:60
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
```
**Symbols:**

```
ffffffff81627690-ffffffff816276b1: aa_secid_to_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff816db6f5)
Location: security/apparmor/secid.c:60
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
```
**Symbols:**

```
ffffffff816db6b0-ffffffff816db6d1: aa_secid_to_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81714dc5)
Location: security/apparmor/secid.c:59
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
```
**Symbols:**

```
ffffffff81714d80-ffffffff81714da1: aa_secid_to_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_secid_to_label(u32 secid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff817537d5)
Location: security/apparmor/secid.c:59
Inline: True
Inline callers:
  - security/apparmor/secid.c:apparmor_secid_to_secctx
```
**Symbols:**

```
ffffffff81753790-ffffffff817537b1: aa_secid_to_label (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
