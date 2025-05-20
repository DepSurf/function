# Function: <code>pciserial_init_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150c780)
Location: drivers/tty/serial/8250/8250_pci.c:4084
Inline: False
```
**Symbols:**

```
ffffffff8150c780-ffffffff8150c92b: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155ea80)
Location: drivers/tty/serial/8250/8250_pci.c:4124
Inline: False
```
**Symbols:**

```
ffffffff8155ea80-ffffffff8155ec30: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158b0d0)
Location: drivers/tty/serial/8250/8250_pci.c:3980
Inline: False
```
**Symbols:**

```
ffffffff8158b0d0-ffffffff8158b280: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159f350)
Location: drivers/tty/serial/8250/8250_pci.c:3619
Inline: True
```
**Symbols:**

```
ffffffff8159f350-ffffffff8159f4f5: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81604850)
Location: drivers/tty/serial/8250/8250_pci.c:3632
Inline: True
```
**Symbols:**

```
ffffffff81604850-ffffffff81604a7d: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163dab0)
Location: drivers/tty/serial/8250/8250_pci.c:3627
Inline: False
```
**Symbols:**

```
ffffffff8163dab0-ffffffff8163dcd5: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165bd20)
Location: drivers/tty/serial/8250/8250_pci.c:3737
Inline: False
```
**Symbols:**

```
ffffffff8165bd20-ffffffff8165bf0c: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:3829
Inline: False
```
**Symbols:**

```
ffffffff81691280-ffffffff8169142a: pciserial_init_one (STB_LOCAL)
ffffffff816915ec-ffffffff81691621: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
ffffffff816b3d70-ffffffff816b3f1a: pciserial_init_one (STB_LOCAL)
ffffffff816b40de-ffffffff816b4113: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4009
Inline: False
```
**Symbols:**

```
ffffffff81766de0-ffffffff81766f82: pciserial_init_one (STB_LOCAL)
ffffffff81767851-ffffffff81767886: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4052
Inline: False
```
**Symbols:**

```
ffffffff81781d20-ffffffff81781ec2: pciserial_init_one (STB_LOCAL)
ffffffff81c08096-ffffffff81c080cb: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4078
Inline: False
```
**Symbols:**

```
ffffffff81765670-ffffffff81765812: pciserial_init_one (STB_LOCAL)
ffffffff81bf9c5a-ffffffff81bf9c8f: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4121
Inline: False
```
**Symbols:**

```
ffffffff817e9f70-ffffffff817ea130: pciserial_init_one (STB_LOCAL)
ffffffff81cfa2b7-ffffffff81cfa2ec: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4005
Inline: False
```
**Symbols:**

```
ffffffff81929a30-ffffffff81929c23: pciserial_init_one (STB_LOCAL)
ffffffff81ec24b1-ffffffff81ec24fe: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a87730)
Location: drivers/tty/serial/8250/8250_pci.c:3993
Inline: False
```
**Symbols:**

```
ffffffff81a87730-ffffffff81a8798e: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad2b10)
Location: drivers/tty/serial/8250/8250_pci.c:3956
Inline: False
```
**Symbols:**

```
ffffffff81ad2b10-ffffffff81ad2d6e: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b26a60)
Location: drivers/tty/serial/8250/8250_pci.c:4212
Inline: False
```
**Symbols:**

```
ffffffff81b26a60-ffffffff81b26cbe: pciserial_init_one (STB_LOCAL)
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
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088f8e8)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
ffff80001088f8e8-ffff80001088fab8: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c098cac8)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
c098cac8-c098ccac: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c000000000937e70)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
c000000000937e70-c000000000938100: pciserial_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000559532)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
ffffffe000559532-ffffffe0005596b4: pciserial_init_one (STB_LOCAL)
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
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
ffffffff816797d0-ffffffff8167997a: pciserial_init_one (STB_LOCAL)
ffffffff81679b3e-ffffffff81679b73: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
ffffffff816588c0-ffffffff81658a6a: pciserial_init_one (STB_LOCAL)
ffffffff81658c2e-ffffffff81658c63: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
ffffffff816a7bb0-ffffffff816a7d5a: pciserial_init_one (STB_LOCAL)
ffffffff816a7f1e-ffffffff816a7f53: pciserial_init_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pciserial_init_one(struct pci_dev *dev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:4017
Inline: False
```
**Symbols:**

```
ffffffff816c2010-ffffffff816c21ba: pciserial_init_one (STB_LOCAL)
ffffffff816c237e-ffffffff816c23b3: pciserial_init_one.cold (STB_LOCAL)
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
