# Function: <code>pciserial_init_ports</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150c550)
Location: drivers/tty/serial/8250/8250_pci.c:3947
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff8150c550-ffffffff8150c774: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155e870)
Location: drivers/tty/serial/8250/8250_pci.c:3993
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff8155e870-ffffffff8155ea74: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158ae60)
Location: drivers/tty/serial/8250/8250_pci.c:3844
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff8158ae60-ffffffff8158b078: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159f0f0)
Location: drivers/tty/serial/8250/8250_pci.c:3483
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
```
**Symbols:**

```
ffffffff8159f0f0-ffffffff8159f2f7: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816045e0)
Location: drivers/tty/serial/8250/8250_pci.c:3496
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
```
**Symbols:**

```
ffffffff816045e0-ffffffff816047f2: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163d830)
Location: drivers/tty/serial/8250/8250_pci.c:3491
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff8163d830-ffffffff8163da52: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165bab0)
Location: drivers/tty/serial/8250/8250_pci.c:3601
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff8165bab0-ffffffff8165bccf: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3693
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff816915b9-ffffffff816915ec: pciserial_init_ports.cold (STB_LOCAL)
ffffffff81691040-ffffffff81691227: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff816b40ab-ffffffff816b40de: pciserial_init_ports.cold (STB_LOCAL)
ffffffff816b3a80-ffffffff816b3d1f: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3858
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff8176780d-ffffffff8176783d: pciserial_init_ports.cold (STB_LOCAL)
ffffffff817669b0-ffffffff81766c45: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3901
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81c08052-ffffffff81c08082: pciserial_init_ports.cold (STB_LOCAL)
ffffffff817818f0-ffffffff81781b87: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3921
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81bf9c13-ffffffff81bf9c43: pciserial_init_ports.cold (STB_LOCAL)
ffffffff81765150-ffffffff817653ee: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3964
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81cfa25e-ffffffff81cfa28e: pciserial_init_ports.cold (STB_LOCAL)
ffffffff817e9890-ffffffff817e9b28: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3850
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81ec2465-ffffffff81ec2495: pciserial_init_ports.cold (STB_LOCAL)
ffffffff819291f0-ffffffff81929504: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a85ba0)
Location: drivers/tty/serial/8250/8250_pci.c:3838
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81a85ba0-ffffffff81a85eeb: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad1300)
Location: drivers/tty/serial/8250/8250_pci.c:3801
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81ad1300-ffffffff81ad1634: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b25160)
Location: drivers/tty/serial/8250/8250_pci.c:4057
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81b25160-ffffffff81b25494: pciserial_init_ports (STB_GLOBAL)
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
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088f5f0)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffff80001088f5f0-ffff80001088f898: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c098c7c4)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
c098c7c4-c098ca84: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c000000000937aa0)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
c000000000937aa0-c000000000937de0: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000559274)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffe000559274-ffffffe0005594e4: pciserial_init_ports (STB_GLOBAL)
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
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81679b0b-ffffffff81679b3e: pciserial_init_ports.cold (STB_LOCAL)
ffffffff816794e0-ffffffff8167977f: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff81658bfb-ffffffff81658c2e: pciserial_init_ports.cold (STB_LOCAL)
ffffffff816585d0-ffffffff8165886f: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff816a7eeb-ffffffff816a7f1e: pciserial_init_ports.cold (STB_LOCAL)
ffffffff816a78c0-ffffffff816a7b5f: pciserial_init_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct serial_private *pciserial_init_ports(struct pci_dev *dev, const struct pciserial_board *board);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3866
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
**Symbols:**

```
ffffffff816c234b-ffffffff816c237e: pciserial_init_ports.cold (STB_LOCAL)
ffffffff816c1d20-ffffffff816c1fbf: pciserial_init_ports (STB_GLOBAL)
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
