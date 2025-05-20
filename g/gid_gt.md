# Function: <code>gid_gt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (0)
Location: include/linux/uidgid.h:75
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/uidgid.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (0)
Location: include/linux/uidgid.h:75
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8112d5bb)
Location: include/linux/uidgid.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (0)
Location: include/linux/uidgid.h:75
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811372eb)
Location: include/linux/uidgid.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810aa619)
Location: include/linux/uidgid.h:75
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff8113884b)
Location: include/linux/uidgid.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b12d9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff81145549)
Location: include/linux/uidgid.h:76
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b80d9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff81153ee9)
Location: include/linux/uidgid.h:76
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810c11b9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff81160ca1)
Location: include/linux/uidgid.h:76
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810c72a9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff8116d339)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810d0379)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff811791d9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810da62d)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff8118c219)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810d5d8f)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff81189439)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810d7a4f)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff8118a2a6)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810eb2ff)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff811b2d66)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool gid_gt(kgid_t left, kgid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff81106211)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff811e5184)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
```
In security/integrity/ima/ima_policy.c (ffffffff81641ee0)
Location: include/linux/uidgid.h:76
Inline: False
```
**Symbols:**

```
ffffffff81641ee0-ffffffff81641eee: gid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool gid_gt(kgid_t left, kgid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff8112be51)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff8122b1d4)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
```
In security/integrity/ima/ima_policy.c (ffffffff816f9fa0)
Location: include/linux/uidgid.h:76
Inline: False
```
**Symbols:**

```
ffffffff816f9fa0-ffffffff816f9fae: gid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool gid_gt(kgid_t left, kgid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff81138cb1)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff812417b7)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
```
In security/integrity/ima/ima_policy.c (ffffffff817340d0)
Location: include/linux/uidgid.h:76
Inline: False
```
**Symbols:**

```
ffffffff817340d0-ffffffff817340de: gid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool gid_gt(kgid_t left, kgid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:68
Inline: True
```
```
In kernel/groups.c (ffffffff811439f1)
Location: include/linux/uidgid.h:68
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff8125b5e7)
Location: include/linux/uidgid.h:68
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
```
In security/integrity/ima/ima_policy.c (ffffffff81774bc0)
Location: include/linux/uidgid.h:68
Inline: False
```
**Symbols:**

```
ffffffff81774bc0-ffffffff81774bce: gid_gt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffff800010130a04)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffff8000101ee474)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (c0380264)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (c042e4e8)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (c00000000017a100)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (c000000000261090)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffe0000e3dbc)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffe000162614)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810ca6f9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff811717f9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810b8f09)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff81164999)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810c9c29)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff8116f5c9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:76
Inline: True
```
```
In kernel/groups.c (ffffffff810d2179)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/groups.c:gid_cmp
```
```
In kernel/auditfilter.c (ffffffff8117cdb9)
Location: include/linux/uidgid.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_gid_comparator
```
</details>
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
