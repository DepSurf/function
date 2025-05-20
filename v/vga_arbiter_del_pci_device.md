# Function: <code>vga_arbiter_del_pci_device</code>

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
In drivers/gpu/vga/vgaarb.c (ffffffff815405d8)
Location: drivers/gpu/vga/vgaarb.c:613
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
In drivers/gpu/vga/vgaarb.c (ffffffff816413f4)
Location: drivers/gpu/vga/vgaarb.c:613
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
In drivers/gpu/vga/vgaarb.c (ffffffff816724d5)
Location: drivers/gpu/vga/vgaarb.c:694
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
In drivers/gpu/vga/vgaarb.c (ffffffff81686b2d)
Location: drivers/gpu/vga/vgaarb.c:694
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
In drivers/gpu/vga/vgaarb.c (ffffffff816f038d)
Location: drivers/gpu/vga/vgaarb.c:694
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
In drivers/gpu/vga/vgaarb.c (ffffffff8172ce51)
Location: drivers/gpu/vga/vgaarb.c:694
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
In drivers/gpu/vga/vgaarb.c (ffffffff8174f5f1)
Location: drivers/gpu/vga/vgaarb.c:694
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
In drivers/gpu/vga/vgaarb.c (ffffffff8178b127)
Location: drivers/gpu/vga/vgaarb.c:743
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
In drivers/gpu/vga/vgaarb.c (ffffffff817aed47)
Location: drivers/gpu/vga/vgaarb.c:743
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool vga_arbiter_del_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81874af0)
Location: drivers/gpu/vga/vgaarb.c:743
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:pci_notify
```
**Symbols:**

```
ffffffff81874af0-ffffffff81874bff: vga_arbiter_del_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool vga_arbiter_del_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81883680)
Location: drivers/gpu/vga/vgaarb.c:742
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:pci_notify
```
**Symbols:**

```
ffffffff81883680-ffffffff8188378f: vga_arbiter_del_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff818661b8)
Location: drivers/gpu/vga/vgaarb.c:743
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:pci_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff818f5805)
Location: drivers/gpu/vga/vgaarb.c:722
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:pci_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff817f4e94)
Location: drivers/pci/vgaarb.c:843
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:pci_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff8191f6e4)
Location: drivers/pci/vgaarb.c:843
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:pci_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff81962cf2)
Location: drivers/pci/vgaarb.c:836
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:pci_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff819ac35b)
Location: drivers/pci/vgaarb.c:844
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:pci_notify
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
In drivers/gpu/vga/vgaarb.c (ffff8000109c14d8)
Location: drivers/gpu/vga/vgaarb.c:743
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
In drivers/gpu/vga/vgaarb.c (c0a8e394)
Location: drivers/gpu/vga/vgaarb.c:743
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
In drivers/gpu/vga/vgaarb.c (c000000000a82700)
Location: drivers/gpu/vga/vgaarb.c:743
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
In drivers/gpu/vga/vgaarb.c (ffffffe000613bba)
Location: drivers/gpu/vga/vgaarb.c:743
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
In drivers/gpu/vga/vgaarb.c (ffffffff81773867)
Location: drivers/gpu/vga/vgaarb.c:743
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
In drivers/gpu/vga/vgaarb.c (ffffffff81753617)
Location: drivers/gpu/vga/vgaarb.c:743
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
In drivers/gpu/vga/vgaarb.c (ffffffff817a3bc7)
Location: drivers/gpu/vga/vgaarb.c:743
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
In drivers/gpu/vga/vgaarb.c (ffffffff817bda47)
Location: drivers/gpu/vga/vgaarb.c:743
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
</ul>
