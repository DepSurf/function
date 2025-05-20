# Function: <code>calculate_max_exit_latency</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164a610)
Location: drivers/usb/host/xhci.c:4617
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8164a610-ffffffff8164a6d8: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ab080)
Location: drivers/usb/host/xhci.c:4599
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816ab080-ffffffff816ab142: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816d91a0)
Location: drivers/usb/host/xhci.c:4592
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816d91a0-ffffffff816d9262: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ed660)
Location: drivers/usb/host/xhci.c:4542
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816ed660-ffffffff816ed732: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81759e50)
Location: drivers/usb/host/xhci.c:4549
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81759e50-ffffffff81759f22: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179a480)
Location: drivers/usb/host/xhci.c:4734
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8179a480-ffffffff8179a573: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c0810)
Location: drivers/usb/host/xhci.c:4766
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817c0810-ffffffff817c0903: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4811
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81800260-ffffffff81800300: calculate_max_exit_latency (STB_LOCAL)
ffffffff8180797f-ffffffff8180799f: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81830ff0-ffffffff81831090: calculate_max_exit_latency (STB_LOCAL)
ffffffff8183883c-ffffffff8183885c: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4894
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff819034a0-ffffffff81903540: calculate_max_exit_latency (STB_LOCAL)
ffffffff8190afac-ffffffff8190afcc: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5032
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8190ba10-ffffffff8190bab0: calculate_max_exit_latency (STB_LOCAL)
ffffffff81c209d9-ffffffff81c209f9: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4959
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff818ef0f0-ffffffff818ef18f: calculate_max_exit_latency (STB_LOCAL)
ffffffff81c12a5c-ffffffff81c12a7d: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4979
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8198b9b0-ffffffff8198ba4f: calculate_max_exit_latency (STB_LOCAL)
ffffffff81d1f681-ffffffff81d1f6a2: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5000
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81ae7b20-ffffffff81ae7bd4: calculate_max_exit_latency (STB_LOCAL)
ffffffff81eeb144-ffffffff81eeb17a: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c73a60)
Location: drivers/usb/host/xhci.c:5004
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81c73a60-ffffffff81c73b46: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdaff0)
Location: drivers/usb/host/xhci.c:4838
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81cdaff0-ffffffff81cdb0d6: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d90020)
Location: drivers/usb/host/xhci.c:4898
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81d90020-ffffffff81d90106: calculate_max_exit_latency (STB_LOCAL)
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
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a6d4c0)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffff800010a6d4c0-ffff800010a6d5b4: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b41aec)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
c0b41aec-c0b41c04: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b41410)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
c000000000b41410-c000000000b4156c: calculate_max_exit_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe0006868e8)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffe0006868e8-ffffffe0006869c8: calculate_max_exit_latency (STB_LOCAL)
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
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817e93d0-ffffffff817e9470: calculate_max_exit_latency (STB_LOCAL)
ffffffff817f0bec-ffffffff817f0c0c: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817ae4e0-ffffffff817ae580: calculate_max_exit_latency (STB_LOCAL)
ffffffff817b5d82-ffffffff817b5da2: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81825e70-ffffffff81825f10: calculate_max_exit_latency (STB_LOCAL)
ffffffff8182d6bc-ffffffff8182d6dc: calculate_max_exit_latency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int calculate_max_exit_latency(struct usb_device *udev, enum usb3_link_state state_changed, u16 hub_encoded_timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8183fd50-ffffffff8183fdf0: calculate_max_exit_latency (STB_LOCAL)
ffffffff818477a5-ffffffff818477c5: calculate_max_exit_latency.cold (STB_LOCAL)
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
