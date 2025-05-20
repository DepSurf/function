# Function: <code>genl_unregister_family</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int genl_unregister_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81750bd0)
Location: net/netlink/genetlink.c:435
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_exit
```
**Symbols:**

```
ffffffff81750bd0-ffffffff81750e13: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int genl_unregister_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817bcd10)
Location: net/netlink/genetlink.c:435
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_exit
```
**Symbols:**

```
ffffffff817bcd10-ffffffff817bcf5b: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817ec5e0)
Location: net/netlink/genetlink.c:401
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_exit
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
```
**Symbols:**

```
ffffffff817ec5e0-ffffffff817ec7e3: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8180c480)
Location: net/netlink/genetlink.c:401
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_exit
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
```
**Symbols:**

```
ffffffff8180c480-ffffffff8180c658: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8188b460)
Location: net/netlink/genetlink.c:402
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_exit
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
```
**Symbols:**

```
ffffffff8188b460-ffffffff8188b638: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818dea30)
Location: net/netlink/genetlink.c:403
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_exit
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff818dea30-ffffffff818debfd: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8190b3f0)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_exit
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff8190b3f0-ffffffff8190b5bd: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8196c1c0)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff8196c1c0-ffffffff8196c38b: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819a2b70)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff819a2b70-ffffffff819a2d3b: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a7d140)
Location: net/netlink/genetlink.c:391
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff81a7d140-ffffffff81a7d260: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a866f0)
Location: net/netlink/genetlink.c:461
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
```
**Symbols:**

```
ffffffff81a866f0-ffffffff81a86810: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a6f850)
Location: net/netlink/genetlink.c:461
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
```
**Symbols:**

```
ffffffff81a6f850-ffffffff81a6fa1b: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81b28ed0)
Location: net/netlink/genetlink.c:453
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
```
**Symbols:**

```
ffffffff81b28ed0-ffffffff81b2909b: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81cb1f80)
Location: net/netlink/genetlink.c:453
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
```
**Symbols:**

```
ffffffff81cb1f80-ffffffff81cb218e: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e70180)
Location: net/netlink/genetlink.c:698
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
```
**Symbols:**

```
ffffffff81e70180-ffffffff81e70390: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ecc290)
Location: net/netlink/genetlink.c:698
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_netlink_exit
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
  - net/handshake/netlink.c:handshake_exit
  - net/handshake/netlink.c:handshake_init
```
**Symbols:**

```
ffffffff81ecc290-ffffffff81ecc4a0: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8f7b0)
Location: net/netlink/genetlink.c:853
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_netlink_exit
  - drivers/dpll/dpll_core.c:dpll_exit
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
  - net/devlink/core.c:devlink_init
  - net/handshake/netlink.c:handshake_exit
  - net/handshake/netlink.c:handshake_init
```
**Symbols:**

```
ffffffff81f8f7b0-ffffffff81f8f9dc: genl_unregister_family (STB_GLOBAL)
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
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffff800010c52480)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffff800010c52480-ffff800010c52680: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c0d6155c)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
c0d6155c-c0d61750: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c000000000d50a40)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:exit_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
c000000000d50a40-c000000000d50d10: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffe0007bcea4)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffe0007bcea4-ffffffe0007bd09a: genl_unregister_family (STB_GLOBAL)
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
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819429e0)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff819429e0-ffffffff81942bab: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818fc4d0)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff818fc4d0-ffffffff818fc69b: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81993b70)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff81993b70-ffffffff81993d3b: genl_unregister_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int genl_unregister_family(const struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819b6670)
Location: net/netlink/genetlink.c:404
Inline: False
Direct callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
```
**Symbols:**

```
ffffffff819b6670-ffffffff819b6840: genl_unregister_family (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct genl_family *family</code> ➡️ <code>const struct genl_family *family</code>
</li>
</ul>
</details>
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
