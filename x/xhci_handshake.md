# Function: <code>xhci_handshake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164ca0f)
Location: drivers/usb/host/xhci.c:63
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff8164cd40-ffffffff8164cda7: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ae726)
Location: drivers/usb/host/xhci.c:64
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff816ad670-ffffffff816ad6d7: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dc8c6)
Location: drivers/usb/host/xhci.c:64
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_halt
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff816db950-ffffffff816db9b7: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f0e0b)
Location: drivers/usb/host/xhci.c:64
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff816f0000-ffffffff816f0067: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175cfe3)
Location: drivers/usb/host/xhci.c:54
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff8175c1c0-ffffffff8175c227: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179da09)
Location: drivers/usb/host/xhci.c:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff8179cb90-ffffffff8179cbf7: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c3e33)
Location: drivers/usb/host/xhci.c:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817c2f70-ffffffff817c2fd7: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81802740)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff81802740-ffffffff818027df: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81833640)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff81833640-ffffffff818336df: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff819066d0)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_start
```
**Symbols:**

```
ffffffff819066d0-ffffffff8190676f: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190ee60)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff8190ee60-ffffffff8190eeff: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f23a0)
Location: drivers/usb/host/xhci.c:68
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff818f23a0-ffffffff818f2448: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198f5f0)
Location: drivers/usb/host/xhci.c:68
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff8198f5f0-ffffffff8198f698: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, u64 timeout_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81aebaa0)
Location: drivers/usb/host/xhci.c:68
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff81aebaa0-ffffffff81aebb72: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, u64 timeout_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c78090)
Location: drivers/usb/host/xhci.c:68
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff81c78090-ffffffff81c78162: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, u64 timeout_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdf190)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff81cdf190-ffffffff81cdf24d: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, u64 timeout_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d94110)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff81d94110-ffffffff81d941cd: xhci_handshake (STB_GLOBAL)
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
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a70600)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffff800010a70600-ffff800010a706ec: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b44568)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
c0b44568-c0b4465c: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b44c40)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
c000000000b44c40-c000000000b44dc4: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000688dbc)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffe000688dbc-ffffffe000688e84: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817eba20)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
**Symbols:**

```
ffffffff817eba20-ffffffff817ebabf: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b0b30)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817b0b30-ffffffff817b0bcf: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818284c0)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff818284c0-ffffffff8182855f: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_handshake(void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81842490)
Location: drivers/usb/host/xhci.c:69
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff81842490-ffffffff8184252f: xhci_handshake (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 timeout_us</code>
</li>
<li>
<b>Param removed. </b>
<code>int usec</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
