# Function: <code>xennet_handle_rx</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool xennet_handle_rx(struct netfront_queue *queue, unsigned int *eoi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1495
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
```
**Symbols:**

```
ffffffff8191e180-ffffffff8191e2a1: xennet_handle_rx (STB_LOCAL)
ffffffff81d11391-ffffffff81d113a6: xennet_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool xennet_handle_rx(struct netfront_queue *queue, unsigned int *eoi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1532
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
```
**Symbols:**

```
ffffffff81a72660-ffffffff81a72766: xennet_handle_rx (STB_LOCAL)
ffffffff81edc015-ffffffff81edc02a: xennet_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool xennet_handle_rx(struct netfront_queue *queue, unsigned int *eoi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1532
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
```
**Symbols:**

```
ffffffff81c06090-ffffffff81c06196: xennet_handle_rx (STB_LOCAL)
ffffffff8209db55-ffffffff8209db6a: xennet_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool xennet_handle_rx(struct netfront_queue *queue, unsigned int *eoi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1532
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
```
**Symbols:**

```
ffffffff81c6b780-ffffffff81c6b886: xennet_handle_rx (STB_LOCAL)
ffffffff8211f0dd-ffffffff8211f0f2: xennet_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool xennet_handle_rx(struct netfront_queue *queue, unsigned int *eoi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1533
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
```
**Symbols:**

```
ffffffff81d20150-ffffffff81d20259: xennet_handle_rx (STB_LOCAL)
ffffffff822008b3-ffffffff822008c8: xennet_handle_rx.cold (STB_LOCAL)
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
