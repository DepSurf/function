# Function: <code>__pci_read_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81430580)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff81430580-ffffffff8143095f: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147bcf0)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff8147bcf0-ffffffff8147c0c8: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149d240)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff8149d240-ffffffff8149d62d: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a7150)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff814a7150-ffffffff814a7518: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e5aa0)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff814e5aa0-ffffffff814e5e68: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81514f30)
Location: drivers/pci/probe.c:181
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff81514f30-ffffffff815152e0: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152a650)
Location: drivers/pci/probe.c:180
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff8152a650-ffffffff8152aa00: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:180
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff8155c7d3-ffffffff8155c84c: __pci_read_base.cold (STB_LOCAL)
ffffffff81559d90-ffffffff8155a0e8: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff8157d83b-ffffffff8157d8b4: __pci_read_base.cold (STB_LOCAL)
ffffffff8157ae00-ffffffff8157b158: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:176
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff8162317c-ffffffff816231f5: __pci_read_base.cold (STB_LOCAL)
ffffffff816209c0-ffffffff81620cf4: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:176
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff81bf7362-ffffffff81bf73db: __pci_read_base.cold (STB_LOCAL)
ffffffff81647060-ffffffff81647394: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:177
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff81be8f0a-ffffffff81be8f83: __pci_read_base.cold (STB_LOCAL)
ffffffff81629970-ffffffff81629ca0: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:178
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff81ce333a-ffffffff81ce33b3: __pci_read_base.cold (STB_LOCAL)
ffffffff81699360-ffffffff81699690: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:177
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff81ea9e50-ffffffff81ea9ec8: __pci_read_base.cold (STB_LOCAL)
ffffffff817ba890-ffffffff817bac03: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d5840)
Location: drivers/pci/probe.c:177
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff818d5840-ffffffff818d5c25: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81918a80)
Location: drivers/pci/probe.c:177
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff81918a80-ffffffff81918e65: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819610f0)
Location: drivers/pci/probe.c:176
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff819610f0-ffffffff8196150b: __pci_read_base (STB_GLOBAL)
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
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dd880)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffff8000106dd880-ffff8000106ddbf8: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0879368)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
c0879368-c087985c: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000855c80)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
c000000000855c80-c000000000856120: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b5bc6)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffe0004b5bc6-ffffffe0004b5f00: __pci_read_base (STB_GLOBAL)
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
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff81571d5b-ffffffff81571dd4: __pci_read_base.cold (STB_LOCAL)
ffffffff8156f320-ffffffff8156f678: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff815604bb-ffffffff81560534: __pci_read_base.cold (STB_LOCAL)
ffffffff8155da80-ffffffff8155ddd8: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff8157158b-ffffffff81571604: __pci_read_base.cold (STB_LOCAL)
ffffffff8156eb50-ffffffff8156eea8: __pci_read_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __pci_read_base(struct pci_dev *dev, enum pci_bar_type type, struct resource *res, unsigned int pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bases
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff8158ba6b-ffffffff8158bae4: __pci_read_base.cold (STB_LOCAL)
ffffffff81589030-ffffffff81589388: __pci_read_base (STB_GLOBAL)
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
