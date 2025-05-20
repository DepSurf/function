# Function: <code>queue_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81657230)
Location: drivers/usb/host/xhci-ring.c:3994
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
```
**Symbols:**

```
ffffffff81657230-ffffffff8165740d: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816b7990)
Location: drivers/usb/host/xhci-ring.c:3892
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816b7990-ffffffff816b7b64: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e5c40)
Location: drivers/usb/host/xhci-ring.c:3792
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816e5c40-ffffffff816e5e18: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fa540)
Location: drivers/usb/host/xhci-ring.c:3892
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816fa540-ffffffff816fa772: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81766f80)
Location: drivers/usb/host/xhci-ring.c:3896
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81766f80-ffffffff817671b5: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a7ca0)
Location: drivers/usb/host/xhci-ring.c:3815
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817a7ca0-ffffffff817a7ea8: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817cdb70)
Location: drivers/usb/host/xhci-ring.c:3879
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817cdb70-ffffffff817cdd78: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3945
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8180e270-ffffffff8180e434: queue_command (STB_LOCAL)
ffffffff8181308a-ffffffff818130d9: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8183f360-ffffffff8183f524: queue_command (STB_LOCAL)
ffffffff818442b4-ffffffff81844303: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4020
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
```
**Symbols:**

```
ffffffff819117c0-ffffffff81911934: queue_command (STB_LOCAL)
ffffffff81916d10-ffffffff81916d5f: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
```
**Symbols:**

```
ffffffff819191d0-ffffffff81919344: queue_command (STB_LOCAL)
ffffffff81c21c52-ffffffff81c21ca1: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4243
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
```
**Symbols:**

```
ffffffff818fc020-ffffffff818fc194: queue_command (STB_LOCAL)
ffffffff81c13c43-ffffffff81c13c92: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4313
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff8199af10-ffffffff8199b081: queue_command (STB_LOCAL)
ffffffff81d20ad7-ffffffff81d20b26: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4248
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81af8560-ffffffff81af86c6: queue_command (STB_LOCAL)
ffffffff81eec65c-ffffffff81eec6a8: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c86480)
Location: drivers/usb/host/xhci-ring.c:4255
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81c86480-ffffffff81c86628: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ced2b0)
Location: drivers/usb/host/xhci-ring.c:4273
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81ced2b0-ffffffff81ced458: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da3070)
Location: drivers/usb/host/xhci-ring.c:4316
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_configure_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81da3070-ffffffff81da321f: queue_command (STB_LOCAL)
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
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7ceb8)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffff800010a7ceb8-ffff800010a7d0bc: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b510a8)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c0b510a8-c0b512c0: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b55780)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c000000000b55780-c000000000b559fc: queue_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000694a04)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffe000694a04-ffffffe000694bcc: queue_command (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817f7710-ffffffff817f78d4: queue_command (STB_LOCAL)
ffffffff817fc664-ffffffff817fc6b3: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817bc8b0-ffffffff817bca74: queue_command (STB_LOCAL)
ffffffff817c1804-ffffffff817c1853: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff818341e0-ffffffff818343a4: queue_command (STB_LOCAL)
ffffffff81839134-ffffffff81839183: queue_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int queue_command(struct xhci_hcd *xhci, struct xhci_command *cmd, u32 field1, u32 field2, u32 field3, u32 field4, bool command_must_succeed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3974
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_stop_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_queue_evaluate_context
  - drivers/usb/host/xhci-ring.c:xhci_queue_reset_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_vendor_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_address_device
  - drivers/usb/host/xhci-ring.c:xhci_queue_slot_control
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8184e4d0-ffffffff8184e6ad: queue_command (STB_LOCAL)
ffffffff81853587-ffffffff818535d6: queue_command.cold (STB_LOCAL)
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
