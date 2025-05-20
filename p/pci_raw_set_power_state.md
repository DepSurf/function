# Function: <code>pci_raw_set_power_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81433cc0)
Location: drivers/pci/pci.c:588
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_power_up
```
**Symbols:**

```
ffffffff81433cc0-ffffffff81433efa: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147f640)
Location: drivers/pci/pci.c:609
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_power_up
```
**Symbols:**

```
ffffffff8147f640-ffffffff8147f89f: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a0c80)
Location: drivers/pci/pci.c:635
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_power_up
```
**Symbols:**

```
ffffffff814a0c80-ffffffff814a0ee3: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aa900)
Location: drivers/pci/pci.c:630
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_power_up
```
**Symbols:**

```
ffffffff814aa900-ffffffff814aab51: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814e9b20)
Location: drivers/pci/pci.c:631
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_power_up
```
**Symbols:**

```
ffffffff814e9b20-ffffffff814e9d71: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81519260)
Location: drivers/pci/pci.c:643
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_power_up
```
**Symbols:**

```
ffffffff81519260-ffffffff815194b0: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152ecd0)
Location: drivers/pci/pci.c:814
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_power_up
```
**Symbols:**

```
ffffffff8152ecd0-ffffffff8152ef10: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_power_up
```
**Symbols:**

```
ffffffff8155e460-ffffffff8155e675: pci_raw_set_power_state (STB_LOCAL)
ffffffff8156492c-ffffffff8156496d: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff8157f510-ffffffff8157f72c: pci_raw_set_power_state (STB_LOCAL)
ffffffff81585c2c-ffffffff81585c6d: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:865
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff81627150-ffffffff8162736a: pci_raw_set_power_state (STB_LOCAL)
ffffffff8162cb99-ffffffff8162cc4c: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1005
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff8164cdf0-ffffffff8164d00a: pci_raw_set_power_state (STB_LOCAL)
ffffffff81bf7d20-ffffffff81bf7dd3: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1035
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff8162f970-ffffffff8162fb80: pci_raw_set_power_state (STB_LOCAL)
ffffffff81be9bc7-ffffffff81be9c7a: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1045
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff8169e440-ffffffff8169e650: pci_raw_set_power_state (STB_LOCAL)
ffffffff81ce455d-ffffffff81ce4610: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e1f50)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffff8000106e1f50-ffff8000106e2188: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087dbd0)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
c087dbd0-c087de30: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085b580)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
c00000000085b580-c00000000085b878: pci_raw_set_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004b9a96)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffe0004b9a96-ffffffe0004b9c66: pci_raw_set_power_state (STB_LOCAL)
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
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff81573a30-ffffffff81573c4c: pci_raw_set_power_state (STB_LOCAL)
ffffffff8157a14c-ffffffff8157a18d: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff81562190-ffffffff815623ac: pci_raw_set_power_state (STB_LOCAL)
ffffffff8156888c-ffffffff815688cd: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff81573260-ffffffff8157347c: pci_raw_set_power_state (STB_LOCAL)
ffffffff8157997c-ffffffff815799bd: pci_raw_set_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_raw_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff8158d740-ffffffff8158d95c: pci_raw_set_power_state (STB_LOCAL)
ffffffff81593e2c-ffffffff81593e6d: pci_raw_set_power_state.cold (STB_LOCAL)
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
