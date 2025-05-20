# Function: <code>tpm_transmit_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, void *cmd, int len, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81523ba0)
Location: drivers/char/tpm/tpm-interface.c:403
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_gen_interrupt
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_continue_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
```
**Symbols:**

```
ffffffff81523ba0-ffffffff81523c09: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, void *cmd, int len, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81576ad0)
Location: drivers/char/tpm/tpm-interface.c:403
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev
  - drivers/char/tpm/tpm-interface.c:tpm_continue_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_gen_interrupt
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
**Symbols:**

```
ffffffff81576ad0-ffffffff81576b38: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, const void *cmd, int len, unsigned int flags, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3190)
Location: drivers/char/tpm/tpm-interface.c:415
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev
  - drivers/char/tpm/tpm-interface.c:tpm_continue_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
**Symbols:**

```
ffffffff815a3190-ffffffff815a31f8: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_space *space, const void *buf, size_t bufsiz, size_t min_rsp_body_length, unsigned int flags, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b6ee0)
Location: drivers/char/tpm/tpm-interface.c:516
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev
  - drivers/char/tpm/tpm-interface.c:tpm_continue_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
**Symbols:**

```
ffffffff815b6ee0-ffffffff815b6f52: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_space *space, const void *buf, size_t bufsiz, size_t min_rsp_body_length, unsigned int flags, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161dc80)
Location: drivers/char/tpm/tpm-interface.c:534
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev
  - drivers/char/tpm/tpm-interface.c:tpm_continue_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
**Symbols:**

```
ffffffff8161dc80-ffffffff8161dcf2: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t bufsiz, size_t min_rsp_body_length, unsigned int flags, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81657990)
Location: drivers/char/tpm/tpm-interface.c:653
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev
  - drivers/char/tpm/tpm-interface.c:tpm_continue_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
**Symbols:**

```
ffffffff81657990-ffffffff81657a02: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t bufsiz, size_t min_rsp_body_length, unsigned int flags, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81676ce0)
Location: drivers/char/tpm/tpm-interface.c:394
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81676ce0-ffffffff81676d61: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff816ac987-ffffffff816ac9a0: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff816ac6f0-ffffffff816ac77b: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff816cf667-ffffffff816cf680: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff816cf450-ffffffff816cf4db: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:213
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff817844ed-ffffffff81784506: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff817842e0-ffffffff8178436b: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:213
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81c0a44a-ffffffff81c0a463: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff8179b830-ffffffff8179b8bb: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:213
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81bfbedd-ffffffff81bfbef6: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff8177e360-ffffffff8177e3eb: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:213
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81cfcb97-ffffffff81cfcbb0: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff81804560-ffffffff818045eb: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:213
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81ec537e-ffffffff81ec5398: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff81943ef0-ffffffff81943f9a: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa6b70)
Location: drivers/char/tpm/tpm-interface.c:213
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81aa6b70-ffffffff81aa6c26: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af23b0)
Location: drivers/char/tpm/tpm-interface.c:213
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81af23b0-ffffffff81af2466: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b45940)
Location: drivers/char/tpm/tpm-interface.c:213
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81b45940-ffffffff81b459f6: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b99e8)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffff8000108b99e8-ffff8000108b9aac: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2e20)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
c09b2e20-c09b2ecc: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095aa50)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
c00000000095aa50-c00000000095ab4c: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe000569e50)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffe000569e50-ffffffe000569f30: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff816950b7-ffffffff816950d0: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff81694ea0-ffffffff81694f2b: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff81672aa7-ffffffff81672ac0: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff81672890-ffffffff8167291b: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff816c3327-ffffffff816c3340: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff816c3110-ffffffff816c319b: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip *chip, struct tpm_buf *buf, size_t min_rsp_body_length, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:212
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
**Symbols:**

```
ffffffff816dd8f7-ffffffff816dd910: tpm_transmit_cmd.cold (STB_LOCAL)
ffffffff816dd6e0-ffffffff816dd76b: tpm_transmit_cmd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, cmd, len, desc</code> ➡️ <code>chip, cmd, len, flags, desc</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *cmd</code> ➡️ <code>const void *cmd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_space *space</code>
</li>
<li>
<b>Param added. </b>
<code>const void *buf</code>
</li>
<li>
<b>Param added. </b>
<code>size_t bufsiz</code>
</li>
<li>
<b>Param added. </b>
<code>size_t min_rsp_body_length</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *cmd</code>
</li>
<li>
<b>Param removed. </b>
<code>int len</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, cmd, len, flags, desc</code> ➡️ <code>chip, space, buf, bufsiz, min_rsp_body_length, flags, desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const void *buf</code> ➡️ <code>void *buf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct tpm_space *space</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t bufsiz</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, space, buf, bufsiz, min_rsp_body_length, flags, desc</code> ➡️ <code>chip, buf, min_rsp_body_length, desc</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *buf</code> ➡️ <code>struct tpm_buf *buf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
