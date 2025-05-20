# Function: <code>xhci_do_dbc_init</code>

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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81774049)
Location: drivers/usb/host/xhci-dbgcap.c:824
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b46b0)
Location: drivers/usb/host/xhci-dbgcap.c:833
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817dac00)
Location: drivers/usb/host/xhci-dbgcap.c:834
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b280)
Location: drivers/usb/host/xhci-dbgcap.c:832
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184c6b0)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_do_dbc_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e520)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff8191e520-ffffffff8191e65b: xhci_do_dbc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_do_dbc_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925b90)
Location: drivers/usb/host/xhci-dbgcap.c:927
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81925b90-ffffffff81925cda: xhci_do_dbc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_do_dbc_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909280)
Location: drivers/usb/host/xhci-dbgcap.c:927
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81909280-ffffffff819093cc: xhci_do_dbc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_do_dbc_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9b00)
Location: drivers/usb/host/xhci-dbgcap.c:927
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff819a9b00-ffffffff819a9c4c: xhci_do_dbc_init (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8bd94)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (c0b5eb84)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (c000000000b67d8c)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0a26)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9c00)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81841530)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185ba90)
Location: drivers/usb/host/xhci-dbgcap.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
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
</ul>
