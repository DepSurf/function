# Function: <code>aa_dup_audit_data</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_audit_node *aa_dup_audit_data(struct apparmor_audit_data *orig, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816c1ad0)
Location: security/apparmor/audit.c:366
Inline: False
```
**Symbols:**

```
ffffffff816c1ad0-ffffffff816c1d02: aa_dup_audit_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_audit_node *aa_dup_audit_data(struct apparmor_audit_data *orig, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816fa640)
Location: security/apparmor/audit.c:379
Inline: False
Direct callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
```
**Symbols:**

```
ffffffff816fa640-ffffffff816fa888: aa_dup_audit_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_audit_node *aa_dup_audit_data(struct apparmor_audit_data *orig, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81737250)
Location: security/apparmor/audit.c:388
Inline: False
Direct callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
```
**Symbols:**

```
ffffffff81737250-ffffffff8173749a: aa_dup_audit_data (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
