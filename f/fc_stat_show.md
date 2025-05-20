# Function: <code>fc_stat_show</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170e350)
Location: drivers/scsi/scsi_transport_fc.c:1685
Inline: True
Direct callers:
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fc_non_bls_resp
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fc_seq_not_found
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fc_xid_busy
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fc_xid_not_found
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fc_no_free_exch_xid
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fc_no_free_exch
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fcp_frame_alloc_failures
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fcp_packet_aborts
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fcp_packet_alloc_failures
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fcp_output_megabytes
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fcp_input_megabytes
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fcp_control_requests
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fcp_output_requests
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_fcp_input_requests
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_invalid_crc_count
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_invalid_tx_word_count
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_prim_seq_protocol_err_count
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_loss_of_signal_count
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_loss_of_sync_count
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_link_failure_count
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_dumped_frames
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_error_frames
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_nos_count
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_lip_count
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_rx_words
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_rx_frames
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_tx_words
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_tx_frames
  - drivers/scsi/scsi_transport_fc.c:show_fcstat_seconds_since_last_reset
```
**Symbols:**

```
ffffffff8170e350-ffffffff8170e3e7: fc_stat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
