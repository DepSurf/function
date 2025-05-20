# Function: <code>AUDIT_MODE</code>

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
In security/apparmor/audit.c (ffffffff81376c3f)
Location: security/apparmor/include/policy.h:275
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff81376eb5)
Location: security/apparmor/include/policy.h:275
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff81378935)
Location: security/apparmor/include/policy.h:275
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81387c5f)
Location: security/apparmor/include/policy.h:275
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8138e5e1)
Location: security/apparmor/include/policy.h:275
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_mount
  - security/apparmor/mount.c:audit_mount
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
In security/apparmor/audit.c (ffffffff813af6ff)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff813afaea)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff813b1685)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff813c272f)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff813c9571)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_mount
  - security/apparmor/mount.c:audit_mount
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
In security/apparmor/audit.c (ffffffff813c687f)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff813c6c6a)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff813c8845)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff813d9bcf)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff813e0be1)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_mount
  - security/apparmor/mount.c:audit_mount
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
In security/apparmor/audit.c (ffffffff813dc70c)
Location: security/apparmor/include/policy.h:296
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff813dc92d)
Location: security/apparmor/include/policy.h:296
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff813ddff5)
Location: security/apparmor/include/policy.h:296
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff813eada8)
Location: security/apparmor/include/policy.h:296
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff813eff21)
Location: security/apparmor/include/policy.h:296
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
In security/apparmor/audit.c (ffffffff8140317c)
Location: security/apparmor/include/policy.h:296
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff81403392)
Location: security/apparmor/include/policy.h:296
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff81404995)
Location: security/apparmor/include/policy.h:296
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff814126e8)
Location: security/apparmor/include/policy.h:296
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff81417e61)
Location: security/apparmor/include/policy.h:296
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
In security/apparmor/audit.c (ffffffff8143412c)
Location: security/apparmor/include/policy.h:304
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff81434514)
Location: security/apparmor/include/policy.h:304
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff81435a45)
Location: security/apparmor/include/policy.h:304
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81444a90)
Location: security/apparmor/include/policy.h:304
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8144a2fb)
Location: security/apparmor/include/policy.h:304
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
In security/apparmor/audit.c (ffffffff81450e2c)
Location: security/apparmor/include/policy.h:304
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff81451068)
Location: security/apparmor/include/policy.h:304
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff81452665)
Location: security/apparmor/include/policy.h:304
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81461970)
Location: security/apparmor/include/policy.h:304
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8146726b)
Location: security/apparmor/include/policy.h:304
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
In security/apparmor/audit.c (ffffffff8147e8ef)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff8147eb25)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff81480025)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff8148ec34)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff814942fd)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (ffffffff814985ef)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff81498825)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff81499d25)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff814a8af4)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff814ae22d)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (ffffffff814f080c)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff814f0b09)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/lib.c (ffffffff814f2485)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff815060e4)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8150d18d)
Location: security/apparmor/include/policy.h:302
Inline: True
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
In security/apparmor/audit.c (ffffffff8150da9c)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff8150dd89)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/lib.c (ffffffff8150f685)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81523214)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff81529ffd)
Location: security/apparmor/include/policy.h:302
Inline: True
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
In security/apparmor/audit.c (ffffffff815144ae)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff8151479d)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/lib.c (ffffffff81516065)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81529404)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff815303ed)
Location: security/apparmor/include/policy.h:302
Inline: True
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
In security/apparmor/audit.c (ffffffff8157236e)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff8157266f)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/lib.c (ffffffff81574065)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff815877a4)
Location: security/apparmor/include/policy.h:302
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8158e80d)
Location: security/apparmor/include/policy.h:302
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8160f2e1)
Location: security/apparmor/include/policy.h:369
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff8160f647)
Location: security/apparmor/include/policy.h:369
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/lib.c (ffffffff81611a65)
Location: security/apparmor/include/policy.h:369
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81627ed2)
Location: security/apparmor/include/policy.h:369
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8162f8e6)
Location: security/apparmor/include/policy.h:369
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816c166f)
Location: security/apparmor/include/policy.h:375
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff816c2044)
Location: security/apparmor/include/policy.h:375
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/lib.c (ffffffff816c4765)
Location: security/apparmor/include/policy.h:375
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff816dc53f)
Location: security/apparmor/include/policy.h:375
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff816e44e2)
Location: security/apparmor/include/policy.h:375
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816fa292)
Location: security/apparmor/include/policy.h:406
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff816fac5f)
Location: security/apparmor/include/policy.h:406
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/lib.c (ffffffff816fd335)
Location: security/apparmor/include/policy.h:406
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81715a78)
Location: security/apparmor/include/policy.h:406
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8171db32)
Location: security/apparmor/include/policy.h:406
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81737032)
Location: security/apparmor/include/policy.h:416
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff8173786f)
Location: security/apparmor/include/policy.h:416
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/lib.c (ffffffff8173a895)
Location: security/apparmor/include/policy.h:416
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81754568)
Location: security/apparmor/include/policy.h:416
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8175c582)
Location: security/apparmor/include/policy.h:416
Inline: True
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
In security/apparmor/audit.c (ffff80001058e194)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffff80001058e420)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffff80001058fbdc)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffff80001059f3cc)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffff8000105a5994)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (c073f030)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (c073f378)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (c07409b0)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (c0750088)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (c075593c)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (c000000000700bfc)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (c000000000700f9c)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (c000000000703080)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (c0000000007191c8)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (c0000000007218a8)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (ffffffe0003dc1f2)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffe0003dc41e)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffe0003dd7d4)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffe0003ea6c4)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffe0003ef5a8)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (ffffffff81490bcf)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff81490e05)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff81492305)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff814a10d4)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff814a680d)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (ffffffff814815ef)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff81481825)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff81482d25)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff81491af4)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff8149722d)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (ffffffff8148cc6f)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff8148cea5)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff8148e3a5)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff8149d174)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff814a28ad)
Location: security/apparmor/include/policy.h:299
Inline: True
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
In security/apparmor/audit.c (ffffffff814a4aaf)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/capability.c (ffffffff814a4ce5)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/lib.c (ffffffff814a62b5)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_apply_modes_to_perms
```
```
In security/apparmor/file.c (ffffffff814b5714)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/file.c:aa_audit_file
```
```
In security/apparmor/mount.c (ffffffff814bb06d)
Location: security/apparmor/include/policy.h:299
Inline: True
```
</details>
</li>
</ul>

## Differences
