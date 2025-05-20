# Function: <code>spi_message_init</code>

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
In drivers/base/regmap/regmap-spi.c (ffffffff8156aca0)
Location: include/linux/spi/spi.h:765
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:spi_write
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81586b4b)
Location: include/linux/spi/spi.h:765
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_write
  - drivers/mfd/tps65912-spi.c:tps65912_spi_read
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158b047)
Location: include/linux/spi/spi.h:765
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff815e84b4)
Location: include/linux/spi/spi.h:765
Inline: True
Inline callers:
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
In drivers/base/regmap/regmap-spi.c (ffffffff815bf843)
Location: include/linux/spi/spi.h:837
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:spi_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e02b5)
Location: include/linux/spi/spi.h:837
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81646d92)
Location: include/linux/spi/spi.h:837
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
In drivers/base/regmap/regmap-spi.c (ffffffff815eec53)
Location: include/linux/spi/spi.h:841
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160cf55)
Location: include/linux/spi/spi.h:841
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81677e82)
Location: include/linux/spi/spi.h:841
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
In drivers/base/regmap/regmap-spi.c (ffffffff81602e73)
Location: include/linux/spi/spi.h:876
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8162101d)
Location: include/linux/spi/spi.h:876
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8168c56e)
Location: include/linux/spi/spi.h:876
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
In drivers/base/regmap/regmap-spi.c (ffffffff8166b243)
Location: include/linux/spi/spi.h:876
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8168983d)
Location: include/linux/spi/spi.h:876
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff816f5f1e)
Location: include/linux/spi/spi.h:876
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
In drivers/tty/serial/max310x.c (ffffffff8163f964)
Location: include/linux/spi/spi.h:872
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816a6daf)
Location: include/linux/spi/spi.h:872
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c59bd)
Location: include/linux/spi/spi.h:872
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817339b1)
Location: include/linux/spi/spi.h:872
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8173408d)
Location: include/linux/spi/spi.h:872
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
In drivers/tty/serial/max310x.c (ffffffff8165db74)
Location: include/linux/spi/spi.h:870
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c77af)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e6db5)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81756421)
Location: include/linux/spi/spi.h:870
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81756e40)
Location: include/linux/spi/spi.h:870
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
In drivers/tty/serial/max310x.c (ffffffff81692804)
Location: include/linux/spi/spi.h:920
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81702a62)
Location: include/linux/spi/spi.h:920
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81720599)
Location: include/linux/spi/spi.h:920
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817924d1)
Location: include/linux/spi/spi.h:920
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81793494)
Location: include/linux/spi/spi.h:920
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
In drivers/tty/serial/max310x.c (ffffffff816b53a4)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81726db2)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81744829)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817b60a1)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817b6fe4)
Location: include/linux/spi/spi.h:923
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
In drivers/tty/serial/max310x.c (ffffffff817681f8)
Location: include/linux/spi/spi.h:1017
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817e3382)
Location: include/linux/spi/spi.h:1017
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff818021a7)
Location: include/linux/spi/spi.h:1017
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8187cedb)
Location: include/linux/spi/spi.h:1017
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8187de1d)
Location: include/linux/spi/spi.h:1017
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
In drivers/tty/serial/max310x.c (ffffffff8178303b)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817f7fe2)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8181302f)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8188b88b)
Location: include/linux/spi/spi.h:1042
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8188c3a3)
Location: include/linux/spi/spi.h:1042
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
In drivers/tty/serial/max310x.c (ffffffff81766932)
Location: include/linux/spi/spi.h:1040
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817dc772)
Location: include/linux/spi/spi.h:1040
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f7749)
Location: include/linux/spi/spi.h:1040
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8186e1f2)
Location: include/linux/spi/spi.h:1040
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8186ef6b)
Location: include/linux/spi/spi.h:1040
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
In drivers/tty/serial/max310x.c (ffffffff817eb302)
Location: include/linux/spi/spi.h:1044
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81868172)
Location: include/linux/spi/spi.h:1044
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81880a79)
Location: include/linux/spi/spi.h:1044
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff818fe292)
Location: include/linux/spi/spi.h:1044
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff818ff07b)
Location: include/linux/spi/spi.h:1044
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
Location: include/linux/spi/spi.h:1035
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff819b09d2)
Location: include/linux/spi/spi.h:1035
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819c91ca)
Location: include/linux/spi/spi.h:1035
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81a4fa56)
Location: include/linux/spi/spi.h:1035
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81a5065b)
Location: include/linux/spi/spi.h:1035
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b24a42)
Location: include/linux/spi/spi.h:1114
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b4053d)
Location: include/linux/spi/spi.h:1114
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81bd746c)
Location: include/linux/spi/spi.h:1114
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81bd97fe)
Location: include/linux/spi/spi.h:1114
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b74b52)
Location: include/linux/spi/spi.h:1144
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b938b2)
Location: include/linux/spi/spi.h:1144
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81c2de96)
Location: include/linux/spi/spi.h:1144
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81c3021a)
Location: include/linux/spi/spi.h:1144
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
In drivers/base/regmap/regmap-spi.c (ffffffff81bc89a2)
Location: include/linux/spi/spi.h:1188
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be7852)
Location: include/linux/spi/spi.h:1188
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff81ce08e6)
Location: include/linux/spi/spi.h:1188
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff81ce30d5)
Location: include/linux/spi/spi.h:1188
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
In drivers/tty/serial/max310x.c (ffff800010898b58)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffff80001091c024)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (ffff800010930414)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffff800010940aa8)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffff8000109c9ac4)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffff8000109cae08)
Location: include/linux/spi/spi.h:923
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
In drivers/tty/serial/max310x.c (c0994424)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (c0a01824)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (c0a119b4)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (c0a29f10)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (c0ab3548)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (c0ab41a4)
Location: include/linux/spi/spi.h:923
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
Location: include/linux/spi/spi.h:923
Inline: False
```
```
In drivers/base/regmap/regmap-spi.c (c0000000009c07bc)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (c0000000009d0434)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (c0000000009e94d0)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (c000000000a8b794)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (c000000000a8c718)
Location: include/linux/spi/spi.h:923
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
In drivers/tty/serial/max310x.c (ffffffe00055b644)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffe00059ba32)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6b7c)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4180)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffe000619afe)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffe00061a6bc)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b312)
Location: include/linux/spi/spi.h:923
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
In drivers/tty/serial/max310x.c (ffffffff8167ae04)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816ecb92)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817028c9)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8177ab81)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8177bac4)
Location: include/linux/spi/spi.h:923
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
In drivers/tty/serial/max310x.c (ffffffff81659ef4)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c71d2)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d66d9)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff8175a931)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff8175b874)
Location: include/linux/spi/spi.h:923
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
In drivers/tty/serial/max310x.c (ffffffff816a91e4)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff8171a272)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81737ce9)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817aaf21)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817abe64)
Location: include/linux/spi/spi.h:923
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
In drivers/tty/serial/max310x.c (ffffffff816c3644)
Location: include/linux/spi/spi.h:923
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817355d2)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81753129)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
```
In drivers/spi/spi.c (ffffffff817c4eb1)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
```
```
In drivers/spi/spi-mem.c (ffffffff817c5df4)
Location: include/linux/spi/spi.h:923
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
</details>
</li>
</ul>

## Differences
