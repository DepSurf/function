# Function: <code>ohci_root_hub_state_changes</code>

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
In drivers/usb/host/ohci-hcd.c (ffffffff816433cd)
Location: drivers/usb/host/ohci-hub.c:341
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816a3f2c)
Location: drivers/usb/host/ohci-hub.c:341
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816d202c)
Location: drivers/usb/host/ohci-hub.c:341
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816e661c)
Location: drivers/usb/host/ohci-hub.c:341
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81752e4c)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
In drivers/usb/host/ohci-hcd.c (ffffffff817935bb)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
In drivers/usb/host/ohci-hcd.c (ffffffff817b9b8b)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
In drivers/usb/host/ohci-hcd.c (ffffffff817f8679)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
In drivers/usb/host/ohci-hcd.c (ffffffff818294d9)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ohci_root_hub_state_changes(struct ohci_hcd *ohci, int changed, int any_connected, int rhsc_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818fbe80)
Location: drivers/usb/host/ohci-hub.c:344
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
**Symbols:**

```
ffffffff818fbe80-ffffffff818fc017: ohci_root_hub_state_changes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ohci_root_hub_state_changes(struct ohci_hcd *ohci, int changed, int any_connected, int rhsc_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff819049e0)
Location: drivers/usb/host/ohci-hub.c:344
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
**Symbols:**

```
ffffffff819049e0-ffffffff81904b77: ohci_root_hub_state_changes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ohci_root_hub_state_changes(struct ohci_hcd *ohci, int changed, int any_connected, int rhsc_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818e8190)
Location: drivers/usb/host/ohci-hub.c:344
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
**Symbols:**

```
ffffffff818e8190-ffffffff818e8324: ohci_root_hub_state_changes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ohci_root_hub_state_changes(struct ohci_hcd *ohci, int changed, int any_connected, int rhsc_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81984580)
Location: drivers/usb/host/ohci-hub.c:344
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
**Symbols:**

```
ffffffff81984580-ffffffff81984714: ohci_root_hub_state_changes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ohci_root_hub_state_changes(struct ohci_hcd *ohci, int changed, int any_connected, int rhsc_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81adfae0)
Location: drivers/usb/host/ohci-hub.c:347
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
**Symbols:**

```
ffffffff81adfae0-ffffffff81adfc91: ohci_root_hub_state_changes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ohci_root_hub_state_changes(struct ohci_hcd *ohci, int changed, int any_connected, int rhsc_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81c6b0f0)
Location: drivers/usb/host/ohci-hub.c:347
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
**Symbols:**

```
ffffffff81c6b0f0-ffffffff81c6b2a1: ohci_root_hub_state_changes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ohci_root_hub_state_changes(struct ohci_hcd *ohci, int changed, int any_connected, int rhsc_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd24e0)
Location: drivers/usb/host/ohci-hub.c:347
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
**Symbols:**

```
ffffffff81cd24e0-ffffffff81cd2692: ohci_root_hub_state_changes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ohci_root_hub_state_changes(struct ohci_hcd *ohci, int changed, int any_connected, int rhsc_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81d874a0)
Location: drivers/usb/host/ohci-hub.c:347
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
**Symbols:**

```
ffffffff81d874a0-ffffffff81d87654: ohci_root_hub_state_changes (STB_LOCAL)
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
In drivers/usb/host/ohci-hcd.c (ffff800010a65904)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
In drivers/usb/host/ohci-hcd.c (c0b36840)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
In drivers/usb/host/ohci-hcd.c (c000000000b352b0)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
In drivers/usb/host/ohci-hcd.c (ffffffe00067fcc8)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817e18b9)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8181e359)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
In drivers/usb/host/ohci-hcd.c (ffffffff81838049)
Location: drivers/usb/host/ohci-hub.c:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
