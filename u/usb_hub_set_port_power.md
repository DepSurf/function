# Function: <code>usb_hub_set_port_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81607c10)
Location: drivers/usb/core/hub.c:770
Inline: False
Direct callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
**Symbols:**

```
ffffffff81607c10-ffffffff81607c5d: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81667920)
Location: drivers/usb/core/hub.c:772
Inline: False
Direct callers:
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff81667920-ffffffff8166796d: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81695640)
Location: drivers/usb/core/hub.c:775
Inline: False
Direct callers:
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff81695640-ffffffff81695687: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816aaa90)
Location: drivers/usb/core/hub.c:784
Inline: False
Direct callers:
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff816aaa90-ffffffff816aaad7: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81715ed0)
Location: drivers/usb/core/hub.c:784
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff81715ed0-ffffffff81715f17: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81754cf0)
Location: drivers/usb/core/hub.c:792
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff81754cf0-ffffffff81754d37: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81779230)
Location: drivers/usb/core/hub.c:793
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff81779230-ffffffff81779277: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b70a0)
Location: drivers/usb/core/hub.c:820
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff817b70a0-ffffffff817b70e7: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e77c0)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff817e77c0-ffffffff817e780b: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b6e40)
Location: drivers/usb/core/hub.c:824
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff818b6e40-ffffffff818b6eda: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c5750)
Location: drivers/usb/core/hub.c:824
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff818c5750-ffffffff818c57ea: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a8a30)
Location: drivers/usb/core/hub.c:831
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff818a8a30-ffffffff818a8ac9: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193d940)
Location: drivers/usb/core/hub.c:831
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff8193d940-ffffffff8193d9d9: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a95670)
Location: drivers/usb/core/hub.c:831
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff81a95670-ffffffff81a95718: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c17da0)
Location: drivers/usb/core/hub.c:835
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:disable_store
```
**Symbols:**

```
ffffffff81c17da0-ffffffff81c17e45: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7eda0)
Location: drivers/usb/core/hub.c:835
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:disable_store
```
**Symbols:**

```
ffffffff81c7eda0-ffffffff81c7ee5a: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_device *hdev, struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d33770)
Location: drivers/usb/core/hub.c:855
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:disable_store
```
**Symbols:**

```
ffffffff81d33770-ffffffff81d3382a: usb_hub_set_port_power (STB_GLOBAL)
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
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a167e0)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffff800010a167e0-ffff800010a168ac: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeeaf0)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
c0aeeaf0-c0aeeb5c: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acf1c0)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
c000000000acf1c0-c000000000acf2bc: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063b8a6)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffe00063b8a6-ffffffe00063b950: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179fba0)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff8179fba0-ffffffff8179fbeb: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81791820)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff81791820-ffffffff8179186b: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817dc640)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff817dc640-ffffffff817dc68b: usb_hub_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int usb_hub_set_port_power(struct usb_hub *hub, int port1, bool set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f68d0)
Location: drivers/usb/core/hub.c:822
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffff817f68d0-ffffffff817f691b: usb_hub_set_port_power (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct usb_device *hdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>hdev, hub, port1, set</code> ➡️ <code>hub, port1, set</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct usb_device *hdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>hub, port1, set</code> ➡️ <code>hdev, hub, port1, set</code>
</li>
</ul>
</details>
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
