# Function: <code>__pci_epc_create</code>

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
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d23f0)
Location: drivers/pci/endpoint/pci-epc-core.c:479
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff814d23f0-ffffffff814d2570: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81512830)
Location: drivers/pci/endpoint/pci-epc-core.c:485
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff81512830-ffffffff815129eb: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81547b10)
Location: drivers/pci/endpoint/pci-epc-core.c:484
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff81547b10-ffffffff81547c24: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155e2a0)
Location: drivers/pci/endpoint/pci-epc-core.c:542
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff8155e2a0-ffffffff8155e3b0: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff8158e895-ffffffff8158e8af: __pci_epc_create.cold (STB_LOCAL)
ffffffff8158e700-ffffffff8158e80d: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815b0320)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff815b0320-ffffffff815b043d: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816594e0)
Location: drivers/pci/endpoint/pci-epc-core.c:608
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff816594e0-ffffffff81659626: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816798e0)
Location: drivers/pci/endpoint/pci-epc-core.c:608
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff816798e0-ffffffff81679a26: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165c2c0)
Location: drivers/pci/endpoint/pci-epc-core.c:702
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff8165c2c0-ffffffff8165c406: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ce8f0)
Location: drivers/pci/endpoint/pci-epc-core.c:758
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff816ce8f0-ffffffff816cea36: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f7510)
Location: drivers/pci/endpoint/pci-epc-core.c:758
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff817f7510-ffffffff817f7675: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81922f80)
Location: drivers/pci/endpoint/pci-epc-core.c:762
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff81922f80-ffffffff819230f0: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81966c50)
Location: drivers/pci/endpoint/pci-epc-core.c:832
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff81966c50-ffffffff81966dc5: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b0360)
Location: drivers/pci/endpoint/pci-epc-core.c:831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff819b0360-ffffffff819b04fc: __pci_epc_create (STB_GLOBAL)
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
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071afa8)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffff80001071afa8-ffff80001071b0e0: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c08a4e1c)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
c08a4e1c-c08a4f24: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088c660)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
c00000000088c660-c00000000088c820: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e2f74)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffe0004e2f74-ffffffe0004e3098: __pci_epc_create (STB_GLOBAL)
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
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3ae0)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff815a3ae0-ffffffff815a3bfd: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81592c80)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff81592c80-ffffffff81592d9d: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a4070)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff815a4070-ffffffff815a418d: __pci_epc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_epc *__pci_epc_create(struct device *dev, const struct pci_epc_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815be470)
Location: drivers/pci/endpoint/pci-epc-core.c:596
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
**Symbols:**

```
ffffffff815be470-ffffffff815be58d: __pci_epc_create (STB_GLOBAL)
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
