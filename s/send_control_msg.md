# Function: <code>send_control_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81517c37)
Location: drivers/char/virtio_console.c:589
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81569fc0)
Location: drivers/char/virtio_console.c:596
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81569fc0-ffffffff81569fee: send_control_msg.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81596700)
Location: drivers/char/virtio_console.c:595
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81596700-ffffffff8159672e: send_control_msg.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815aa4e0)
Location: drivers/char/virtio_console.c:595
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff815aa4e0-ffffffff815aa50e: send_control_msg.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81610e50)
Location: drivers/char/virtio_console.c:592
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81610e50-ffffffff81610e7e: send_control_msg.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164adb0)
Location: drivers/char/virtio_console.c:591
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff8164adb0-ffffffff8164adde: send_control_msg.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81668b90)
Location: drivers/char/virtio_console.c:591
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81668b90-ffffffff81668bbe: send_control_msg.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169e4e0)
Location: drivers/char/virtio_console.c:578
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff8169e4e0-ffffffff8169e50e: send_control_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c1510)
Location: drivers/char/virtio_console.c:578
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff816c1510-ffffffff816c153e: send_control_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81776bba)
Location: drivers/char/virtio_console.c:578
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff817918ea)
Location: drivers/char/virtio_console.c:578
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81773e5a)
Location: drivers/char/virtio_console.c:578
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff817fa22e)
Location: drivers/char/virtio_console.c:578
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8193977e)
Location: drivers/char/virtio_console.c:579
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81a9991e)
Location: drivers/char/virtio_console.c:571
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81ae518e)
Location: drivers/char/virtio_console.c:572
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81b3855e)
Location: drivers/char/virtio_console.c:569
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b3048)
Location: drivers/char/virtio_console.c:578
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffff8000108b3048-ffff8000108b30ac: send_control_msg.isra.0 (STB_LOCAL)
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
In drivers/char/virtio_console.c (c09b0204)
Location: drivers/char/virtio_console.c:578
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t send_control_msg(struct port *port, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094c990)
Location: drivers/char/virtio_console.c:578
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
c00000000094c990-c00000000094ca08: send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t send_control_msg(struct port *port, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe00056615a)
Location: drivers/char/virtio_console.c:578
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffe00056615a-ffffffe0005661a8: send_control_msg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81686f60)
Location: drivers/char/virtio_console.c:578
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81686f60-ffffffff81686f8e: send_control_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81664b60)
Location: drivers/char/virtio_console.c:578
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81664b60-ffffffff81664b8e: send_control_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b52b0)
Location: drivers/char/virtio_console.c:578
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff816b52b0-ffffffff816b52de: send_control_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816cfab0)
Location: drivers/char/virtio_console.c:578
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff816cfab0-ffffffff816cfade: send_control_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
