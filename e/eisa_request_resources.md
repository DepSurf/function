# Function: <code>eisa_request_resources</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff828ee27b)
Location: drivers/eisa/eisa-bus.c:261
Inline: True
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff828ee27b-ffffffff828ee395: eisa_request_resources.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff82909714)
Location: drivers/eisa/eisa-bus.c:260
Inline: True
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff82909714-ffffffff82909836: eisa_request_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff82913119)
Location: drivers/eisa/eisa-bus.c:260
Inline: True
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff82913119-ffffffff8291323b: eisa_request_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int eisa_request_resources(struct eisa_root_device *root, struct eisa_device *edev, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff82d2595a)
Location: drivers/eisa/eisa-bus.c:260
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
**Symbols:**

```
ffffffff82d2595a-ffffffff82d25a71: eisa_request_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int eisa_request_resources(struct eisa_root_device *root, struct eisa_device *edev, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff83013efb)
Location: drivers/eisa/eisa-bus.c:260
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
**Symbols:**

```
ffffffff83013efb-ffffffff83014012: eisa_request_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int eisa_request_resources(struct eisa_root_device *root, struct eisa_device *edev, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff8321efdd)
Location: drivers/eisa/eisa-bus.c:260
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
**Symbols:**

```
ffffffff8321efdd-ffffffff8321f0ef: eisa_request_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int eisa_request_resources(struct eisa_root_device *root, struct eisa_device *edev, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff8330857a)
Location: drivers/eisa/eisa-bus.c:255
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
**Symbols:**

```
ffffffff8330857a-ffffffff833087ed: eisa_request_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int eisa_request_resources(struct eisa_root_device *root, struct eisa_device *edev, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff834c1b3b)
Location: drivers/eisa/eisa-bus.c:255
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
**Symbols:**

```
ffffffff834c1b3b-ffffffff834c1db1: eisa_request_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int eisa_request_resources(struct eisa_root_device *root, struct eisa_device *edev, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff83f01190)
Location: drivers/eisa/eisa-bus.c:255
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
**Symbols:**

```
ffffffff83f01190-ffffffff83f0154b: eisa_request_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int eisa_request_resources(struct eisa_root_device *root, struct eisa_device *edev, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff83727040)
Location: drivers/eisa/eisa-bus.c:255
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
**Symbols:**

```
ffffffff83727040-ffffffff837273fb: eisa_request_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int eisa_request_resources(struct eisa_root_device *root, struct eisa_device *edev, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff8395af60)
Location: drivers/eisa/eisa-bus.c:255
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
**Symbols:**

```
ffffffff8395af60-ffffffff8395b31b: eisa_request_resources (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff828f8f2d)
Location: drivers/eisa/eisa-bus.c:260
Inline: True
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff828f8f2d-ffffffff828f904f: eisa_request_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff828f0a16)
Location: drivers/eisa/eisa-bus.c:260
Inline: True
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff828f0a16-ffffffff828f0b38: eisa_request_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff8290d765)
Location: drivers/eisa/eisa-bus.c:260
Inline: True
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff8290d765-ffffffff8290d887: eisa_request_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff8291417b)
Location: drivers/eisa/eisa-bus.c:260
Inline: True
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff8291417b-ffffffff8291429d: eisa_request_resources.isra.0 (STB_LOCAL)
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
