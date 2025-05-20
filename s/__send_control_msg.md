# Function: <code>__send_control_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815171f0)
Location: drivers/char/virtio_console.c:559
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff815171f0-ffffffff815172cd: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81569ea0)
Location: drivers/char/virtio_console.c:565
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81569ea0-ffffffff81569f81: __send_control_msg.part.27 (STB_LOCAL)
ffffffff81569f90-ffffffff81569fb7: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815965e0)
Location: drivers/char/virtio_console.c:564
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff815965e0-ffffffff815966c1: __send_control_msg.part.29 (STB_LOCAL)
ffffffff815966d0-ffffffff815966f7: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815aa3c0)
Location: drivers/char/virtio_console.c:564
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff815aa3c0-ffffffff815aa4a1: __send_control_msg.part.27 (STB_LOCAL)
ffffffff815aa4b0-ffffffff815aa4d7: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81610d30)
Location: drivers/char/virtio_console.c:561
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81610d30-ffffffff81610e11: __send_control_msg.part.27 (STB_LOCAL)
ffffffff81610e20-ffffffff81610e47: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164ac90)
Location: drivers/char/virtio_console.c:560
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff8164ac90-ffffffff8164ad71: __send_control_msg.part.29 (STB_LOCAL)
ffffffff8164ad80-ffffffff8164ada7: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81668a70)
Location: drivers/char/virtio_console.c:560
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81668a70-ffffffff81668b51: __send_control_msg.part.26 (STB_LOCAL)
ffffffff81668b60-ffffffff81668b87: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169e3c0)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff8169e3c0-ffffffff8169e4ab: __send_control_msg.part.0 (STB_LOCAL)
ffffffff8169e4b0-ffffffff8169e4d7: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c13f0)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff816c13f0-ffffffff816c14db: __send_control_msg.part.0 (STB_LOCAL)
ffffffff816c14e0-ffffffff816c1507: __send_control_msg (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81776bcd)
Location: drivers/char/virtio_console.c:547
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81775b30-ffffffff81775c1b: __send_control_msg.part.0 (STB_LOCAL)
ffffffff81777b68-ffffffff81777b8b: __send_control_msg.isra.0 (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff817918fd)
Location: drivers/char/virtio_console.c:547
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81790860-ffffffff8179094b: __send_control_msg.part.0 (STB_LOCAL)
ffffffff81c0875b-ffffffff81c0877e: __send_control_msg.isra.0 (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81773990)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81773990-ffffffff81773a94: __send_control_msg.isra.0 (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff817f97d0)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff817f97d0-ffffffff817f98d4: __send_control_msg.isra.0 (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81936730)
Location: drivers/char/virtio_console.c:548
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81936730-ffffffff81936862: __send_control_msg.isra.0 (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81a96590)
Location: drivers/char/virtio_console.c:540
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81a96590-ffffffff81a966c2: __send_control_msg.isra.0 (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81ae1da0)
Location: drivers/char/virtio_console.c:541
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81ae1da0-ffffffff81ae1ed2: __send_control_msg.isra.0 (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81b35190)
Location: drivers/char/virtio_console.c:538
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
ffffffff81b35190-ffffffff81b352c2: __send_control_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b2ea0)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffff8000108b2ea0-ffff8000108b2fd0: __send_control_msg.part.0 (STB_LOCAL)
ffff8000108b2fd0-ffff8000108b3044: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ae444)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
**Symbols:**

```
c09ae444-c09ae594: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094c9ac)
Location: drivers/char/virtio_console.c:547
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:send_control_msg
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:send_control_msg
```
**Symbols:**

```
c00000000094c7a0-c00000000094c928: __send_control_msg.part.0 (STB_LOCAL)
c00000000094c930-c00000000094c984: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe00056617c)
Location: drivers/char/virtio_console.c:547
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:send_control_msg
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:send_control_msg
```
**Symbols:**

```
ffffffe000566014-ffffffe000566108: __send_control_msg.part.0 (STB_LOCAL)
ffffffe000566108-ffffffe00056615a: __send_control_msg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81686e40)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81686e40-ffffffff81686f2b: __send_control_msg.part.0 (STB_LOCAL)
ffffffff81686f30-ffffffff81686f57: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81664a40)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff81664a40-ffffffff81664b2b: __send_control_msg.part.0 (STB_LOCAL)
ffffffff81664b30-ffffffff81664b57: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b5190)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff816b5190-ffffffff816b527b: __send_control_msg.part.0 (STB_LOCAL)
ffffffff816b5280-ffffffff816b52a7: __send_control_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t __send_control_msg(struct ports_device *portdev, u32 port_id, unsigned int event, unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816cf990)
Location: drivers/char/virtio_console.c:547
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff816cf990-ffffffff816cfa79: __send_control_msg.part.0 (STB_LOCAL)
ffffffff816cfa80-ffffffff816cfaa7: __send_control_msg (STB_LOCAL)
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
