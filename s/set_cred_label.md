# Function: <code>set_cred_label</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff8145182e)
Location: security/apparmor/include/cred.h:34
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff81457055)
Location: security/apparmor/include/cred.h:34
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffff828cf1ba)
Location: security/apparmor/include/cred.h:34
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff8147f23d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff814848c1)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffff828e8c1c)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff81498f3d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff8149e7e1)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffff828f1708)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff814f1541)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff814f7a34)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff82d0679d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff8150e7e1)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff81514b84)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff82ff3b68)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff815151dd)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff8151b4a2)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff831fe686)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff8157318d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff8157952e)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff832e5998)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff8161047d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff8161765f)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8349c704)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff816c2edd)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff816ca4d7)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff83ed3c29)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff816fba8d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff81703149)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff836f8b7f)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff81738a40)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff81740942)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8392c07e)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffff80001058ebb0)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffff8000105946e0)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffff80001146b90c)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (c073fa3c)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (c0745600)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (c154456c)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (c000000000701a1c)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (c000000000709654)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (c00000000139a40c)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffe0003dc9f0)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffe0003e190c)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffe0000268e6)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff8149151d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff81496dc1)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffff828da5bc)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff81481f3d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff814877e1)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffff828d2cd8)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff8148d5bd)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff81492e61)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffff828ed330)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
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
In security/apparmor/task.c (ffffffff814a548d)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff814aae9b)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
```
In security/apparmor/lsm.c (ffffffff828f2752)
Location: security/apparmor/include/cred.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:apparmor_cred_alloc_blank
  - security/apparmor/lsm.c:apparmor_cred_free
```
</details>
</li>
</ul>

## Differences
