# Function: <code>ncsi_xmit_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff8188c300)
Location: net/ncsi/ncsi-cmd.c:306
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff8188c300-ffffffff8188c50b: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff818c04b0)
Location: net/ncsi/ncsi-cmd.c:306
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff818c04b0-ffffffff818c06ba: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff818e6e20)
Location: net/ncsi/ncsi-cmd.c:294
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff818e6e20-ffffffff818e7032: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff8196c2d0)
Location: net/ncsi/ncsi-cmd.c:294
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff8196c2d0-ffffffff8196c4f1: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff819c5d60)
Location: net/ncsi/ncsi-cmd.c:294
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff819c5d60-ffffffff819c5fb4: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff819fd480)
Location: net/ncsi/ncsi-cmd.c:314
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff819fd480-ffffffff819fd71a: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81a6c710)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81a6c710-ffffffff81a6c977: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81aa30d0)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81aa30d0-ffffffff81aa3337: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81b9ebf0)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81b9ebf0-ffffffff81b9edfe: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81bae5f0)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81bae5f0-ffffffff81bae7fe: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81b9d670)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81b9d670-ffffffff81b9d922: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81c6abd0)
Location: net/ncsi/ncsi-cmd.c:318
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81c6abd0-ffffffff81c6af03: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-cmd.c (0)
Location: net/ncsi/ncsi-cmd.c:318
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81f0ed23-ffffffff81f0ed45: ncsi_xmit_cmd.cold (STB_LOCAL)
ffffffff81e0e330-ffffffff81e0e640: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81fe4770)
Location: net/ncsi/ncsi-cmd.c:319
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81fe4770-ffffffff81fe4ac0: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff82060a80)
Location: net/ncsi/ncsi-cmd.c:319
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff82060a80-ffffffff82060dd0: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff821339a0)
Location: net/ncsi/ncsi-cmd.c:320
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff821339a0-ffffffff82133ced: ncsi_xmit_cmd (STB_GLOBAL)
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
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffff800010d74b90)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffff800010d74b90-ffff800010d74e0c: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (c0e71650)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
c0e71650-c0e71898: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (c000000000eb4480)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
c000000000eb4480-c000000000eb4798: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4bd0)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffe0008a4bd0-ffffffe0008a4e10: ncsi_xmit_cmd (STB_GLOBAL)
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
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81a42460)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81a42460-ffffffff81a426c7: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff819ff050)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff819ff050-ffffffff819ff2b7: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81aae310)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81aae310-ffffffff81aae577: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ncsi_xmit_cmd(struct ncsi_cmd_arg *nca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-cmd.c (ffffffff81aba6c0)
Location: net/ncsi/ncsi-cmd.c:310
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81aba6c0-ffffffff81aba927: ncsi_xmit_cmd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
