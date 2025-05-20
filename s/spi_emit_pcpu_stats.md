# Function: <code>spi_emit_pcpu_stats</code>

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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t spi_emit_pcpu_stats(struct spi_statistics *stat, char *buf, size_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c29b10)
Location: drivers/spi/spi.c:120
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_controller_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_controller_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_controller_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_controller_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_controller_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_controller_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_controller_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_controller_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_controller_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_controller_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:spi_controller_messages_show
```
**Symbols:**

```
ffffffff81c29b10-ffffffff81c29bd3: spi_emit_pcpu_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t spi_emit_pcpu_stats(struct spi_statistics *stat, char *buf, size_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdc360)
Location: drivers/spi/spi.c:120
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_controller_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_controller_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_controller_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_controller_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_controller_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_controller_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_controller_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_controller_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_controller_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_controller_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_controller_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:spi_controller_messages_show
```
**Symbols:**

```
ffffffff81cdc360-ffffffff81cdc423: spi_emit_pcpu_stats (STB_LOCAL)
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
