# Function: <code>hub_port_power_cycle</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817e7810-ffffffff817e78a2: hub_port_power_cycle (STB_LOCAL)
ffffffff817eaf07-ffffffff817eaf33: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2770
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818b6ee0-ffffffff818b6f70: hub_port_power_cycle (STB_LOCAL)
ffffffff818ba398-ffffffff818ba3c4: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2788
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818c57f0-ffffffff818c5880: hub_port_power_cycle (STB_LOCAL)
ffffffff81c1aebe-ffffffff81c1aeea: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2843
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818a8ad0-ffffffff818a8b5c: hub_port_power_cycle (STB_LOCAL)
ffffffff81c0cd2c-ffffffff81c0cd58: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2847
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff8193d9e0-ffffffff8193da6c: hub_port_power_cycle (STB_LOCAL)
ffffffff81d13cdc-ffffffff81d13d08: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2849
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81a95720-ffffffff81a957ce: hub_port_power_cycle (STB_LOCAL)
ffffffff81edea68-ffffffff81edea92: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a168b0)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffff800010a168b0-ffff800010a16978: hub_port_power_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeeb5c)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
c0aeeb5c-c0aeec0c: hub_port_power_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acf2c0)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
c000000000acf2c0-c000000000acf3bc: hub_port_power_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063b950)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffe00063b950-ffffffe00063ba16: hub_port_power_cycle (STB_LOCAL)
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
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff8179fbf0-ffffffff8179fc82: hub_port_power_cycle (STB_LOCAL)
ffffffff817a32e7-ffffffff817a3313: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81791870-ffffffff81791902: hub_port_power_cycle (STB_LOCAL)
ffffffff81795127-ffffffff81795153: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817dc690-ffffffff817dc722: hub_port_power_cycle (STB_LOCAL)
ffffffff817dfd87-ffffffff817dfdb3: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void hub_port_power_cycle(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2765
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817f6920-ffffffff817f69b2: hub_port_power_cycle (STB_LOCAL)
ffffffff817fa077-ffffffff817fa0a3: hub_port_power_cycle.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
