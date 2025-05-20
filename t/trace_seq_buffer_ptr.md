# Function: <code>trace_seq_buffer_ptr</code>

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
In kernel/trace/trace_output.c (ffffffff811538a4)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff815b75c7)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff815db74e)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
```
```
In drivers/firmware/efi/cper.c (ffffffff816d482e)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff8115cc9f)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff8160fcf0)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff8163596c)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff817381ee)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff8116756f)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff8163f580)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff81666a0c)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff8176b38e)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff8116a8b0)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:54
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffff8167b19c)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff817897ce)
Location: include/linux/trace_seq.h:54
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811779e0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffff816e47fc)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff817ffa7e)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff81186bd0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffff81721095)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff818489a5)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff81194540)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffff81743985)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff81874c15)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811a2270)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffff8177f725)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff818b8e45)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811adc50)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffff817a33e5)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb845)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811c6000)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff8183f206)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff81867145)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff819befb5)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811c3630)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff8184f866)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff81875f55)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff819c0a25)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811c46b0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff81832d76)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff81858745)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff819a5125)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811efb70)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff818bedc6)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff818e7165)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff81a52463)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff812280b0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff81a0b237)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff81a38845)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff81bc154c)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff812736a0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (ffffffff81b8ac67)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff81bbd7e5)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff81d65cdc)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff8128ab20)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In kernel/trace/trace_seq.c (ffffffff8128cbc0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_acquire
```
```
In drivers/scsi/scsi_trace.c (ffffffff81bdebd5)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff81c15035)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff81dd0e0c)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff812a5ed0)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In kernel/trace/trace_seq.c (ffffffff812a7f90)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_acquire
```
```
In drivers/scsi/scsi_trace.c (ffffffff81c33ac5)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/ata/libata-trace.c (ffffffff81c6a235)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff81e89bbc)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffff80001022af78)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffff8000109af07c)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffff800010b5eb38)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (c04685c4)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq_u64
  - kernel/trace/trace_output.c:trace_print_symbols_seq_u64
  - kernel/trace/trace_output.c:trace_print_flags_seq_u64
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (c0a7e448)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
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
In kernel/trace/trace_output.c (c0000000002b2cf8)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (c000000000a767e0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
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
In kernel/trace/trace_output.c (ffffffe000185142)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffe00060c068)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
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
In kernel/trace/trace_output.c (ffffffff811a6270)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/nvme/host/trace.c (ffffffff81749435)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/nvme/host/trace.c:nvme_trace_disk_name
```
```
In drivers/ata/libata-trace.c (ffffffff817684a5)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
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
In kernel/trace/trace_output.c (ffffffff811991f0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/nvme/host/trace.c (ffffffff8172b025)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/nvme/host/trace.c:nvme_trace_disk_name
```
```
In drivers/ata/libata-trace.c (ffffffff81748305)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff81845f45)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811a4040)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffff81798265)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff818e06a5)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
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
In kernel/trace/trace_output.c (ffffffff811b1dd0)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/trace_seq.h:55
Inline: True
```
```
In drivers/ata/libata-trace.c (ffffffff817b20d5)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
```
In drivers/firmware/efi/cper.c (ffffffff818fd145)
Location: include/linux/trace_seq.h:55
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
</details>
</li>
</ul>

## Differences
