# Function: <code>tpm_buf_append_u32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81525f75)
Location: drivers/char/tpm/tpm.h:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579dfe)
Location: drivers/char/tpm/tpm.h:467
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a633b)
Location: drivers/char/tpm/tpm.h:478
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
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
In drivers/char/tpm/tpm-interface.c (ffffffff815b7224)
Location: drivers/char/tpm/tpm.h:493
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815bac60)
Location: drivers/char/tpm/tpm.h:493
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff815bbfc4)
Location: drivers/char/tpm/tpm.h:493
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
In drivers/char/tpm/tpm-interface.c (ffffffff8161de76)
Location: drivers/char/tpm/tpm.h:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81621304)
Location: drivers/char/tpm/tpm.h:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816224fa)
Location: drivers/char/tpm/tpm.h:486
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
In drivers/char/tpm/tpm-interface.c (ffffffff81657bc2)
Location: drivers/char/tpm/tpm.h:500
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b0e5)
Location: drivers/char/tpm/tpm.h:500
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c30a)
Location: drivers/char/tpm/tpm.h:500
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff81677641)
Location: drivers/char/tpm/tpm.h:476
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81679096)
Location: drivers/char/tpm/tpm.h:476
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8167967a)
Location: drivers/char/tpm/tpm.h:476
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ad2c4)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af829)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816afc99)
Location: drivers/char/tpm/tpm.h:366
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816cffa4)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d2522)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816d2999)
Location: drivers/char/tpm/tpm.h:366
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a1fe1)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814a3372)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81784eec)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81785a9d)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81786e87)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bf9ac)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c0b12)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8179c32c)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179cc9d)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8179df97)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c5c0c)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c70e1)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8177ee5c)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177f77d)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81780957)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e62c)
Location: include/linux/tpm.h:395
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151fbc1)
Location: include/linux/tpm.h:395
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8180517c)
Location: include/linux/tpm.h:395
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81805b0d)
Location: include/linux/tpm.h:395
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81806d67)
Location: include/linux/tpm.h:395
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b1c23)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b32c1)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81944b9c)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff819455c3)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81946977)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c77d)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165df51)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7a8c)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa85f3)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81aa9bf7)
Location: include/linux/tpm.h:397
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8169509d)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff81696891)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af32bc)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af3e23)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81af5237)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d16cd)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2f11)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b4684c)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b473e3)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81b48827)
Location: include/linux/tpm.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
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
In drivers/char/tpm/tpm1-cmd.c (ffff8000108ba720)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcfb4)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd4a4)
Location: drivers/char/tpm/tpm.h:366
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
In drivers/char/tpm/tpm1-cmd.c (c09b3b68)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (c09b63c4)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (c09b68a0)
Location: drivers/char/tpm/tpm.h:366
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
In drivers/char/tpm/tpm1-cmd.c (c00000000095ba8c)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (c00000000095ee24)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (c00000000095f2e4)
Location: drivers/char/tpm/tpm.h:366
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
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b10c)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f24c)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffe00056f800)
Location: drivers/char/tpm/tpm.h:366
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816959f4)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81697f72)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816983e9)
Location: drivers/char/tpm/tpm.h:366
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816733e4)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81675962)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81675dd9)
Location: drivers/char/tpm/tpm.h:366
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c3c64)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c61e2)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816c6659)
Location: drivers/char/tpm/tpm.h:366
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816de219)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e06d7)
Location: drivers/char/tpm/tpm.h:366
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816e0b41)
Location: drivers/char/tpm/tpm.h:366
Inline: True
```
</details>
</li>
</ul>

## Differences
