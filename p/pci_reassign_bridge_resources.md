# Function: <code>pci_reassign_bridge_resources</code>

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
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f8860)
Location: drivers/pci/setup-bus.c:2093
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff814f8860-ffffffff814f8b0f: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815292b0)
Location: drivers/pci/setup-bus.c:2088
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff815292b0-ffffffff8152955f: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153f150)
Location: drivers/pci/setup-bus.c:2090
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff8153f150-ffffffff8153f412: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2059
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff8156ed43-ffffffff8156edd7: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff8156e4b0-ffffffff8156e6e6: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff8158fd5b-ffffffff8158fdf3: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff8158f490-ffffffff8158f6c2: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2123
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff81637867-ffffffff816378f7: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff81636ee0-ffffffff816371fd: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2124
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff81bf8cd0-ffffffff81bf8d60: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff8165bfa0-ffffffff8165c2bd: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2124
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff81beab28-ffffffff81beabb7: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff8163e540-ffffffff8163e864: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2124
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff81ce59bf-ffffffff81ce5a4d: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff816af0b0-ffffffff816af3fc: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2124
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff81eac48b-ffffffff81eac512: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff817d2550-ffffffff817d28a3: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f2db0)
Location: drivers/pci/setup-bus.c:2228
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff818f2db0-ffffffff818f3150: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff819361d0)
Location: drivers/pci/setup-bus.c:2219
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff819361d0-ffffffff81936570: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197f030)
Location: drivers/pci/setup-bus.c:2229
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff8197f030-ffffffff8197f3c9: pci_reassign_bridge_resources (STB_GLOBAL)
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
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f4a50)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffff8000106f4a50-ffff8000106f4d0c: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088f514)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
c088f514-c088f7d0: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c0000000008732a0)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
c0000000008732a0-c0000000008735f4: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c7a66)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffe0004c7a66-ffffffe0004c7c8a: pci_reassign_bridge_resources (STB_GLOBAL)
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
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff81583bdf-ffffffff81583c73: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff81583310-ffffffff81583546: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff815729bb-ffffffff81572a53: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff815720f0-ffffffff81572322: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff81583aab-ffffffff81583b43: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff815831e0-ffffffff81583412: pci_reassign_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_reassign_bridge_resources(struct pci_dev *bridge, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2071
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_resize_resource
```
**Symbols:**

```
ffffffff8159df5b-ffffffff8159dff3: pci_reassign_bridge_resources.cold (STB_LOCAL)
ffffffff8159d690-ffffffff8159d8c2: pci_reassign_bridge_resources (STB_GLOBAL)
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
