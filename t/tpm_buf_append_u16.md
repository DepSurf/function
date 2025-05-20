# Function: <code>tpm_buf_append_u16</code>

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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81525ff9)
Location: drivers/char/tpm/tpm.h:479
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815796a7)
Location: drivers/char/tpm/tpm.h:460
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a5bd4)
Location: drivers/char/tpm/tpm.h:471
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
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
In drivers/char/tpm/tpm-interface.c (ffffffff815b793b)
Location: drivers/char/tpm/tpm.h:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815ba010)
Location: drivers/char/tpm/tpm.h:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm.h:479
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816207fc)
Location: drivers/char/tpm/tpm.h:479
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm.h:493
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165a5c9)
Location: drivers/char/tpm/tpm.h:493
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
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
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm.h:469
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81678f65)
Location: drivers/char/tpm/tpm.h:469
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ad7e0)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816afab9)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816d04c0)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d27b9)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a1d0a)
Location: include/linux/tpm.h:378
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814a37b3)
Location: include/linux/tpm.h:378
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff817853d8)
Location: include/linux/tpm.h:378
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff817869f1)
Location: include/linux/tpm.h:378
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bf6b4)
Location: include/linux/tpm.h:378
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c0f82)
Location: include/linux/tpm.h:378
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81c0a578)
Location: include/linux/tpm.h:378
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81c0a6fa)
Location: include/linux/tpm.h:378
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c5914)
Location: include/linux/tpm.h:387
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c74d1)
Location: include/linux/tpm.h:387
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81bfc00b)
Location: include/linux/tpm.h:387
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81bfc17d)
Location: include/linux/tpm.h:387
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e334)
Location: include/linux/tpm.h:388
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151ffba)
Location: include/linux/tpm.h:388
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81cfcd2f)
Location: include/linux/tpm.h:388
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81cfceb6)
Location: include/linux/tpm.h:388
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b1892)
Location: include/linux/tpm.h:390
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b372f)
Location: include/linux/tpm.h:390
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81ec5559)
Location: include/linux/tpm.h:390
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81ec5743)
Location: include/linux/tpm.h:390
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c3d2)
Location: include/linux/tpm.h:390
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165e40f)
Location: include/linux/tpm.h:390
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7489)
Location: include/linux/tpm.h:390
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa96ee)
Location: include/linux/tpm.h:390
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694cf2)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff81696d5f)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af2cc6)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af4f1a)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d1322)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d33df)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46256)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b484da)
Location: include/linux/tpm.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (ffff8000108ba22c)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bd214)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (c09b35f0)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (c09b6628)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (c00000000095b430)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (c00000000095ecd4)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056aa24)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f0cc)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff81695f10)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81698209)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff81673900)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81675bf9)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c4180)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c6479)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm1-cmd.c (ffffffff816de715)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e095e)
Location: drivers/char/tpm/tpm.h:359
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
</ul>

## Differences
