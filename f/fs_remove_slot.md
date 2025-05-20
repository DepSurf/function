# Function: <code>fs_remove_slot</code>

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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c8cc)
Location: drivers/pci/hotplug/pci_hotplug_core.c:374
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81498fef)
Location: drivers/pci/hotplug/pci_hotplug_core.c:374
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814babdf)
Location: drivers/pci/hotplug/pci_hotplug_core.c:371
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c53cb)
Location: drivers/pci/hotplug/pci_hotplug_core.c:371
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81505957)
Location: drivers/pci/hotplug/pci_hotplug_core.c:371
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81536879)
Location: drivers/pci/hotplug/pci_hotplug_core.c:357
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154dbcd)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157d9eb)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f44b)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fs_remove_slot(struct pci_slot *pci_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647cd0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: False
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
**Symbols:**

```
ffffffff81647cd0-ffffffff81647e01: fs_remove_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fs_remove_slot(struct pci_slot *pci_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166ce50)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: False
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
**Symbols:**

```
ffffffff8166ce50-ffffffff8166cf81: fs_remove_slot (STB_LOCAL)
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f86f)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c15cb)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e6deb)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190bd7b)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194f3fb)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8199882b)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffff800010707978)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c00000000087ffe8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d537c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592c5b)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81581deb)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159319b)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ad61b)
Location: drivers/pci/hotplug/pci_hotplug_core.c:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
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
