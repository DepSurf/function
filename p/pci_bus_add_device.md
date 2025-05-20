# Function: <code>pci_bus_add_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f140)
Location: drivers/pci/bus.c:280
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8142f140-ffffffff8142f1a6: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8147aec0)
Location: drivers/pci/bus.c:311
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8147aec0-ffffffff8147af51: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8149c340)
Location: drivers/pci/bus.c:311
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8149c340-ffffffff8149c3d1: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a6100)
Location: drivers/pci/bus.c:311
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814a6100-ffffffff814a618c: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e4f40)
Location: drivers/pci/bus.c:311
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814e4f40-ffffffff814e4fcc: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81514420)
Location: drivers/pci/bus.c:310
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81514420-ffffffff815144ad: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81529b80)
Location: drivers/pci/bus.c:310
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81529b80-ffffffff81529c0d: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81558ef9-ffffffff81558f1f: pci_bus_add_device.cold (STB_LOCAL)
ffffffff81558d90-ffffffff81558e02: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8157a4e6-ffffffff8157a50c: pci_bus_add_device.cold (STB_LOCAL)
ffffffff8157a330-ffffffff8157a3a2: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8161f611-ffffffff8161f627: pci_bus_add_device.cold (STB_LOCAL)
ffffffff8161f450-ffffffff8161f4bb: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81bf6f0e-ffffffff81bf6f24: pci_bus_add_device.cold (STB_LOCAL)
ffffffff81645c40-ffffffff81645cab: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81be8d81-ffffffff81be8d97: pci_bus_add_device.cold (STB_LOCAL)
ffffffff81628980-ffffffff816289eb: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81ce317b-ffffffff81ce3191: pci_bus_add_device.cold (STB_LOCAL)
ffffffff81698300-ffffffff8169836b: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81ea9c6f-ffffffff81ea9c85: pci_bus_add_device.cold (STB_LOCAL)
ffffffff817b95e0-ffffffff817b9657: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d41e0)
Location: drivers/pci/bus.c:313
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff818d41e0-ffffffff818d4266: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81917430)
Location: drivers/pci/bus.c:334
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81917430-ffffffff819174c0: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195f540)
Location: drivers/pci/bus.c:334
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8195f540-ffffffff8195f5d0: pci_bus_add_device (STB_GLOBAL)
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
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dcc30)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffff8000106dcc30-ffff8000106dccf4: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c0878830)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c0878830-c08788d0: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c000000000854d40)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c000000000854d40-c000000000854e3c: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b50ba)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffe0004b50ba-ffffffe0004b516a: pci_bus_add_device (STB_GLOBAL)
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
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8156e9fc-ffffffff8156ea22: pci_bus_add_device.cold (STB_LOCAL)
ffffffff8156e840-ffffffff8156e8b2: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8155d166-ffffffff8155d18c: pci_bus_add_device.cold (STB_LOCAL)
ffffffff8155cfb0-ffffffff8155d022: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8156e236-ffffffff8156e25c: pci_bus_add_device.cold (STB_LOCAL)
ffffffff8156e080-ffffffff8156e0f2: pci_bus_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:309
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81588716-ffffffff8158873c: pci_bus_add_device.cold (STB_LOCAL)
ffffffff81588560-ffffffff815885d2: pci_bus_add_device (STB_GLOBAL)
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
