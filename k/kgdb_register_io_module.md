# Function: <code>kgdb_register_io_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81130610)
Location: kernel/debug/debug_core.c:982
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81130610-ffffffff8113075c: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81138920)
Location: kernel/debug/debug_core.c:982
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81138920-ffffffff81138a6c: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811426b0)
Location: kernel/debug/debug_core.c:982
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff811426b0-ffffffff811427fc: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81143ee0)
Location: kernel/debug/debug_core.c:983
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81143ee0-ffffffff8114402d: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81150ba0)
Location: kernel/debug/debug_core.c:983
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81150ba0-ffffffff81150cf0: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:983
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff8115f930-ffffffff8115f952: kgdb_register_io_module.cold.24 (STB_LOCAL)
ffffffff8115f710-ffffffff8115f843: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116c504)
Location: kernel/debug/debug_core.c:1046
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff8116c6a0-ffffffff8116c6c2: kgdb_register_io_module.cold.24 (STB_LOCAL)
ffffffff8116c480-ffffffff8116c5b3: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81179338)
Location: kernel/debug/debug_core.c:1046
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff811794dc-ffffffff811794ff: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff811792b0-ffffffff811793e8: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811851d8)
Location: kernel/debug/debug_core.c:1034
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff8118536c-ffffffff8118538f: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff81185150-ffffffff81185271: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1090
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff811994d0-ffffffff8119958b: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff811992c0-ffffffff8119937d: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1129
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81be4bf6-ffffffff81be4cb1: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff811965f0-ffffffff811966ad: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1103
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81bd6a6a-ffffffff81bd6b25: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff811975a0-ffffffff8119765d: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1101
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81cb3a85-ffffffff81cb3b5b: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff811c1310-ffffffff811c13cd: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1125
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81e648f1-ffffffff81e64a05: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff811f4920-ffffffff811f49c2: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1113
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff8205c85c-ffffffff8205c870: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff8123b8a0-ffffffff8123ba74: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1113
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff820db1b1-ffffffff820db1c5: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff812528b0-ffffffff81252a84: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:1116
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff821b6eec-ffffffff821b6f00: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff8126c720-ffffffff8126c8f4: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101fad88)
Location: kernel/debug/debug_core.c:1034
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffff8000101fad88-ffff8000101faf00: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c043ae90)
Location: kernel/debug/debug_core.c:1034
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
c043ae90-c043b008: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000000272900)
Location: kernel/debug/debug_core.c:1034
Inline: False
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
c000000000272900-c000000000272b5c: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117d7f8)
Location: kernel/debug/debug_core.c:1034
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff8117d98c-ffffffff8117d9af: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff8117d770-ffffffff8117d891: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81170948)
Location: kernel/debug/debug_core.c:1034
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff81170adc-ffffffff81170aff: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff811708c0-ffffffff811709e1: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117b5c8)
Location: kernel/debug/debug_core.c:1034
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff8117b75c-ffffffff8117b77f: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff8117b540-ffffffff8117b661: kgdb_register_io_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_register_io_module(struct kgdb_io *new_dbg_io_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81188eea)
Location: kernel/debug/debug_core.c:1034
Inline: True
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
```
**Symbols:**

```
ffffffff8118907c-ffffffff8118909f: kgdb_register_io_module.cold (STB_LOCAL)
ffffffff81188e60-ffffffff81188f83: kgdb_register_io_module (STB_GLOBAL)
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
