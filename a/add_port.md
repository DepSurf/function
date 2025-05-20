# Function: <code>add_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815185c0)
Location: drivers/char/virtio_console.c:1390
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff815185c0-ffffffff8151896e: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8156b2e0)
Location: drivers/char/virtio_console.c:1397
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8156b2e0-ffffffff8156b68a: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81597a50)
Location: drivers/char/virtio_console.c:1396
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81597a50-ffffffff81597dfa: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815aba10)
Location: drivers/char/virtio_console.c:1404
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff815aba10-ffffffff815abd9f: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816123b0)
Location: drivers/char/virtio_console.c:1401
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff816123b0-ffffffff8161273f: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164bde0)
Location: drivers/char/virtio_console.c:1400
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8164bde0-ffffffff8164c14d: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81669f50)
Location: drivers/char/virtio_console.c:1373
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81669f50-ffffffff8166a2bd: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8169f740-ffffffff8169fa45: add_port (STB_LOCAL)
ffffffff816a07ac-ffffffff816a0839: add_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff816c24e0-ffffffff816c27f8: add_port (STB_LOCAL)
ffffffff816c3568-ffffffff816c35ef: add_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1358
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff817760c0-ffffffff81776409: add_port.isra.0 (STB_LOCAL)
ffffffff81777bb0-ffffffff81777c2d: add_port.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1358
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81790df0-ffffffff81791139: add_port.isra.0 (STB_LOCAL)
ffffffff81c087a3-ffffffff81c08820: add_port.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1358
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81773ec0-ffffffff817741c3: add_port.isra.0 (STB_LOCAL)
ffffffff81bfa345-ffffffff81bfa3c2: add_port.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1358
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff817fa2a0-ffffffff817fa5a3: add_port.isra.0 (STB_LOCAL)
ffffffff81cfacf9-ffffffff81cfad76: add_port.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1359
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81937670-ffffffff81937984: add_port.isra.0 (STB_LOCAL)
ffffffff81ec32c8-ffffffff81ec3341: add_port.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81a97b80)
Location: drivers/char/virtio_console.c:1354
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81a97b80-ffffffff81a97ef8: add_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81ae3390)
Location: drivers/char/virtio_console.c:1355
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81ae3390-ffffffff81ae3703: add_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81b36750)
Location: drivers/char/virtio_console.c:1323
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81b36750-ffffffff81b36af2: add_port.isra.0 (STB_LOCAL)
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
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b52b0)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffff8000108b52b0-ffff8000108b5630: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09af3c8)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
c09af3c8-c09af714: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094e970)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
c00000000094e970-c00000000094edbc: add_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe0005668f0)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffe0005668f0-ffffffe000566bba: add_port (STB_LOCAL)
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
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81687f30-ffffffff81688248: add_port (STB_LOCAL)
ffffffff81688fb8-ffffffff8168903f: add_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81665a50-ffffffff81665d47: add_port (STB_LOCAL)
ffffffff81666a49-ffffffff81666ad0: add_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff816b6210-ffffffff816b650d: add_port (STB_LOCAL)
ffffffff816b721f-ffffffff816b72a6: add_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int add_port(struct ports_device *portdev, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1360
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff816d0800-ffffffff816d0b0f: add_port (STB_LOCAL)
ffffffff816d1866-ffffffff816d18ed: add_port.cold (STB_LOCAL)
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
