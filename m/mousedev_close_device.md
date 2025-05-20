# Function: <code>mousedev_close_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8166ba30)
Location: drivers/input/mousedev.c:442
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mixdev_close_devices
  - drivers/input/mousedev.c:mousedev_disconnect
```
**Symbols:**

```
ffffffff8166ba30-ffffffff8166ba7f: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816cba80)
Location: drivers/input/mousedev.c:442
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff816cba80-ffffffff816cbacf: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816f9a30)
Location: drivers/input/mousedev.c:442
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff816f9a30-ffffffff816f9a7f: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8170f590)
Location: drivers/input/mousedev.c:442
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff8170f590-ffffffff8170f5df: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81780810)
Location: drivers/input/mousedev.c:442
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff81780810-ffffffff8178085f: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff817c1890)
Location: drivers/input/mousedev.c:442
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff817c1890-ffffffff817c18df: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff817e8d80)
Location: drivers/input/mousedev.c:442
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff817e8d80-ffffffff817e8dcf: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81829ab0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff81829ab0-ffffffff81829aff: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8185b440)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff8185b440-ffffffff8185b48f: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8192ec19)
Location: drivers/input/mousedev.c:439
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff8192df20-ffffffff8192df6f: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81935fb9)
Location: drivers/input/mousedev.c:439
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff819352b0-ffffffff819352ff: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81919be9)
Location: drivers/input/mousedev.c:439
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff81918b40-ffffffff81918b8f: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff819baeb0-ffffffff819baf14: mousedev_close_device (STB_LOCAL)
ffffffff81d2358b-ffffffff81d235a0: mousedev_close_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff81b1bb90-ffffffff81b1bc08: mousedev_close_device (STB_LOCAL)
ffffffff81eef47b-ffffffff81eef490: mousedev_close_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff81cad990-ffffffff81cada08: mousedev_close_device (STB_LOCAL)
ffffffff820a69d9-ffffffff820a69ee: mousedev_close_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff81d14f80-ffffffff81d14ff8: mousedev_close_device (STB_LOCAL)
ffffffff82127de6-ffffffff82127dfb: mousedev_close_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff81dcaba0-ffffffff81dcac18: mousedev_close_device (STB_LOCAL)
ffffffff82209767-ffffffff8220977c: mousedev_close_device.cold (STB_LOCAL)
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
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffff800010a9b5e0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffff800010a9b5e0-ffff800010a9b64c: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (c0b7d4a0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
c0b7d4a0-c0b7d4fc: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (c000000000b7bed0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
c000000000b7bed0-c000000000b7bf80: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffe0006abc9e)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffe0006abc9e-ffffffe0006abcf8: mousedev_close_device (STB_LOCAL)
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
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81810450)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff81810450-ffffffff8181049f: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff817d7ba0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff817d7ba0-ffffffff817d7bef: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8184f5d0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff8184f5d0-ffffffff8184f61f: mousedev_close_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mousedev_close_device(struct mousedev *mousedev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8186a9e0)
Location: drivers/input/mousedev.c:439
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mixdev_close_devices
```
**Symbols:**

```
ffffffff8186a9e0-ffffffff8186aa2f: mousedev_close_device (STB_LOCAL)
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
