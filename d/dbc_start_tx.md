# Function: <code>dbc_start_tx</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81774540)
Location: drivers/usb/host/xhci-dbgtty.c:29
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff81774540-ffffffff8177467b: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b4a20)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff817b4a20-ffffffff817b4b4f: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817daf70)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff817daf70-ffffffff817db09f: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181b950)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff8181b950-ffffffff8181bab7: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184cd20)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff8184cd20-ffffffff8184ce87: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8191f970)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff8191f970-ffffffff8191facf: dbc_start_tx.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81927090)
Location: drivers/usb/host/xhci-dbgtty.c:40
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff81927090-ffffffff819271e3: dbc_start_tx.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190a690)
Location: drivers/usb/host/xhci-dbgtty.c:40
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff8190a690-ffffffff8190a7b8: dbc_start_tx.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819aad40)
Location: drivers/usb/host/xhci-dbgtty.c:40
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff819aad40-ffffffff819aae68: dbc_start_tx.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b09310)
Location: drivers/usb/host/xhci-dbgtty.c:40
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff81b09310-ffffffff81b09448: dbc_start_tx.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c99070)
Location: drivers/usb/host/xhci-dbgtty.c:40
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff81c99070-ffffffff81c991a8: dbc_start_tx.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00420)
Location: drivers/usb/host/xhci-dbgtty.c:40
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff81d00420-ffffffff81d00558: dbc_start_tx.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db5f10)
Location: drivers/usb/host/xhci-dbgtty.c:40
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff81db5f10-ffffffff81db6048: dbc_start_tx.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c4f8)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffff800010a8c4f8-ffff800010a8c664: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c0b5f034)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
c0b5f034-c0b5f14c: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c000000000b684e0)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
c000000000b684e0-c000000000b686d4: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a0f54)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffe0006a0f54-ffffffe0006a1098: dbc_start_tx (STB_LOCAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca270)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff817ca270-ffffffff817ca3d7: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81841ba0)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff81841ba0-ffffffff81841d07: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dbc_start_tx(struct dbc_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c240)
Location: drivers/usb/host/xhci-dbgtty.c:30
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
```
**Symbols:**

```
ffffffff8185c240-ffffffff8185c3a5: dbc_start_tx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
