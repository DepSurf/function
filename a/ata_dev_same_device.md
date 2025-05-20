# Function: <code>ata_dev_same_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c9840)
Location: drivers/ata/libata-core.c:3926
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff815c9840-ffffffff815c99a8: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81621ff0)
Location: drivers/ata/libata-core.c:4102
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81621ff0-ffffffff81622158: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81652b70)
Location: drivers/ata/libata-core.c:4144
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81652b70-ffffffff81652cd8: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816672c0)
Location: drivers/ata/libata-core.c:4221
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff816672c0-ffffffff81667428: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d0920)
Location: drivers/ata/libata-core.c:4231
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff816d0920-ffffffff816d0a88: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4227
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff8170d070-ffffffff8170d178: ata_dev_same_device (STB_LOCAL)
ffffffff81712ff5-ffffffff8171305d: ata_dev_same_device.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4228
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff8172f4f0-ffffffff8172f5f8: ata_dev_same_device (STB_LOCAL)
ffffffff817354a5-ffffffff8173550d: ata_dev_same_device.cold.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff8176ac80-ffffffff8176ad7d: ata_dev_same_device (STB_LOCAL)
ffffffff81770ed4-ffffffff81770f41: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff8178ecf0-ffffffff8178eded: ata_dev_same_device (STB_LOCAL)
ffffffff81794ed2-ffffffff81794f3f: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3605
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81852c10-ffffffff81852d0d: ata_dev_same_device (STB_LOCAL)
ffffffff81859234-ffffffff818592a1: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3605
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81862f70-ffffffff8186306d: ata_dev_same_device (STB_LOCAL)
ffffffff81c17247-ffffffff81c172b4: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3605
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81845b00-ffffffff81845bfd: ata_dev_same_device (STB_LOCAL)
ffffffff81c08e72-ffffffff81c08edf: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3656
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff818d2600-ffffffff818d26fd: ata_dev_same_device (STB_LOCAL)
ffffffff81d0d735-ffffffff81d0d7a2: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3683
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81a22db0-ffffffff81a22f11: ata_dev_same_device (STB_LOCAL)
ffffffff81ed6670-ffffffff81ed66e2: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba4a30)
Location: drivers/ata/libata-core.c:3685
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81ba4a30-ffffffff81ba4c02: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfb130)
Location: drivers/ata/libata-core.c:3878
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81bfb130-ffffffff81bfb302: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c50bc0)
Location: drivers/ata/libata-core.c:3875
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81c50bc0-ffffffff81c50d92: ata_dev_same_device (STB_LOCAL)
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
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010997ae0)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffff800010997ae0-ffff800010997c48: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6869c)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
c0a6869c-c0a687f8: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5af90)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
c000000000a5af90-c000000000a5b3a8: ata_dev_same_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f92da)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffe0005f92da-ffffffe0005f93f6: ata_dev_same_device (STB_LOCAL)
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
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81753e60-ffffffff81753f5d: ata_dev_same_device (STB_LOCAL)
ffffffff81759fe2-ffffffff8175a04f: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81733d00-ffffffff81733dfd: ata_dev_same_device (STB_LOCAL)
ffffffff81739e82-ffffffff81739eef: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff81783b70-ffffffff81783c6d: ata_dev_same_device (STB_LOCAL)
ffffffff81789d52-ffffffff81789dbf: ata_dev_same_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_dev_same_device(struct ata_device *dev, unsigned int new_class, const u16 *new_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_reread_id
```
**Symbols:**

```
ffffffff8179da30-ffffffff8179db2d: ata_dev_same_device (STB_LOCAL)
ffffffff817a3ba2-ffffffff817a3c0f: ata_dev_same_device.cold (STB_LOCAL)
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
