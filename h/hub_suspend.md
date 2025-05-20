# Function: <code>hub_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816081b0)
Location: drivers/usb/core/hub.c:3608
Inline: False
```
**Symbols:**

```
ffffffff816081b0-ffffffff81608419: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81667e70)
Location: drivers/usb/core/hub.c:3609
Inline: False
```
**Symbols:**

```
ffffffff81667e70-ffffffff816680e5: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81695b90)
Location: drivers/usb/core/hub.c:3535
Inline: False
```
**Symbols:**

```
ffffffff81695b90-ffffffff81695e05: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816aafd0)
Location: drivers/usb/core/hub.c:3554
Inline: False
```
**Symbols:**

```
ffffffff816aafd0-ffffffff816ab228: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81716420)
Location: drivers/usb/core/hub.c:3557
Inline: False
```
**Symbols:**

```
ffffffff81716420-ffffffff81716678: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81755240)
Location: drivers/usb/core/hub.c:3608
Inline: False
```
**Symbols:**

```
ffffffff81755240-ffffffff81755494: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81779770)
Location: drivers/usb/core/hub.c:3628
Inline: False
```
**Symbols:**

```
ffffffff81779770-ffffffff817799c4: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3672
Inline: False
```
**Symbols:**

```
ffffffff817b7620-ffffffff817b782b: hub_suspend (STB_LOCAL)
ffffffff817ba6b9-ffffffff817ba6f1: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
ffffffff817e7de0-ffffffff817e7feb: hub_suspend (STB_LOCAL)
ffffffff817eaf33-ffffffff817eaf6b: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3734
Inline: False
```
**Symbols:**

```
ffffffff818b72c0-ffffffff818b74fc: hub_suspend (STB_LOCAL)
ffffffff818ba5d3-ffffffff818ba60b: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3752
Inline: False
```
**Symbols:**

```
ffffffff818c5bd0-ffffffff818c5e0c: hub_suspend (STB_LOCAL)
ffffffff81c1b0f9-ffffffff81c1b131: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3828
Inline: False
```
**Symbols:**

```
ffffffff818a8eb0-ffffffff818a90ec: hub_suspend (STB_LOCAL)
ffffffff81c0cf67-ffffffff81c0cf9f: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3832
Inline: False
```
**Symbols:**

```
ffffffff8193ddc0-ffffffff8193dff9: hub_suspend (STB_LOCAL)
ffffffff81d13f14-ffffffff81d13f4c: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3838
Inline: False
```
**Symbols:**

```
ffffffff81a95dd0-ffffffff81a9601e: hub_suspend (STB_LOCAL)
ffffffff81edea92-ffffffff81edeac9: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c184c0)
Location: drivers/usb/core/hub.c:3853
Inline: False
```
**Symbols:**

```
ffffffff81c184c0-ffffffff81c1874d: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7f4a0)
Location: drivers/usb/core/hub.c:3873
Inline: False
```
**Symbols:**

```
ffffffff81c7f4a0-ffffffff81c7f72d: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d33e90)
Location: drivers/usb/core/hub.c:3875
Inline: False
```
**Symbols:**

```
ffffffff81d33e90-ffffffff81d3411d: hub_suspend (STB_LOCAL)
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
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a17030)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
ffff800010a17030-ffff800010a1725c: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aef100)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
c0aef100-c0aef354: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acfb60)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
c000000000acfb60-c000000000acfe4c: hub_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063bf22)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
ffffffe00063bf22-ffffffe00063c0de: hub_suspend (STB_LOCAL)
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
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
ffffffff817a01c0-ffffffff817a03cb: hub_suspend (STB_LOCAL)
ffffffff817a3313-ffffffff817a334b: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
ffffffff81791e30-ffffffff8179203b: hub_suspend (STB_LOCAL)
ffffffff81795153-ffffffff8179518b: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
ffffffff817dcc60-ffffffff817dce6b: hub_suspend (STB_LOCAL)
ffffffff817dfdb3-ffffffff817dfdeb: hub_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hub_suspend(struct usb_interface *intf, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3720
Inline: False
```
**Symbols:**

```
ffffffff817f6f30-ffffffff817f713b: hub_suspend (STB_LOCAL)
ffffffff817fa0a3-ffffffff817fa0db: hub_suspend.cold (STB_LOCAL)
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
