# Function: <code>xhci_dbc_queue_bulk_tx</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773d7e)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b43cf)
Location: drivers/usb/host/xhci-dbgcap.c:240
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da90e)
Location: drivers/usb/host/xhci-dbgcap.c:240
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b042)
Location: drivers/usb/host/xhci-dbgcap.c:240
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bd49)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e970)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
**Symbols:**

```
ffffffff8191e970-ffffffff8191ea63: xhci_dbc_queue_bulk_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925fd0)
Location: drivers/usb/host/xhci-dbgcap.c:245
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
**Symbols:**

```
ffffffff81925fd0-ffffffff819260c7: xhci_dbc_queue_bulk_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909620)
Location: drivers/usb/host/xhci-dbgcap.c:245
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
**Symbols:**

```
ffffffff81909620-ffffffff81909791: xhci_dbc_queue_bulk_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9ea0)
Location: drivers/usb/host/xhci-dbgcap.c:245
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
**Symbols:**

```
ffffffff819a9ea0-ffffffff819aa00e: xhci_dbc_queue_bulk_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b083d0)
Location: drivers/usb/host/xhci-dbgcap.c:245
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
**Symbols:**

```
ffffffff81b083d0-ffffffff81b08563: xhci_dbc_queue_bulk_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97930)
Location: drivers/usb/host/xhci-dbgcap.c:245
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
**Symbols:**

```
ffffffff81c97930-ffffffff81c97abc: xhci_dbc_queue_bulk_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfec60)
Location: drivers/usb/host/xhci-dbgcap.c:245
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
**Symbols:**

```
ffffffff81cfec60-ffffffff81cfedec: xhci_dbc_queue_bulk_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db3d60)
Location: drivers/usb/host/xhci-dbgcap.c:260
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
**Symbols:**

```
ffffffff81db3d60-ffffffff81db3eec: xhci_dbc_queue_bulk_tx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b9dc)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5de2c)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67964)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a074c)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9299)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840bc9)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b099)
Location: drivers/usb/host/xhci-dbgcap.c:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
