# Function: <code>mmc_io_rw_direct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff816ca2c0)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff816ca2c0-ffffffff816ca2de: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8172d280)
Location: drivers/mmc/core/sdio_ops.c:114
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff8172d280-ffffffff8172d29e: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81760240)
Location: drivers/mmc/core/sdio_ops.c:112
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff81760240-ffffffff81760257: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8177eaf0)
Location: drivers/mmc/core/sdio_ops.c:112
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff8177eaf0-ffffffff8177eb07: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff817f5090)
Location: drivers/mmc/core/sdio_ops.c:112
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff817f5090-ffffffff817f50a7: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8183e580)
Location: drivers/mmc/core/sdio_ops.c:112
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff8183e580-ffffffff8183e597: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8186a530)
Location: drivers/mmc/core/sdio_ops.c:112
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff8186a530-ffffffff8186a547: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818ae420)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff818ae420-ffffffff818ae437: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818e08b0)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff818e08b0-ffffffff818e08c7: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff819b38d0)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_select_driver_type
  - drivers/mmc/core/sdio.c:sdio_select_driver_type
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_fbr
  - drivers/mmc/core/sdio.c:sdio_read_fbr
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_get_pending_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_get_pending_irqs
```
**Symbols:**

```
ffffffff819b38d0-ffffffff819b38e7: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff819b5d50)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_select_driver_type
  - drivers/mmc/core/sdio.c:sdio_select_driver_type
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_fbr
  - drivers/mmc/core/sdio.c:sdio_read_fbr
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_get_pending_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_get_pending_irqs
```
**Symbols:**

```
ffffffff819b5d50-ffffffff819b5d67: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff8199a510)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff8199a510-ffffffff8199a527: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81a46e50)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff81a46e50-ffffffff81a46e67: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81bb4c60)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:mmc_sdio_switch_hs
  - drivers/mmc/core/sdio.c:mmc_sdio_switch_hs
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff81bb4c60-ffffffff81bb4c89: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81d59350)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:mmc_sdio_switch_hs
  - drivers/mmc/core/sdio.c:mmc_sdio_switch_hs
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff81d59350-ffffffff81d59379: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81dc3d00)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:mmc_sdio_switch_hs
  - drivers/mmc/core/sdio.c:mmc_sdio_switch_hs
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff81dc3d00-ffffffff81dc3d29: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81e7c5e0)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:mmc_sdio_switch_hs
  - drivers/mmc/core/sdio.c:mmc_sdio_switch_hs
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio.c:sdio_read_cccr
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff81e7c5e0-ffffffff81e7c609: mmc_io_rw_direct (STB_GLOBAL)
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
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffff800010b3aa60)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffff800010b3aa60-ffff800010b3aac4: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (c0c15434)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
c0c15434-c0c1546c: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (c000000000c37480)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
c000000000c37480-c000000000c37498: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffe0007123d6)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffe0007123d6-ffffffe000712428: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff81884270)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff81884270-ffffffff81884287: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818d5710)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff818d5710-ffffffff818d5727: mmc_io_rw_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card *card, int write, unsigned int fn, unsigned int addr, u8 in, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_ops.c (ffffffff818f2230)
Location: drivers/mmc/core/sdio_ops.c:108
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_io.c:sdio_f0_readb
  - drivers/mmc/core/sdio_io.c:sdio_writeb_readb
  - drivers/mmc/core/sdio_io.c:sdio_readb
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_set_block_size
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_disable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
  - drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs
```
**Symbols:**

```
ffffffff818f2230-ffffffff818f2247: mmc_io_rw_direct (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
