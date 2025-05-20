# Function: <code>spi_message_init_no_memset</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff815bf87b)
Location: include/linux/spi/spi.h:831
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:spi_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e02e4)
Location: include/linux/spi/spi.h:831
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81646da0)
Location: include/linux/spi/spi.h:831
Inline: True
Inline callers:
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
In drivers/base/regmap/regmap-spi.c (ffffffff815eec8b)
Location: include/linux/spi/spi.h:835
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160cf84)
Location: include/linux/spi/spi.h:835
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81677e90)
Location: include/linux/spi/spi.h:835
Inline: True
Inline callers:
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
In drivers/base/regmap/regmap-spi.c (ffffffff81602eab)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8162107a)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8168c582)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
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
In drivers/base/regmap/regmap-spi.c (ffffffff8166b27b)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8168989a)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff816f5f32)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff8163f989)
Location: include/linux/spi/spi.h:866
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816a6db8)
Location: include/linux/spi/spi.h:866
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c59cd)
Location: include/linux/spi/spi.h:866
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817339d2)
Location: include/linux/spi/spi.h:866
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817340b4)
Location: include/linux/spi/spi.h:866
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff8165db99)
Location: include/linux/spi/spi.h:864
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c77b8)
Location: include/linux/spi/spi.h:864
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e6dc4)
Location: include/linux/spi/spi.h:864
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81756442)
Location: include/linux/spi/spi.h:864
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81756e67)
Location: include/linux/spi/spi.h:864
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff81692829)
Location: include/linux/spi/spi.h:914
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81702a6b)
Location: include/linux/spi/spi.h:914
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817205ac)
Location: include/linux/spi/spi.h:914
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817924e8)
Location: include/linux/spi/spi.h:914
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817934b8)
Location: include/linux/spi/spi.h:914
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff816b53c9)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81726dbb)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8174483c)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817b60b8)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817b7008)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff817681fb)
Location: include/linux/spi/spi.h:1011
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817e338b)
Location: include/linux/spi/spi.h:1011
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff818021bc)
Location: include/linux/spi/spi.h:1011
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8187cf04)
Location: include/linux/spi/spi.h:1011
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8187de4b)
Location: include/linux/spi/spi.h:1011
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff8178303e)
Location: include/linux/spi/spi.h:1036
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817f7feb)
Location: include/linux/spi/spi.h:1036
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8181303e)
Location: include/linux/spi/spi.h:1036
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8188b8b4)
Location: include/linux/spi/spi.h:1036
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8188c3d1)
Location: include/linux/spi/spi.h:1036
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff81766935)
Location: include/linux/spi/spi.h:1034
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817dc77b)
Location: include/linux/spi/spi.h:1034
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f775c)
Location: include/linux/spi/spi.h:1034
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8186e213)
Location: include/linux/spi/spi.h:1034
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8186ef8e)
Location: include/linux/spi/spi.h:1034
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff817eb305)
Location: include/linux/spi/spi.h:1038
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff8186817b)
Location: include/linux/spi/spi.h:1038
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81880a8c)
Location: include/linux/spi/spi.h:1038
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff818fe2b3)
Location: include/linux/spi/spi.h:1038
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff818ff096)
Location: include/linux/spi/spi.h:1038
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff8192b90f)
Location: include/linux/spi/spi.h:1029
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff819b09db)
Location: include/linux/spi/spi.h:1029
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819c91d9)
Location: include/linux/spi/spi.h:1029
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81a4fa72)
Location: include/linux/spi/spi.h:1029
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81a5067b)
Location: include/linux/spi/spi.h:1029
Inline: True
Inline callers:
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b24a56)
Location: include/linux/spi/spi.h:1108
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b4054c)
Location: include/linux/spi/spi.h:1108
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81bd7488)
Location: include/linux/spi/spi.h:1108
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81bd981e)
Location: include/linux/spi/spi.h:1108
Inline: True
Inline callers:
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b74b5b)
Location: include/linux/spi/spi.h:1138
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b938c1)
Location: include/linux/spi/spi.h:1138
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81c2deb2)
Location: include/linux/spi/spi.h:1138
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81c3023a)
Location: include/linux/spi/spi.h:1138
Inline: True
Inline callers:
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
In drivers/base/regmap/regmap-spi.c (ffffffff81bc89ab)
Location: include/linux/spi/spi.h:1182
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be7861)
Location: include/linux/spi/spi.h:1182
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81ce0902)
Location: include/linux/spi/spi.h:1182
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81ce30f5)
Location: include/linux/spi/spi.h:1182
Inline: True
Inline callers:
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
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffff80001091c03c)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (ffff800010930440)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffff800010940aa8)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffff8000109c9b28)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffff8000109cae58)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (c099442c)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (c0a01828)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (c0a119b8)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (c0a29f20)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (c0ab355c)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (c0ab41b8)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
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
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (c0000000009c07d8)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (c0000000009d043c)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (c0000000009e94e8)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (c000000000a8b7ac)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (c000000000a8c734)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffe00055b64c)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffe00059ba52)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6b84)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4180)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffe000619afe)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffe00061a6c4)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b322)
Location: include/linux/spi/spi.h:917
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
In drivers/tty/serial/max310x.c (ffffffff8167ae29)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816ecb9b)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817028dc)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8177ab98)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8177bae8)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff81659f19)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c71db)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d66ec)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8175a948)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8175b898)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff816a9209)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff8171a27b)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81737cfc)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817aaf38)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817abe88)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff816c3669)
Location: include/linux/spi/spi.h:917
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817355db)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8175313c)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817c4ec8)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817c5e18)
Location: include/linux/spi/spi.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
</details>
</li>
</ul>

## Differences
