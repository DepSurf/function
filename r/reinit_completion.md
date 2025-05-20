# Function: <code>reinit_completion</code>

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
In fs/ecryptfs/crypto.c (ffffffff813053f2)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81397b7a)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ahash_wait
```
```
In drivers/char/hw_random/core.c (ffffffff8151ab11)
Location: include/linux/completion.h:86
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81559ea6)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
```
```
In drivers/ata/libata-eh.c (ffffffff815d8b84)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff815e746c)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In fs/ecryptfs/crypto.c (ffffffff8133968d)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813d3e5c)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ahash_wait
```
```
In crypto/drbg.c (0)
Location: include/linux/completion.h:86
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff8156d841)
Location: include/linux/completion.h:86
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815ad224)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/ata/libata-eh.c (ffffffff81632795)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81645d91)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In fs/ecryptfs/crypto.c (ffffffff8134f42d)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813eb89c)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ahash_wait
```
```
In crypto/drbg.c (0)
Location: include/linux/completion.h:86
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81599fa5)
Location: include/linux/completion.h:86
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815dbfe4)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/ata/libata-eh.c (ffffffff816638e5)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81676b91)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e6e07)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff816fff07)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/mmc/core/core.c (ffffffff817543fe)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
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
In fs/ecryptfs/crypto.c (ffffffff81363ed8)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813f7bbc)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ahash_wait
```
```
In crypto/drbg.c (0)
Location: include/linux/completion.h:86
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff815adf7f)
Location: include/linux/completion.h:86
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815f0b64)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
```
In drivers/ata/libata-eh.c (ffffffff816780b2)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff8168b321)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816faf51)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81715817)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726c58)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81772051)
Location: include/linux/completion.h:86
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
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
In fs/crypto/crypto.c (ffffffff812cfcef)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d08e5)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0efb)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81388c5a)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81420c95)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8143a4c6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8143d081)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814426b8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In drivers/tty/serdev/core.c (ffffffff816097c8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff81614950)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816580b4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/mfd/da9052-core.c (ffffffff8168ba02)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff816e16f2)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff816f4ca1)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81767a8e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81786a37)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817982a8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff817e8131)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
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
In kernel/kthread.c (ffffffff810b3754)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In fs/crypto/crypto.c (ffffffff812fa5dd)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812faef9)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fba50)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7ab8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81453151)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8146ceb8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fec5)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81475547)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In drivers/tty/serdev/core.c (ffffffff81643038)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff8164e568)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81693b28)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/mfd/da9052-core.c (ffffffff816c7aa3)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff8171e0a2)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81732cc9)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a8dd8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c7af8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817daf54)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd3c9)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81831547)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
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
In kernel/watchdog.c (ffffffff81176f3b)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/crypto/crypto.c (ffffffff8130f924)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff813102d0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310fcf)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0fbe)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814702b5)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff814894a5)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814901c4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8149345c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffffffff8166126f)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff8166c7f8)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b41ad)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
```
In drivers/mfd/da9052-core.c (ffffffff816e8f63)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81740982)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81755783)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817ced48)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817ef198)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81802594)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8185d527)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
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
In kernel/watchdog.c (ffffffff81183d9b)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffffffff81331ea6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/crypto/crypto.c (ffffffff81336dbb)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81337718)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff813386f5)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fbba0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8149dc72)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b70c6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bd37c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c1016)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffffffff81696caf)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff816a2432)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816eb445)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff81722641)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff8177c69a)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff8179186e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180f13b)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8182fce8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843451)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818a1178)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In net/packet/af_packet.c (ffffffff81a55f76)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff8118fc10)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffffffff81345a66)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/crypto/crypto.c (ffffffff8134a98e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134b2d6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e504)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81350581)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff814159fe)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b80b2)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814d02e6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814d6080)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9e46)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffffffff816b983f)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff816c51d3)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8170f405)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff817468e1)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff817a033b)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff817b546e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184024b)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffffffff818474a6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861618)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81874dd1)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818d3468)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In net/packet/af_packet.c (ffffffff81a8d456)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff811a4835)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffffffff81381442)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/io-wq.c (ffffffff8138b5e3)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/crypto/crypto.c (ffffffff813900ee)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81390944)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8139429f)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81396fad)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff81463d8e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff815170c5)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff81530345)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81535c5a)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815393f1)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff815825be)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In drivers/tty/serdev/core.c (ffffffff8176dbcf)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff81779240)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/iommu/intel/svm.c (ffffffff817a932a)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/base/power/main.c (ffffffff817caa15)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff818045e1)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81864d50)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff8187c3d9)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81913eea)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81919b38)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819350b2)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949baf)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff819a5b68)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c4e3a)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_simple_command
```
```
In net/packet/af_packet.c (ffffffff81b88186)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff811a18d5)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/zswap.c (ffffffff812cd671)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/io_uring.c (ffffffff8138f47b)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_files_unregister
```
```
In fs/io-wq.c (ffffffff8139c7cf)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/crypto/crypto.c (ffffffff813a172e)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a1dc4)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a575f)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813a8bdd)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff8147f54e)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81534285)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8154d293)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81552bca)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815561b9)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff8159f56a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In drivers/tty/serdev/core.c (ffffffff817885af)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff81793a4c)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/iommu/intel/svm.c (ffffffff817b531a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/base/power/main.c (ffffffff817df4c5)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff81815011)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81873b50)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff8188a7c6)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191b50a)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81920433)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c122)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f87f)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff819a8928)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c506a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_simple_command
```
```
In net/packet/af_packet.c (ffffffff81b97c6b)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff811a24c7)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/zswap.c (ffffffff812d40f9)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/io_uring.c (ffffffff8139e366)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/crypto/crypto.c (ffffffff813a88bc)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a8f64)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac83f)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813afc4c)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff81484ee1)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d29b)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8155520e)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8155b48a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e93a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff815a6271)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In drivers/tty/serdev/core.c (ffffffff8176beff)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff81776c05)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/iommu/intel/svm.c (ffffffff8179873a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/base/power/main.c (ffffffff817c38a5)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff817f96f1)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81856179)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff8186d172)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818feaca)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81903b33)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f6b2)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819334e5)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8198d5fb)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819aa037)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_simple_command
```
```
In net/packet/af_packet.c (ffffffff81b86c79)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff811cbca7)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/zswap.c (ffffffff81319dc3)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/io_uring.c (ffffffff813ee4cb)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/crypto/crypto.c (ffffffff813f7ffc)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813f86f4)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc1af)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813ff83c)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff814dc561)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159c11b)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815b623e)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815bbe2a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfc93)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff8160ed91)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In drivers/tty/serdev/core.c (ffffffff817f163f)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff817fc5d5)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/iommu/intel/svm.c (ffffffff81820ebf)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/base/power/main.c (ffffffff8184dc35)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff81882b82)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff818e4818)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff818fd122)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199dc3a)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a3be0)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2462)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d68a6)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81a38c47)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81a578e7)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_simple_command
```
```
In net/packet/af_packet.c (ffffffff81c5352d)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff811ffa59)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/zswap.c (ffffffff813856d4)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff8146add4)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8146b41d)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f634)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff814734ba)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff8156a379)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816410f9)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8165f4f6)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff816656ad)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a216)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff816c360c)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In io_uring/io_uring.c (ffffffff81e90c47)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
```
```
In drivers/acpi/acpi_pcc.c (ffffffff81842f25)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
```
```
In drivers/tty/serdev/core.c (ffffffff81931c6f)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff8193b22c)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/iommu/intel/svm.c (ffffffff81961047)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/base/power/main.c (ffffffff819932c5)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff819cb532)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81a35bb5)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81a4e761)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afaeea)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b01594)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b22822)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39408)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81ba5ca8)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81bc73e4)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_simple_command
```
```
In net/packet/af_packet.c (ffffffff81df6d21)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff81247479)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/zswap.c (ffffffff8140343d)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff814fbf04)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff814fc895)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500db4)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff8150534a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff8160e109)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f9065)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff81718926)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff817204bd)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817247e7)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff81784aa1)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In io_uring/rsrc.c (ffffffff817a1109)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/acpi/acpi_pcc.c (ffffffff8197a0e5)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
```
```
In drivers/tty/serdev/core.c (ffffffff81a9062f)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b903)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/iommu/intel/svm.c (ffffffff81ac9bd8)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/base/power/main.c (ffffffff81b03975)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff81b432c2)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81bba6f5)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81bd69d1)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c895fa)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c90587)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb50a2)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf188)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81d47fc8)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d70064)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_simple_command
```
```
In net/packet/af_packet.c (ffffffff81fcb32e)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff8125e539)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/zswap.c (ffffffff81436a05)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff81533234)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81533e05)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538441)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81645f74)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/keys/dh.c (ffffffff81692936)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff817331d0)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/akcipher.c (ffffffff8174755b)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_post
```
```
In crypto/gcm.c (ffffffff81754296)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8175bdb5)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff817c4e01)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In drivers/acpi/acpi_pcc.c (ffffffff819c0b75)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
```
```
In drivers/tty/serdev/core.c (ffffffff81adbe3f)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff81ae725b)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/iommu/intel/svm.c (ffffffff81b16768)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/base/power/main.c (ffffffff81b519d5)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff81b96632)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81c11f9e)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81c2d401)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf07fa)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf6d75)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1c712)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d37287)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81db28c8)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81dddd24)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_simple_command
```
```
In net/packet/af_packet.c (ffffffff8202c62a)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff81278479)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/zswap.c (ffffffff81470f63)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
```
```
In fs/crypto/crypto.c (ffffffff81568132)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/crypto/fname.c (ffffffff81568d95)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d591)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8167f434)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/keys/dh.c (ffffffff816cef06)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81773c20)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/akcipher.c (ffffffff817893cb)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_post
```
```
In crypto/gcm.c (ffffffff81795c06)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8179dcb5)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff81809af1)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In drivers/acpi/acpi_pcc.c (ffffffff81a0b565)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f0dd)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a62b)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6d248)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_drain_pasid_prq
  - drivers/iommu/intel/svm.c:intel_drain_pasid_prq
```
```
In drivers/base/power/main.c (ffffffff81ba9c55)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_async_fn
```
```
In drivers/mfd/da9052-core.c (ffffffff81bea602)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81c67183)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81cdfe01)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da601a)
Location: include/linux/completion.h:97
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dac72f)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2462)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded507)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81e6ac58)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e93bf7)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_simple_command
```
```
In net/packet/af_packet.c (ffffffff820fc0c7)
Location: include/linux/completion.h:97
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffff8000102073f8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffff800010403cd8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
```
In fs/crypto/crypto.c (ffff80001040b180)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffff80001040bcd4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f728)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffff800010412250)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6fc8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b03ec)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffff8000105cc7c4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffff8000105d1e54)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5c6c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffff8000108a958c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffff8000108b71d0)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffff8000108ffa84)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffff800010943304)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffff8000109abc54)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffff8000109c8c0c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/spi/spi-fsl-spi.c (ffff8000109cc59c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ce098)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e5bb8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7ee20)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a85dc8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9b58)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abc1f0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abd51c)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mmc/core/core.c (ffff800010b2c904)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e630)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_property_list
```
```
In drivers/firmware/ti_sci.c (ffff800010b50f10)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56ef0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
```
```
In drivers/firmware/imx/imx-scu.c (ffff800010b61f50)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc
  - drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc
```
```
In net/packet/af_packet.c (ffff800010d59004)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (c044617c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (c05d7758)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/crypto/crypto.c (c05d8348)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c05d8ae4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c05dc4e8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/verity/hash_algs.c (c05de8c8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (c06b4d48)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
```
In security/integrity/ima/ima_crypto.c (c075fba0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c077a6a8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c077f6f8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (c07836cc)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (c093a894)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read
```
```
In drivers/tty/serdev/core.c (c09a5df4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (c09b0e90)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (c09e9dcc)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (c0a2c4c4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (c0a7b5c8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (c0ab2848)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/spi/spi-fsl-spi.c (c0ab59a8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab6f70)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac8cb8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/usb/host/xhci-ring.c (c0b522c0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (c0b58fdc)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b99210)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9aa2c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9d8b4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
```
```
In drivers/mmc/core/core.c (c0c07c60)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/firmware/arm_scmi/driver.c (c0c382b0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
```
```
In drivers/firmware/imx/imx-scu.c (c0c406b4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc
  - drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c74974)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:emc_prepare_timing_change
```
```
In net/packet/af_packet.c (c0e5a9d4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/powerpc/platforms/pseries/suspend.c (c0000000001044a4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/suspend.c:pseries_prepare_late
```
```
In kernel/watchdog.c (c000000000283a30)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (c0000000005108a0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/crypto/crypto.c (c000000000517c8c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c000000000518a2c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c00000000051d20c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (c00000000051ffdc)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (c000000000638308)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (c00000000072ffbc)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c000000000757c6c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c00000000075ee24)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (c00000000076448c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (c000000000940be4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (c00000000095153c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/base/power/main.c (c00000000099cda0)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (c0000000009ec808)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (c000000000a72dc8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (c000000000a8a650)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/spi/spi-fsl-spi.c (c000000000a8eab4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
```
In drivers/usb/host/xhci-ring.c (c000000000b57840)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (c000000000b60350)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d62c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (c000000000c255fc)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In net/packet/af_packet.c (c000000000e94b4c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffe000169ae2)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffffffe0002b11a0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/crypto/crypto.c (ffffffe0002b4e82)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffe0002b575c)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b86ac)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/verity/hash_algs.c (ffffffe0002ba2a8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffe000365b6e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f8076)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffe00041071a)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffe0004155e8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419dda)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffffffe00055eca2)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffe000567f32)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffe0005b60ae)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffe0006092ce)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffe000618f0e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061b7fc)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c78a)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000695b02)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffffffe00069bb4a)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006bed5e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffe0007069f6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In net/packet/af_packet.c (ffffffe0008912fc)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff81188230)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffffffff8133e046)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/crypto/crypto.c (ffffffff81342f6e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813438b6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346ae4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81348b61)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff8140dfde)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b0692)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c88c6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ce660)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2426)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffffffff8167f29f)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff8168ac23)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816d5145)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff81703951)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81765425)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81779f4e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f85fb)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817ff856)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/mmc/core/core.c (ffffffff81876e28)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In net/packet/af_packet.c (ffffffff81a2cae6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff8117b370)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffffffff8132ed06)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/crypto/crypto.c (ffffffff81333c4e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81334596)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813377c4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81339841)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff813fea5e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a10b2)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b92e6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bf080)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2e46)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/char/hw_random/core.c (ffffffff81668623)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816afdf5)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff816d7751)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff81745285)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff81759cfe)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bd79b)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817c49f6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184e98f)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_bus_suspend
```
```
In net/packet/af_packet.c (ffffffff819e9cd6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff81186000)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffffffff8133bb16)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/crypto/crypto.c (ffffffff81340a3e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81341386)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813445b4)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81346631)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b35e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac722)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c4956)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ca6f0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce4b6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffffffff816ad67f)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff816b8e93)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817030c5)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff81739da1)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff817951bb)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff817aa2ee)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818350cb)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8183c326)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818557a8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff818689eb)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_remove
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_resume
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_suspend
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a281)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818c82c8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In net/packet/af_packet.c (ffffffff81a98696)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/watchdog.c (ffffffff81193950)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In fs/io_uring.c (ffffffff8134ecc6)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/crypto/crypto.c (ffffffff81353d3e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81354686)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81357894)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81359911)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/ecryptfs/crypto.c (ffffffff81420ffe)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c5172)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814dd426)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814e31c0)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6f86)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffffffff816c7adf)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_write
```
```
In drivers/char/hw_random/core.c (ffffffff816d3463)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8171d945)
Location: include/linux/completion.h:98
Inline: True
```
```
In drivers/mfd/da9052-core.c (ffffffff817551e1)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
```
In drivers/ata/libata-eh.c (ffffffff817af02b)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/spi/spi.c (ffffffff817c418e)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184f3eb)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffffffff818567cf)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818708d8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81884211)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818e4dc8)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In net/packet/af_packet.c (ffffffff81aa4d30)
Location: include/linux/completion.h:98
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
