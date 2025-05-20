# Function: <code>edac_queue_work</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff8175f7a0)
Location: drivers/edac/wq.c:5
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff8175f7a0-ffffffff8175f7c2: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff817d1830)
Location: drivers/edac/wq.c:5
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff817d1830-ffffffff817d1852: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff8181a5e0)
Location: drivers/edac/wq.c:5
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff8181a5e0-ffffffff8181a602: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81845dd0)
Location: drivers/edac/wq.c:5
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff81845dd0-ffffffff81845df2: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81888bb0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff81888bb0-ffffffff81888bd2: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff818bab60)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff818bab60-ffffffff818bab82: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff8198b3c0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff8198b3c0-ffffffff8198b3e2: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff8198efd0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff8198efd0-ffffffff8198eff2: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81973620)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff81973620-ffffffff81973642: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81a1c320)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff81a1c320-ffffffff81a1c342: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81b853c0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff81b853c0-ffffffff81b853ee: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81d243c0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff81d243c0-ffffffff81d243ee: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81d8d5d0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff81d8d5d0-ffffffff81d8d5fe: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81e44e80)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_device.c:edac_device_workq_function
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
**Symbols:**

```
ffffffff81e44e80-ffffffff81e44eae: edac_queue_work (STB_GLOBAL)
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
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffff800010b130c8)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffff800010b130c8-ffff800010b13108: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (c0bf1088)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
c0bf1088-c0bf10bc: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (c000000000c079a0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
c000000000c079a0-c000000000c079e8: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffe0006ffaf4)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffe0006ffaf4-ffffffe0006ffb30: edac_queue_work (STB_GLOBAL)
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
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff818609e0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff818609e0-ffffffff81860a02: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff81827fb0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff81827fb0-ffffffff81827fd2: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff818b0010)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff818b0010-ffffffff818b0032: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool edac_queue_work(struct delayed_work *work, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/wq.c (ffffffff818cc2a0)
Location: drivers/edac/wq.c:6
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff818cc2a0-ffffffff818cc2c2: edac_queue_work (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
