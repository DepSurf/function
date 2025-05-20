# Function: <code>hub_port_logical_disconnect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81605940)
Location: drivers/usb/core/hub.c:986
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81605940-ffffffff816059df: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816656f0)
Location: drivers/usb/core/hub.c:988
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff816656f0-ffffffff81665774: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81693170)
Location: drivers/usb/core/hub.c:909
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff81693170-ffffffff816931f4: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a8800)
Location: drivers/usb/core/hub.c:918
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff816a8800-ffffffff816a8884: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81713c00)
Location: drivers/usb/core/hub.c:918
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff81713c00-ffffffff81713c84: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81752970)
Location: drivers/usb/core/hub.c:926
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff81752970-ffffffff817529f4: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81776df0)
Location: drivers/usb/core/hub.c:927
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff81776df0-ffffffff81776e74: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b4e90)
Location: drivers/usb/core/hub.c:954
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff817b4e90-ffffffff817b4f18: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e55c0)
Location: drivers/usb/core/hub.c:956
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff817e55c0-ffffffff817e5648: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b4730)
Location: drivers/usb/core/hub.c:958
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff818b4730-ffffffff818b47af: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c3090)
Location: drivers/usb/core/hub.c:958
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff818c3090-ffffffff818c310f: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a6160)
Location: drivers/usb/core/hub.c:965
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff818a6160-ffffffff818a61df: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193afc0)
Location: drivers/usb/core/hub.c:965
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff8193afc0-ffffffff8193b03c: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a92bc0)
Location: drivers/usb/core/hub.c:965
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff81a92bc0-ffffffff81a92c54: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c14d90)
Location: drivers/usb/core/hub.c:969
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff81c14d90-ffffffff81c14dfc: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7bb90)
Location: drivers/usb/core/hub.c:969
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff81c7bb90-ffffffff81c7bbfc: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d307e0)
Location: drivers/usb/core/hub.c:989
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff81d307e0-ffffffff81d3084c: hub_port_logical_disconnect (STB_LOCAL)
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
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a143f0)
Location: drivers/usb/core/hub.c:956
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffff800010a143f0-ffff800010a144ac: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aec4a4)
Location: drivers/usb/core/hub.c:956
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
c0aec4a4-c0aec538: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acc210)
Location: drivers/usb/core/hub.c:956
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
c000000000acc210-c000000000acc30c: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe0006394ba)
Location: drivers/usb/core/hub.c:956
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffe0006394ba-ffffffe000639574: hub_port_logical_disconnect (STB_LOCAL)
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
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179d9a0)
Location: drivers/usb/core/hub.c:956
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff8179d9a0-ffffffff8179da28: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178f620)
Location: drivers/usb/core/hub.c:956
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff8178f620-ffffffff8178f6a8: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817da440)
Location: drivers/usb/core/hub.c:956
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff817da440-ffffffff817da4c8: hub_port_logical_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hub_port_logical_disconnect(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f46d0)
Location: drivers/usb/core/hub.c:956
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_remove_device
```
**Symbols:**

```
ffffffff817f46d0-ffffffff817f4758: hub_port_logical_disconnect (STB_LOCAL)
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
