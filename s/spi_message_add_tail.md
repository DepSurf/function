# Function: <code>spi_message_add_tail</code>

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
In drivers/base/regmap/regmap-spi.c (ffffffff8156ace0)
Location: include/linux/spi/spi.h:772
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:spi_write
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81586b83)
Location: include/linux/spi/spi.h:772
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_write
  - drivers/mfd/tps65912-spi.c:tps65912_spi_read
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158b060)
Location: include/linux/spi/spi.h:772
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff815e84e4)
Location: include/linux/spi/spi.h:772
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
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
In drivers/base/regmap/regmap-spi.c (ffffffff815bf883)
Location: include/linux/spi/spi.h:844
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:spi_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e02cb)
Location: include/linux/spi/spi.h:844
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81646dd0)
Location: include/linux/spi/spi.h:844
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
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
In drivers/base/regmap/regmap-spi.c (ffffffff815eec93)
Location: include/linux/spi/spi.h:848
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160cf6b)
Location: include/linux/spi/spi.h:848
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81677ec0)
Location: include/linux/spi/spi.h:848
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
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
In drivers/base/regmap/regmap-spi.c (ffffffff81602eb3)
Location: include/linux/spi/spi.h:883
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8162108b)
Location: include/linux/spi/spi.h:883
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8168c5bc)
Location: include/linux/spi/spi.h:883
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
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
In drivers/base/regmap/regmap-spi.c (ffffffff8166b283)
Location: include/linux/spi/spi.h:883
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816898ab)
Location: include/linux/spi/spi.h:883
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff816f5f6c)
Location: include/linux/spi/spi.h:883
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
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
In drivers/tty/serial/max310x.c (ffffffff8163f99b)
Location: include/linux/spi/spi.h:879
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816a6dcb)
Location: include/linux/spi/spi.h:879
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c59f5)
Location: include/linux/spi/spi.h:879
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81733a00)
Location: include/linux/spi/spi.h:879
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81734301)
Location: include/linux/spi/spi.h:879
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff8165dbab)
Location: include/linux/spi/spi.h:877
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c77cb)
Location: include/linux/spi/spi.h:877
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e6de4)
Location: include/linux/spi/spi.h:877
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81756470)
Location: include/linux/spi/spi.h:877
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817570b9)
Location: include/linux/spi/spi.h:877
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff8169283b)
Location: include/linux/spi/spi.h:927
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81702a7e)
Location: include/linux/spi/spi.h:927
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817205be)
Location: include/linux/spi/spi.h:927
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81792527)
Location: include/linux/spi/spi.h:927
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81793718)
Location: include/linux/spi/spi.h:927
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff816b53db)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81726dce)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8174484e)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817b60f7)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817b7268)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff8176822f)
Location: include/linux/spi/spi.h:1024
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817e339e)
Location: include/linux/spi/spi.h:1024
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff818021d4)
Location: include/linux/spi/spi.h:1024
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8187cf3c)
Location: include/linux/spi/spi.h:1024
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8187df22)
Location: include/linux/spi/spi.h:1024
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff81783072)
Location: include/linux/spi/spi.h:1049
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817f7ffe)
Location: include/linux/spi/spi.h:1049
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8181307a)
Location: include/linux/spi/spi.h:1049
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8188b8ec)
Location: include/linux/spi/spi.h:1049
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8188c4a8)
Location: include/linux/spi/spi.h:1049
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff8176695a)
Location: include/linux/spi/spi.h:1047
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817dc78e)
Location: include/linux/spi/spi.h:1047
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f7776)
Location: include/linux/spi/spi.h:1047
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8186e245)
Location: include/linux/spi/spi.h:1047
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8186f073)
Location: include/linux/spi/spi.h:1047
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff817eb32a)
Location: include/linux/spi/spi.h:1051
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff8186818e)
Location: include/linux/spi/spi.h:1051
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81880aa6)
Location: include/linux/spi/spi.h:1051
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff818fe2e5)
Location: include/linux/spi/spi.h:1051
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff818ff192)
Location: include/linux/spi/spi.h:1051
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff8192b91c)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff819b09f2)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819c9202)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81a4faa6)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81a50766)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b24a6d)
Location: include/linux/spi/spi.h:1121
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b40578)
Location: include/linux/spi/spi.h:1121
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81bd74bc)
Location: include/linux/spi/spi.h:1121
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81bd990c)
Location: include/linux/spi/spi.h:1121
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b74b6f)
Location: include/linux/spi/spi.h:1151
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b938e5)
Location: include/linux/spi/spi.h:1151
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81c2dee6)
Location: include/linux/spi/spi.h:1151
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81c30328)
Location: include/linux/spi/spi.h:1151
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/base/regmap/regmap-spi.c (ffffffff81bc89bf)
Location: include/linux/spi/spi.h:1195
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be7885)
Location: include/linux/spi/spi.h:1195
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81ce0936)
Location: include/linux/spi/spi.h:1195
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81ce31e8)
Location: include/linux/spi/spi.h:1195
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffff800010898b84)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffff80001091c050)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (ffff800010930440)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffff800010940aa8)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffff8000109c9b40)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffff8000109caec8)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (c0994464)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (c0a01854)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (c0a119d8)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (c0a29f68)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (c0ab3590)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (c0ab4284)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (0)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (c0000000009c07e8)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (c0000000009d0464)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (c0000000009e9518)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (c000000000a8b7e4)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (c000000000a8c974)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffe00055b65c)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffe00059ba5a)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6b94)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b41a2)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffe000619b4e)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffe00061a834)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b350)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
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
In drivers/tty/serial/max310x.c (ffffffff8167ae3b)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816ecbae)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817028ee)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8177abd7)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8177bd48)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff81659f2b)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c71ee)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d66fe)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8175a987)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8175baf8)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff816a921b)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff8171a28e)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81737d0e)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817aaf77)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817ac0e8)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
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
In drivers/tty/serial/max310x.c (ffffffff816c367b)
Location: include/linux/spi/spi.h:930
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817355ee)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8175314e)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817c4f07)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817c6078)
Location: include/linux/spi/spi.h:930
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
</details>
</li>
</ul>

## Differences
