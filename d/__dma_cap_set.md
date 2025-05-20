# Function: <code>__dma_cap_set</code>

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
In drivers/rapidio/rio.c (ffffffff814596f7)
Location: include/linux/dmaengine.h:1039
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff814bced8)
Location: include/linux/dmaengine.h:1039
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:__dma_request_channel
  - drivers/dma/dmaengine.c:dma_request_slave_channel
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509559)
Location: include/linux/dmaengine.h:1039
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff814a7187)
Location: include/linux/dmaengine.h:1183
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff8150d961)
Location: include/linux/dmaengine.h:1183
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b469)
Location: include/linux/dmaengine.h:1183
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff814c9297)
Location: include/linux/dmaengine.h:1207
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81539a91)
Location: include/linux/dmaengine.h:1207
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81587c12)
Location: include/linux/dmaengine.h:1207
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff814d50f7)
Location: include/linux/dmaengine.h:1218
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff8154d2e1)
Location: include/linux/dmaengine.h:1218
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c0a2)
Location: include/linux/dmaengine.h:1218
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff815155a7)
Location: include/linux/dmaengine.h:1207
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff815b08a9)
Location: include/linux/dmaengine.h:1207
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816013a2)
Location: include/linux/dmaengine.h:1207
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8154a957)
Location: include/linux/dmaengine.h:1211
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff815e8cf2)
Location: include/linux/dmaengine.h:1211
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163a662)
Location: include/linux/dmaengine.h:1211
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff815626a7)
Location: include/linux/dmaengine.h:1214
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81602a89)
Location: include/linux/dmaengine.h:1214
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658980)
Location: include/linux/dmaengine.h:1214
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff81592ac7)
Location: include/linux/dmaengine.h:1202
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81635299)
Location: include/linux/dmaengine.h:1202
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168de60)
Location: include/linux/dmaengine.h:1202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff815b3d47)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81656fb5)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b03b0)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8165d157)
Location: include/linux/dmaengine.h:1334
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff8170725b)
Location: include/linux/dmaengine.h:1334
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817637c2)
Location: include/linux/dmaengine.h:1334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8167e877)
Location: include/linux/dmaengine.h:1379
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff817246eb)
Location: include/linux/dmaengine.h:1379
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177e7b8)
Location: include/linux/dmaengine.h:1379
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff816616f7)
Location: include/linux/dmaengine.h:1381
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff817059ab)
Location: include/linux/dmaengine.h:1381
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81709758)
Location: include/linux/dmaengine.h:1381
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81762108)
Location: include/linux/dmaengine.h:1381
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff816d4487)
Location: include/linux/dmaengine.h:1379
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff8178127b)
Location: include/linux/dmaengine.h:1379
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8178510e)
Location: include/linux/dmaengine.h:1379
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e6168)
Location: include/linux/dmaengine.h:1379
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff817fe597)
Location: include/linux/dmaengine.h:1402
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff818b7bdb)
Location: include/linux/dmaengine.h:1402
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbced)
Location: include/linux/dmaengine.h:1402
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff819256e2)
Location: include/linux/dmaengine.h:1402
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8192bdea)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81a04e5b)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07b5f)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a8d9)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a82112)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8197005a)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81a4dcbb)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a509d9)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53760)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acd712)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff819ba06a)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81a9995b)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c6a9)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f510)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b207e2)
Location: include/linux/dmaengine.h:1382
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffff80001073be70)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/video/fbdev/mx3fb.c (ffff800010760738)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/dma/dmaengine.c (ffff8000107fd568)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/amba-pl08x.c (ffff8000108026cc)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804700)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
```
In drivers/dma/mv_xor.c (ffff8000108080b8)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mv_xor_v2.c (ffff80001080921c)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff80001148ef74)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f530)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088b960)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/amba-pl011.c (ffff80001089573c)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
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
In drivers/rapidio/rio.c (c08c1c7c)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/video/fbdev/mx3fb.c (c08e3178)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/dma/dmaengine.c (c091e8d0)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/amba-pl08x.c (c092142c)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/mv_xor.c (c0925f2c)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mxs-dma.c (c158e96c)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (c158eedc)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/dma/tegra20-apb-dma.c (c092a7c8)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/dma/ti/edma.c (c092ef60)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
```
```
In drivers/dma/ti/omap-dma.c (c0931424)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (c093a994)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (c09892bc)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/amba-pl011.c (c0991820)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
```
```
In drivers/mtd/nand/raw/omap2.c (c0aabb80)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
```
```
In sound/core/pcm_dmaengine.c (c0c9cd80)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_request_channel
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_request_channel
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
In drivers/rapidio/rio.c (c00000000089555c)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (c0000000008c8470)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934278)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffe0004eb606)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/dma/dmaengine.c (ffffffe000516efe)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe000555364)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff815a7fb7)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff8161ce55)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81675e20)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff81597157)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81611545)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81654f00)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff815a8547)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff8164adf5)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a41f0)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff815c2ac7)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81665395)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816be680)
Location: include/linux/dmaengine.h:1204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
</details>
</li>
</ul>

## Differences
