# Function: <code>pci_release_resource</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814f45d0)
Location: drivers/pci/setup-res.c:400
Inline: False
```
**Symbols:**

```
ffffffff814f45d0-ffffffff814f4623: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81524680)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff81524680-ffffffff815246da: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8153a500)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff8153a500-ffffffff8153a55a: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8156a57a)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff8156a57a-ffffffff8156a5d4: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8158b54a)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff8158b54a-ffffffff8158b5a4: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff816325c1)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff816325c1-ffffffff8163261b: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81bf829d)
Location: drivers/pci/setup-res.c:394
Inline: False
```
**Symbols:**

```
ffffffff81bf829d-ffffffff81bf82f7: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81bea13c)
Location: drivers/pci/setup-res.c:394
Inline: False
```
**Symbols:**

```
ffffffff81bea13c-ffffffff81bea196: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81ce4f39)
Location: drivers/pci/setup-res.c:394
Inline: False
```
**Symbols:**

```
ffffffff81ce4f39-ffffffff81ce4f93: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81eab9bc)
Location: drivers/pci/setup-res.c:398
Inline: False
```
**Symbols:**

```
ffffffff81eab9bc-ffffffff81eaba22: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff818ecc30)
Location: drivers/pci/setup-res.c:409
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
```
**Symbols:**

```
ffffffff818ecc30-ffffffff818ecc9b: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81930110)
Location: drivers/pci/setup-res.c:409
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
```
**Symbols:**

```
ffffffff81930110-ffffffff8193017b: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81978aa0)
Location: drivers/pci/setup-res.c:413
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
```
**Symbols:**

```
ffffffff81978aa0-ffffffff81978b19: pci_release_resource (STB_GLOBAL)
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
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffff8000106f055c)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffff8000106f055c-ffff8000106f05e8: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c088b0a4)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
c088b0a4-c088b118: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c00000000086dba4)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
c00000000086dba4-c00000000086dc4c: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffe0004c410a)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffe0004c410a-ffffffe0004c417a: pci_release_resource (STB_GLOBAL)
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
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8157f3ca)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff8157f3ca-ffffffff8157f424: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8156e1aa)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff8156e1aa-ffffffff8156e204: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8157f29a)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff8157f29a-ffffffff8157f2f4: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_release_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8159974a)
Location: drivers/pci/setup-res.c:393
Inline: False
```
**Symbols:**

```
ffffffff8159974a-ffffffff815997a4: pci_release_resource (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
