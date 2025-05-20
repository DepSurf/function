# Function: <code>register_client</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff815415b0)
Location: drivers/gpu/vga/vga_switcheroo.c:234
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff815415b0-ffffffff815416a7: register_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816425e0)
Location: drivers/gpu/vga/vga_switcheroo.c:272
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff816425e0-ffffffff816426d7: register_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816736c0)
Location: drivers/gpu/vga/vga_switcheroo.c:272
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff816736c0-ffffffff816737b7: register_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81687940)
Location: drivers/gpu/vga/vga_switcheroo.c:273
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81687940-ffffffff81687a37: register_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816f1210)
Location: drivers/gpu/vga/vga_switcheroo.c:273
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff816f1210-ffffffff816f1307: register_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172dda0)
Location: drivers/gpu/vga/vga_switcheroo.c:290
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff8172dda0-ffffffff8172de9f: register_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81750560)
Location: drivers/gpu/vga/vga_switcheroo.c:292
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81750560-ffffffff8175065f: register_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff8178bf70-ffffffff8178c061: register_client (STB_LOCAL)
ffffffff8178c699-ffffffff8178c6af: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff817afeb0-ffffffff817affa1: register_client (STB_LOCAL)
ffffffff817b0315-ffffffff817b032b: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff818757d0-ffffffff818758c1: register_client (STB_LOCAL)
ffffffff81876292-ffffffff818762a8: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff818840b0-ffffffff818841a1: register_client (STB_LOCAL)
ffffffff81c189d1-ffffffff81c189e7: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81866930-ffffffff81866a21: register_client (STB_LOCAL)
ffffffff81c0a7c5-ffffffff81c0a7db: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff818f5f20-ffffffff818f601f: register_client (STB_LOCAL)
ffffffff81d0f50a-ffffffff81d0f534: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81a46c00-ffffffff81a46d11: register_client (STB_LOCAL)
ffffffff81eda179-ffffffff81eda1a3: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81bcdb80-ffffffff81bcdc9e: register_client (STB_LOCAL)
ffffffff8209ccec-ffffffff8209cd00: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81c25770-ffffffff81c2588e: register_client (STB_LOCAL)
ffffffff8211dbf7-ffffffff8211dc0b: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81cd7ec0-ffffffff81cd800d: register_client (STB_LOCAL)
ffffffff821ff154-ffffffff821ff168: register_client.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81774990-ffffffff81774a81: register_client (STB_LOCAL)
ffffffff81774df5-ffffffff81774e0b: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff81754740-ffffffff81754831: register_client (STB_LOCAL)
ffffffff81754ba5-ffffffff81754bbb: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff817a4d30-ffffffff817a4e21: register_client (STB_LOCAL)
ffffffff817a5195-ffffffff817a51ab: register_client.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int register_client(struct pci_dev *pdev, const struct vga_switcheroo_client_ops *ops, enum vga_switcheroo_client_id id, struct pci_dev *vga_dev, bool active, bool driver_power_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: drivers/gpu/vga/vga_switcheroo.c:291
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_audio_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
```
**Symbols:**

```
ffffffff817bebb0-ffffffff817beca1: register_client (STB_LOCAL)
ffffffff817bf015-ffffffff817bf02b: register_client.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *vga_dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>pdev, ops, id, active, driver_power_control</code> ➡️ <code>pdev, ops, id, vga_dev, active, driver_power_control</code>
</li>
</ul>
</details>
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
