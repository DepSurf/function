# Function: <code>pci_get_dev_by_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143ab20)
Location: drivers/pci/search.c:260
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_dev_present
```
**Symbols:**

```
ffffffff8143ab20-ffffffff8143abaa: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81486a40)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff81486a40-ffffffff81486aca: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a81f0)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff814a81f0-ffffffff814a827a: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b21b0)
Location: drivers/pci/search.c:268
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff814b21b0-ffffffff814b221b: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f18a0)
Location: drivers/pci/search.c:268
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff814f18a0-ffffffff814f190b: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521b30)
Location: drivers/pci/search.c:269
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff81521b30-ffffffff81521b9b: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537960)
Location: drivers/pci/search.c:269
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff81537960-ffffffff815379cc: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/search.c (0)
Location: drivers/pci/search.c:265
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff815672f0-ffffffff81567365: pci_get_dev_by_id (STB_LOCAL)
ffffffff815676fc-ffffffff81567717: pci_get_dev_by_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81588650)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff81588650-ffffffff815886bd: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f230)
Location: drivers/pci/search.c:270
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff8162f230-ffffffff8162f29d: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816548c0)
Location: drivers/pci/search.c:270
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff816548c0-ffffffff8165492d: pci_get_dev_by_id (STB_LOCAL)
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
In drivers/pci/search.c (ffffffff8163740c)
Location: drivers/pci/search.c:268
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
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
In drivers/pci/search.c (ffffffff816a767c)
Location: drivers/pci/search.c:268
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
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
In drivers/pci/search.c (ffffffff817ca092)
Location: drivers/pci/search.c:268
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
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
In drivers/pci/search.c (ffffffff818e7b32)
Location: drivers/pci/search.c:268
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
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
In drivers/pci/search.c (ffffffff8192b152)
Location: drivers/pci/search.c:268
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
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
In drivers/pci/search.c (ffffffff819739d2)
Location: drivers/pci/search.c:268
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_base_class
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
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
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106ecb98)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffff8000106ecb98-ffff8000106ecc18: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0887de4)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
c0887de4-c0887e7c: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0000000008689e0)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
c0000000008689e0-c000000000868a88: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c1a76)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffe0004c1a76-ffffffe0004c1aea: pci_get_dev_by_id (STB_LOCAL)
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
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c4e0)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff8157c4e0-ffffffff8157c54d: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b2b0)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff8156b2b0-ffffffff8156b31d: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c3a0)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff8157c3a0-ffffffff8157c40d: pci_get_dev_by_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_dev *pci_get_dev_by_id(const struct pci_device_id *id, struct pci_dev *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81596850)
Location: drivers/pci/search.c:264
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
**Symbols:**

```
ffffffff81596850-ffffffff815968bd: pci_get_dev_by_id (STB_LOCAL)
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
