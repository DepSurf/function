# Function: <code>link_peers</code>

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
In drivers/usb/core/port.c (ffffffff8161efba)
Location: drivers/usb/core/port.c:191
Inline: True
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
In drivers/usb/core/port.c (ffffffff8167f95a)
Location: drivers/usb/core/port.c:272
Inline: True
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
In drivers/usb/core/port.c (ffffffff816ad69a)
Location: drivers/usb/core/port.c:272
Inline: True
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
In drivers/usb/core/port.c (ffffffff816c287a)
Location: drivers/usb/core/port.c:272
Inline: True
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
In drivers/usb/core/port.c (ffffffff8172e64a)
Location: drivers/usb/core/port.c:263
Inline: True
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
In drivers/usb/core/port.c (ffffffff8176d785)
Location: drivers/usb/core/port.c:296
Inline: True
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
In drivers/usb/core/port.c (ffffffff81791e05)
Location: drivers/usb/core/port.c:306
Inline: True
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
In drivers/usb/core/port.c (ffffffff817d05c5)
Location: drivers/usb/core/port.c:315
Inline: True
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
In drivers/usb/core/port.c (ffffffff81801495)
Location: drivers/usb/core/port.c:321
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int link_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818d1be0)
Location: drivers/usb/core/port.c:321
Inline: False
Direct callers:
  - drivers/usb/core/port.c:link_peers_report
```
**Symbols:**

```
ffffffff818d1be0-ffffffff818d1dad: link_peers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int link_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818dbfc0)
Location: drivers/usb/core/port.c:321
Inline: False
Direct callers:
  - drivers/usb/core/port.c:link_peers_report
```
**Symbols:**

```
ffffffff818dbfc0-ffffffff818dc18d: link_peers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int link_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818bf390)
Location: drivers/usb/core/port.c:321
Inline: False
Direct callers:
  - drivers/usb/core/port.c:link_peers_report
```
**Symbols:**

```
ffffffff818bf390-ffffffff818bf55d: link_peers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int link_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff819559f0)
Location: drivers/usb/core/port.c:321
Inline: False
Direct callers:
  - drivers/usb/core/port.c:link_peers_report
```
**Symbols:**

```
ffffffff819559f0-ffffffff81955bba: link_peers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int link_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81aaf6a0)
Location: drivers/usb/core/port.c:322
Inline: False
Direct callers:
  - drivers/usb/core/port.c:link_peers_report
```
**Symbols:**

```
ffffffff81aaf6a0-ffffffff81aaf88b: link_peers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int link_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81c37420)
Location: drivers/usb/core/port.c:433
Inline: False
Direct callers:
  - drivers/usb/core/port.c:link_peers_report
```
**Symbols:**

```
ffffffff81c37420-ffffffff81c37611: link_peers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int link_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81c9e760)
Location: drivers/usb/core/port.c:444
Inline: False
Direct callers:
  - drivers/usb/core/port.c:link_peers_report
```
**Symbols:**

```
ffffffff81c9e760-ffffffff81c9e94d: link_peers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int link_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81d53360)
Location: drivers/usb/core/port.c:444
Inline: False
Direct callers:
  - drivers/usb/core/port.c:link_peers_report
```
**Symbols:**

```
ffffffff81d53360-ffffffff81d5354d: link_peers (STB_LOCAL)
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
In drivers/usb/core/port.c (ffff800010a35838)
Location: drivers/usb/core/port.c:321
Inline: True
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
In drivers/usb/core/port.c (c0b08f8c)
Location: drivers/usb/core/port.c:321
Inline: True
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
In drivers/usb/core/port.c (c000000000af39b4)
Location: drivers/usb/core/port.c:321
Inline: True
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
In drivers/usb/core/port.c (ffffffe000653080)
Location: drivers/usb/core/port.c:321
Inline: True
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
In drivers/usb/core/port.c (ffffffff817b9875)
Location: drivers/usb/core/port.c:321
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff817ab2a5)
Location: drivers/usb/core/port.c:321
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff817f6315)
Location: drivers/usb/core/port.c:321
Inline: True
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
In drivers/usb/core/port.c (ffffffff81810555)
Location: drivers/usb/core/port.c:321
Inline: True
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
